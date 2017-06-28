# about-maven
# maven的常用命令
compile
compile是maven工程的编译命令，作用是将src/main/java下的文件编译为class文件输出到target目录下。

cmd进入命令状态，执行mvn compile，如下图提示成功：
 


 查看 target目录，class文件已生成，编译完成。
 
test
test是maven工程的测试命令，会执行src/test/java下的单元测试类。
cmd执行mvn test执行src/test/java下单元测试类，下图为测试结果，运行1个测试用例，全部成功。

 



clean
clean是maven工程的清理命令，执行 clean会删除target目录的内容。

package
package是maven工程的打包命令，对于java工程执行package打成jar包，对于web工程打成war包。

install
install是maven工程的安装命令，执行install将maven打成jar包或war包发布到本地仓库。
从运行结果中，可以看出：
当后面的命令执行时，前面的操作过程也都会自动执行，

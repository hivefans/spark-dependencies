spark-dependencies
==================

windows 或者 linux 编译Spark 时依赖的一些jar包，如果你的系统编译失败的话，可以直接把这几个文件夹直接copy到你的电脑上，然后再编译就可以了。

windows 存放目录：
C:\Users\${user.name}\

linux 存放目录：
xxxx@xxx.xxx.xxx.xxx:~$ ~/ 


当前用户目录下，直接覆盖原先的文件夹


两个jar包：
 带有assembly 的是用 ./sbt/sbt assembly 编译出来的，可以直接导入scala工程使用
 带有root的是用 ./sbt/sbt package 编译出来的，不带有相关的依赖class文件，只有spark的class文件


contact
==================
joey.wen@outlook.com

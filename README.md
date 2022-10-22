# datax
阿里云开源的datax（包含clickhousewriter插件）的工具包（datax.zip）
datax目录下有七个目录，分别是：
--bin
--conf
--job
--lib
--plugin
--script
--tmp
我们主要就是在job目录下编写json工作文件，将json文件作为输入,json文件中要配置读写的插件，读写的插件在plugin目录下，利用bin目录下的datax.py将json文件运行起来。

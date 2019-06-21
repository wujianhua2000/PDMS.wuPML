# PDMS.wuPML
my PDMS PML code

	....\PMLLIB
	....\PMLLIB\wolfgang\
	....\PMLLIB\wolfgang\functions
	....\PMLLIB\wolfgang\objects

文件

	....\PMLLIB\pml.index

可以手工添加，使用 PML INDEX 似乎无法很好的更新上述文件的内容，也可能是我的客户端的功能被削弱。

大致的内容如下：

	/wolfgang/functions
	......
	wuXmlDouble.pmlfnc
	wuXmlEntityBasic.pmlfnc
	wuXmlEntityCartesian.pmlfnc
	......

当编写了新的代码的时候，可以自己修改 pml.index 文件的内容。

当执行一个命令流的时候，在 command window 内输入

	$m  d:\code-PML\proc-list-gene-wall.mac



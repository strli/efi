# 提取EFI固件中的数据

所需工具：windows、AIAD64 工程版

打开AIAD64->工具->ACPI浏览器

点击Save Table，然后保存所有的文件。

导出以后的文件格式为.bin的二进制文件，需要反编译才能看到其中的函数。

反编译工具下载地址：

https://acpica.org/downloads

windows系统选windows即可

linux下载二进制文件，编译安装即可

（需要sudo apt install bison flex)

介绍文档：

https://acpica.org/sites/acpica/files/aslcompiler_10.pdf

安装以后有以下工具：

iasl

acpixtract

acpiexec

acpihelp

acpinames

acpisrc

acpibin



使用方法，将提取出的dsdt.bin等文件改后缀名为.aml



这部分黑苹果高手常常会使用，回头录个视频吧。


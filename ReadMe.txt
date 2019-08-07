1.下载vcglib并解压 https://github.com/cnr-isti-vclab/vcglib/tree/devel
2.用vs2015打开 ..\src\external\external.pro 进行编译
3.查找rc.exe的路径 我的路径是在C:\Program Files (x86)\Windows Kits\10\bin\10.0.17763.0\x64
   右键我的电脑->属性->高级系统设置->环境变量
   在系统变量中的Path中添加rc.exe的路径
4.用vs2015打开 ..\src\meshlab_full.pro
5.右键项目filter_isoparametrization->属性->C/C++->命令行 在其他选项中添加/bigobj
6.对meshlab_full.pro进行编译
7.在..\src\distrib中点击.exe文件即可运行

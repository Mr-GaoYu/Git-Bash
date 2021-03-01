1、下载NSSM：
https://nssm.cc/release/nssm-2.24.zip
复制代码
2、下载安装包
https://dl.gogs.io/0.12.3/gogs_0.12.3_windows_amd64.zip
复制代码
3、安装git for windows

4、安装NSSM
设置系统变量："控制面板" --> "系统和安全"--> "系统"--> "高级系统设置"--> "环境变量"--> "系统变量"-->"编辑系统变量"在"变量值"项目添加NSSM文件路径"D:\conanl\Downloads\nssm-2.24\nssm-2.24\win64"。路径安置的实际配置。

6、安装gogs
6.1、编辑系统安装文件：
D:\conanl\Downloads\gogs_0.12.3_windows_amd64\gogs\scripts\windows\install-as-service.bat

修改如下项目：
SETgogspath=D:\conanl\Downloads\gogs_0.12.3_windows_amd64\gogs (按实际安装目录修改)

6.2、以管理权限运行安装脚本：



效果
浏览器输入：http://127.0.0.1:3000/



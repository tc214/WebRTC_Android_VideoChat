运行步骤：
1.启动服务器
在终端进入ProjectRTC-master/下，执行：
node app

#  启动成功后，在浏览器打开：127.0.0.1:3000
#  可以看到一个界面

2.启动Android客户端
将源码工程导入Android Studio;
修改AndroidRTC-android-studio\app\src\main\res\values\strings.xml：
将host改为服务器所在电脑的IP,重新编译安装到手机。
该App启动后即可进行点对点视频聊天。



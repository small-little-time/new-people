2595001965 <a href="https://github.com/2595001965" target="_blank">我的主页</a>

2019/11/21  Java环境配置
今天配置了Java虚拟机，但是我的书和视频上的配置路径并不完全相同。
共同点：都是在我的电脑>>属性>>环境变量里添加path和classpath
注意：在系统变量里添加任何一个用户都能使用，在指定用户里添加只能指定用户使用。
书上配置path路径是D:\java\jdk1.8.0_131\bin  classpath路径是D:\java\jdk1.8.0_131\lib
但视频里却要先配置一个JAVA_HOME的路径也就是Java安装路径下JDK的路径然后再配置path和classpath路径。而且视频里说path路径已有只要加“；”在后面添加我们的路径JAVA_HOME%\bin;classpath路径是JAVA_HOME%\lib\dt.jar。
最后用命令提示符输入Javac看是否有如下图片，有则正确。
![实例](https://www.2cto.com/uploadfile/Collfiles/20180413/201804131409341003.png ''来自百度'')

2595001965 <a href="https://github.com/2595001965" target="_blank">我的主页</a>

2019/11/21  Java环境配置
今天配置了Java虚拟机，但是我的书和视频上的配置路径并不完全相同。
共同点：都是在我的电脑>>属性>>环境变量里添加path和classpath
注意：在系统变量里添加任何一个用户都能使用，在指定用户里添加只能指定用户使用。
书上配置path路径是D:\java\jdk1.8.0_131\bin  classpath路径是D:\java\jdk1.8.0_131\lib
但视频里却要先配置一个JAVA_HOME的路径也就是Java安装路径下JDK的路径然后再配置path和classpath路径。而且视频里说path路径已有只要加“；”在后面添加我们的路径JAVA_HOME%\bin;classpath路径是JAVA_HOME%\lib\dt.jar。
最后用命令提示符输入Javac看是否有如下图片，有则正确。
![实例](https://image.baidu.com/search/detail?ct=503316480&z=0&ipn=d&word=javac&step_word=&hs=0&pn=2&spn=0&di=46970&pi=0&rn=1&tn=baiduimagedetail&is=0%2C0&istype=0&ie=utf-8&oe=utf-8&in=&cl=2&lm=-1&st=undefined&cs=3981493368%2C2499601157&os=210701626%2C52083849&simid=0%2C0&adpicid=0&lpn=0&ln=711&fr=&fmq=1574349035142_R&fm=&ic=undefined&s=undefined&hd=undefined&latest=undefined&copyright=undefined&se=&sme=&tab=0&width=undefined&height=undefined&face=undefined&ist=&jit=&cg=&bdtype=0&oriquery=&objurl=http%3A%2F%2Faliyunzixunbucket.oss-cn-beijing.aliyuncs.com%2Fpng%2F20180110234446269925.png&fromurl=ippr_z2C%24qAzdH3FAzdH3Fyq_z%26e3Bwsty7g_z%26e3Bv54AzdH3Fztstw5AzdH3Fmc89lmAzdH3F&gsm=&rpstart=0&rpnum=0&islist=&querylist=&force=undefined ''来自百度'')

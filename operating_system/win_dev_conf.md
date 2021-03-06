# WINDOWS下开发环境搭建

>该开发环境的搭建，主要针对于WINDOWS7 64位机器下的JAVA后端开发。<br>
>如果喜欢用IDEA作为JAVA的开发工具，建议安装jdk8。

### 1、JAVA安装与环境变量配置

>安装过程略过（建议安装在D盘）<br>
>JAVA的环境变量配置：

    ①在系统左下角点击“开始”按钮；
    ②找的“计算机”右键选择“属性”；
    ③在弹出的窗口中点击“高级设置”；
    ④在弹出的“系统属性”的“高级”下
    ⑤点击“环境变量”

>如图：

![设置windows环境变量](../static/imgs/win_env_var.png)

>添加环境变量

    JAVA_HOME   D:\Program Files\Java\jdk1.8.0_66
    CLASSPATH   .;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar;
    PATH        %JAVA_HOME%\bin;%JAVA_HOME%\jre\bin;

>按下Win(Ctrl和Alt之间的键)+R，然后输入CMD打开命令提示符窗口，<br>
>输入以下命令验证环境配置是否正确

    java -version

### 2、MAVEN安装与环境变量配置

>先下载[MAVEN](http://maven.apache.org/download.cgi)压缩包，解压到硬盘（建议放到D盘）。<br>
>修改MAVEN的配置文件<br>
>添加环境变量<br>

    MAVEN_HOME  D:\tools\apache-maven-3.3.9
    PATH        %MAVEN_HOME%\bin;

### 3、NODE.js安装与环境变量配置

>下现在安装包[node-v6.11.1-x64](https://nodejs.org/dist/v6.11.1/node-v6.11.1-x64.msi)（安装的时候，默认设置了环境变量，可以略过下一步）;<br>
>建议安装路径设置在非系统盘（如：D:\Program Files\nodejs），这样重装系统后，只想要配置环境变量即可

    PATH    D:\Program Files\nodejs\node.exe;C:\Users\Administrator\AppData\Roaming\npm;

>其他配置可参照[快速搭建 Node.js 开发环境以及加速 npm](https://cnodejs.org/topic/5338c5db7cbade005b023c98)

>安装gulp插件

    npm install -g gulp --registry=https://registry.npm.taobao.org


### 4、ORACLE11g安装，及PLSQL安装与配置

>

### 5、MYSQL安装配置

>下载压缩包的版本[mysql5.6]()，解压到硬盘（这里解压的D盘）；<br>
>

### 6、安装Sublime Text3（个人喜好，可略过）

>请参照文章：[如何优雅地使用Sublime Text3](http://jeffjade.com/2015/12/15/2015-04-17-toss-sublime-text/)

### 7、修改HOST文件（科学上网）

>请参照开源项目[hosts](https://github.com/racaljk/hosts)。<br>
>如果有些网站还是不能访问，可找一些代理工具翻墙，这里推荐使用[蓝灯](https://github.com/getlantern/lantern)。<br>
>翻墙后可下载谷歌浏览器，方便做前端调试。

### 8、安装版本控制工具

>git客户端工具推荐使用[git](https://git-scm.com/download/win)或者[SourceTree](https://www.sourcetreeapp.com/)<br>


### 9、IDEA的安装与配置

>请下载[IDEA](https://www.jetbrains.com/idea/download/download-thanks.html)，再进行安装。
>破解


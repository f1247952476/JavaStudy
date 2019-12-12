# JavaStudy
金讯
Java Lesson
2019-12-05

1.	想让⼤家平时练习时就把 git 和 maven ⽤上，今晚讲⼀下它们的简单⽤法在 github 上创建项⽬
创建 maven 项⽬，常⻅的配置，如何在 pom.xml 加⼊依赖项⽬ maven 编译 git 提交代码到 github 你创建的项⽬上
2.	：条件、循环、循环嵌套等
3.	使⽤ LeetCode 上的⼀些和当前所学内容相关的算法题来作为课堂练习 git + maven 的安装和使⽤
maven 安装下载 maven 最新版本，https://maven.apache.org/download.cgi 解压下载的安装包（例如：apache-maven-3.6.3-bin.zip）到某个⽬录 windows 环境下将⽬录 maven解压⽬录\bin 添加到环境变量 Path 上 mac 环境，在 ~/.bash_profile ⽂件中加⼊⼀⾏，然后执⾏⼀下 source ~/.bash_profile 使之⽣效   export PATH=/maven解压⽬录/bin:$PATH 
命令⾏下执⾏ mvn --version，如果能正确显示版本号，说明安装正确，⽐如显示内容如下：
  ➜  java-les mvn --version 
  Apache Maven 3.6.1 (d66c9c0b3152b2e69ee9bac180bb8fcc8e6af555; 
2019-04-05T03:00:29+08:00) 
  Maven home: /Users/sh/bin/mvn 
  Java version: 1.8.0_212, vendor: Oracle Corporation, runtime: /Library/Java/JavaVirtualMachines/jdk1.8.0_212.jdk/Contents/Home/j re 
  Default locale: zh_CN, platform encoding: UTF-8 
  OS name: "mac os x", version: "10.15", arch: "x86_64", family: "mac"
注册 github 账号
新建⼀个项⽬
登录成功后，点击右上⻆【+】，在下拉菜单中选择【New repository】填写项⽬名（Repository name）和描述（Description）选择公共库（Public）、不使⽤ README.md 初始化点击【Create repository】进⾏创建
将⾃⼰项⽬上传 github
下载 git，https://www.git-scm.com/download/
安装后，进⼊命令⾏执⾏ git --version，如果能正常显示版本号说明安装正确，⽐如显示内容如下：
 
git add . 是添加所以的变更，如果单独添加某个⽂件可以使⽤ git add 单个⽂件路径名称   到 github 项⽬⻚⾯上刷新⼀下，看⼀下效果程序控制执⾏流程

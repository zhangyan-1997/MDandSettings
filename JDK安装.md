JDK安装

1.下载，[官方链接]([Java SE Development Kit 8 — 下载 | Oracle 中国](https://www.oracle.com/cn/java/technologies/javase/javase-jdk8-downloads.html))  [本地存储](D:\开发工具安装包\JDK)

2.安装： 双击安装包安装，选择`开发工具`，安装到`C:\dev\Java\jdk1.8.0_201`。

3.jre安装到: `C:\dev\Java\jre1.8.0_201`

4.配置环境变量

```shell
JAVA_HOME C:\dev\Java\jdk1.8.0_201
Path %JAVA_HOME%\bin
```

5.检查安装成功

```shell
java -version
javac
```


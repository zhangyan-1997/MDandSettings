1.解压maven安装包，放在dev目录下

2.配置环境变量

```
mvn -v
```

3.配置IDEA

- 打开settings->build->maven
- 修改maven home
- 修改settings文件
- 修改本地仓库地址

4.在dev settings.xml文件中添加阿里云镜像地址

```
<mirror>
        <id>alimaven</id>
        <name>aliyun maven</name>
        <!-- https://maven.aliyun.com/repository/public/ -->
        <url>http://maven.aliyun.com/nexus/content/groups/public/</url>
        <mirrorOf>central</mirrorOf>
    </mirror>
```


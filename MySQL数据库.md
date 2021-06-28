# Mysql数据库安装及其使用

## 安装数据库

1.下载`msi`安装包

2.打开安装程序，选择`Custom`， 选择`MySQL Servers -> x64 ->只选择MySQL Server 及 Client Programs`，`Execute` ，设置密码，`Execute`， `Finish`。

注意： 数据库密码为：`zhangyan`

3.配置环境变量

将`C:\Program Files\MySQL\MySQL Server 5.7\bin`添加到环境变量

在命令行输入`mysql -uroot -pzhangyan`

4.命令行启动mysql与关闭

```
net start mysql57 //启动mysql服务（如果安装时选择开机启动，则无需手动操作）
net stop mysql  //关闭mysql服务
mysqld -remove  //卸载mysql服务
```

## 安装navicat

1.安装navicat，全选下一步

2.断网，注册

3.以管理员身份运行注册机exe程序

4.生成序列号，复制到激活窗口

5.将激活码复制，复制进注册机进行生成，将生成的注册码拷贝回去，激活成功！

## Navicat连接MySQL

省略.......
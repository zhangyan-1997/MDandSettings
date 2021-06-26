Typora 添加右键

1.打开注册表

```
Win+R  regedit
```

![image](.\asset\01.png)

2.定位 `HKEY_CLASSES_ROOT\Directory\Background\shell`

![image](.\asset\02.png)

3.在shell下面新建项 `Typora` ,更改默认数据为Typora，再新建一个新建字符串值，命名为icon,其数据改为Typroa的安装路径。

![image](.\asset\03.png)

4.右键Typora新建项command，双击右边窗口的默认文件，填写文件路径,路径中的双引号不能少，表示字符串。

![image](.\asset\04.png)

## 右键添加当前目录下新建typora

执行`typora.reg`文件

内容如下:

```shell
Windows Registry Editor Version 5.00
[HKEY_CLASSES_ROOT\.md]
@="Typora.md"
"Content Type"="text/markdown"
"PerceivedType"="text"
[HKEY_CLASSES_ROOT\.md\ShellNew]
"NullFile"=""
```


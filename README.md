# Customize-the-installer
Fully customizable installer(可以完全自定义的安装程序)

## 自定义教程
> [!NOTE]
> 首先，开门见山，说一下如何自定义

下载后解压压缩包,会得到几个文件,其中install.exe是主程序,install文件夹存放要安装的文件,下面是对应表,(区分大小写)带*的是文件夹,带-的可省略

```
install          要安装的文件 *
install.exe      主程序
logo.ico         安装程序左上角的logo图标 -
Title.txt        安装程序的标题 -
Test.txt         安装程序下方的文本框内容 -
start.txt        如果用户勾选了安装后运行，那么就将在install文件夹里启动此文件里的程序名所指的程序
installlogo.png  安装程序中间的大logo
```

> [!IMPORTANT]
> 尽量不要在install中放置文件夹(如果它是重要程序的话)

> [!WARNING]
> 禁止倒卖！

## 二次封装及打包注意事项
```
确保主程序可以获得管理员权限
请制作64位程序
确保程序拥有当前文件夹的读、写、执行权
```

> [!CAUTION]
> 如果此程序为二次打包或未按标准配置造成的数据损失由用户自己承担

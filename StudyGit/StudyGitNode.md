#Git学习笔记01——准备环境_初步配置_HelloGit——[凌霄IT部落@2016-03-10起记录]

##1.什么是Git？
	一句话：Git是一个分布式的版本控制工具。

##2.Git安装——Win环境下载
###下载地址：
在Windows上安装git，一般为msysgit，国内可访问地址为：

	http://git-scm.com/download/win

国外官方下载地址为：

	http://code.google.com/p/msysgit/downloads/list

##3.怎么安装？
###exe安装版
	双击运行，网上说一路NEXT，自己百度照着安装。个人喜欢绿色版。。。
###7z.exe绿色版
	双击xxxxxx.7z.exe，选择要解压的路径即可。
	然后打开目录下的git-cmd.exe(win的命令行)、git-bash.exe(自带的命令行)


##4.安装完的配置

##说明
	**当安装完 Git 应该做的第一件事就是设置你的用户名称与邮件地址**。 
	这样做很重要，因为每一个Git 的提交都会使用这些信息，并且它会写入到你的每一次提交中，不可更改。

###设置用户名
	
1. 打开：git-bash.exe
2. 输入命令：`git config --global user.name "userName"`

###设置邮箱
	
1. 打开：git-bash.exe
2. git config --global user.email userxxxx@qq.com

###提示
	如果使用了 --global 选项，那么该命令只需要运行一次
	因为之后无论你在该系统上做任何事情， Git 都会使用那些信息。

###查看配置是否成功？
	

1. 查看配置信息：git config --list
2. 查看是否有user.name=xxx、user.email=xxx@qq.com

###查看单个配置
	输入 git config <key>： 来检查 Git 的某一项配置
	例如：git config user.name

##5.怎么获取帮助？
	有三种方法可以找到 Git 命令的使用手册
	1. git help <verb>
	2. $ git <verb> --help
	3. $ man git-<verb>

###例如
	要想获得 config 命令的手册，执行：$ git help config




![凌霄IT部落微信公众号：lingxiaoIT](http://i.imgur.com/juNDLS1.png)

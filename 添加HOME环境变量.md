# 添加 HOME 环境变量

本文只讲述如何添加环境变量，并不会深究环境变量的原理

在下面的演示过程中，请自觉将`username`替换为您系统上的用户名

Linux 和 macOS 通常并不需要添加 HOME 环境变量

## Windows 系统添加 HOME 环境变量

Windows 系统的主目录默认并不在用户文件夹`C:\Users\username`，而是在 AppData 文件夹中，但是 AppData 是隐藏文件夹，如果我们需要配置 Emacs 的话还要进入一个隐藏文件夹就会很费劲，我们可以通过添加 HOME 环境变量将主目录修改为用户文件夹。

在 Windows 系统的开始菜单中搜索环境变量，可以打开环境变量的编辑见面。点击“新建”来新建一个环境变量，环境变量名为`HOME`，值为`C:\Users\username`，**请将`username`替换为您系统上的用户名！**然后确定即可。


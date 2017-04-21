# 开始

连接移动硬盘，打开“实用工具”（shift+command+U），打开“终端”进行命令输入：

	使用'diskutil list'命令查看到磁盘的'Name'（复制粘贴命令然后回车）

 
 `diskutil list` 找到移动硬盘的名字记下


用下面这条命令更新 `/etc/fstab` 文件（复制粘贴命令然后回车）

`sudo nano /etc/fstab`（复制粘贴命令然后回车）

会要求输入电脑的密码（没有密码会跳过去），出现以下内容

 GNU nano 2.0.6              File: /etc/fstab
 
 
                                                   [ Read 1 line ]
 ^G Get Help  ^O WriteOut  ^R Read File ^Y Prev Page ^K Cut Text  ^C Cur Pos
 
 ^X Exit       ^J Justify    ^W Where Is   ^V Next Page  ^U UnCut Text^T To Spell   

复制以下内容粘贴后 不回车 ，按 `Ctrl + X` 


 
 `LABEL=BOOTCAMP none ntfs rw,auto,nobrowse` 

endლ(╹◡╹ლ)



# HelloGitHub
this is my first project . let me try

    第一次使用git备注
       本地文件上传到git仓库
		git通过ssh进行传输来保证安全性，首先在本地创建ssh key,命令：ssh-keygen -t rsa -C "email address"
		之后会要求确认路径和输入密码,一路回车键使用默认的也行。如果成功会生成.ssh文件夹。里面有两个文件
		id_rsa.pub和id_rsa.然后打开id_rsa.pub复制里面的内容到github的设置选项下的ssh栏的addsshkey下。
	
	然后设置用户名和邮箱，命令如下：
		git config --global user.name "your name" 
		git config --global user.email "email address"
	
	直接add  commit 然后push到github上的仓库地址
	
	切换分支
		1，先在本地fetch获取所有分支的更新
		2，执行git branch -a查看本地和远程的分支（不带-a则是本地分支）
		3，执行 git checkout 分支名 即可切换

	
	新建分支
	    git branch 分支名
	删除远程分支
	    git push origin --delete 分支名
	删除本地分支
	    git branch -d new_branch
	
	  
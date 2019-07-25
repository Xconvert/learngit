[从远程库克隆]

1. ssh
	git clone git@github.com:Xconvert/learngit.git

[分支创建与合并]

1. 创建 jiangjun 分支：git checkout -b jiangjun

	git checkout命令加上-b参数表示创建并切换，相当于以下两条命令：

	$ git branch jiangjun
	$ git checkout jiangjun

2. 切换回 master 分支
	
	git checkout master

3. 小结
	
	查看分支：git branch

	创建分支：git branch <name>

	切换分支：git checkout <name>

	创建+切换分支：git checkout -b <name>

	合并某分支到当前分支：git merge <name>

	删除分支：git branch -d <name>

4. 分支操作

	a. 重命名远程分支对应的本地分支

	git branch -m old-local-branch-name new-local-branch-name

	b. 删除远程分支

	git push --delete origin old-branch

	c. 上传新命名的本地分支

	git push origin  new-local-branch-name: new-local-branch-name

	d. 绑定远程分支

	git branch --set-upstream
	
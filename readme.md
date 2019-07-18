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
	
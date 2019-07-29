# git Order

- git init
> 初始化一个工作环境，可以存储修改记录

- git add
> 将一个文件放在一个待提交区

- git commit -m
> 将待提交区的文件放到工作历史路径中

- git status
> 获得文件处理的状态，查询修改是否被提交

- git diff file
> 获得文件修改有什么区别

- git log --pretty=oneline 
> 查询修改的历史

- git reset --hard tag 
> 返回一个修改历史

- git relog --pretty=oneline
> 获得命令后修改的历史

- git rm file
> 本地删除文件

- git remote add origin git@githubname:path/.git

> 链接远程的文件库  

- git push -u origin master
> 第一次将本地的仓库推到远程仓库上

- git push origin master
> 将本地的仓库推到远程仓库上

- git clone git@github.com:githubname/~.git
> 克隆远程仓库到本地

- git checkout -b name
> 创建切换分支

- git branch
>  获取当前分支的情况

-  git merge
> 将分区某某某合并到当前分区
 
-  git branch -b dev
> 创建新的分区

- git checkout name
> 切换新的分区

- git branch -d
> 删除分区

- git chekout -d name
 
- git log --graph
> 获得分支的历史记录图表

- git merge --no-ff -m " " name
> 关掉fast-merge 可以保留历史的分支

- git stash
> 保存当前的工作状态

- git stash list
> 获得当前保存状态的链表

- git stash apply
> 恢复原先的状态

- git stash drop
> 删除保留的状态

- git stash pop

- git stash apply stash@{}

- git branch -d/-D

- git rebase
> 将历史记录做成一条链

- git tag name
> 打上标签明

- git tag 
> 获取所有的标签

- git tag -d 
> 删除标签

- git push origin name


- git push origin --tags

**本地删除标签名，推送到服务器上**

- git tag -d 

- git push origin:refs/tags/name

**如果本地的服务器上的文件不一致**

1. git fetch origin master
2. git merge origin master
3. git pull origin master --allow-unrelated-histories
      
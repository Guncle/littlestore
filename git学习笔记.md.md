Git是一款免费、开源的分布式版本控制系统，用于敏捷高效地处理任何或小或大的项目，是目前世界上最先进的分布式版本控制系统。

1.下载网址<https://git-scm.com/>  （git官网）

2.初始化一个Git仓库，使用`git init`命令。

添加文件到Git仓库，分两步：

1. 使用命令`git add <file>`，注意，可反复多次使用，添加多个文件；

2. 使用命令`git commit -m <message>`，完成。

   Git基本常用命令如下：

　　mkdir： XX (创建一个空目录 XX指目录名)

　　pwd： 显示当前目录的路径。

　　git init 把当前的目录变成可以管理的git仓库，生成隐藏.git文件。

　　git add XX 把xx文件添加到暂存区去。

　　git commit –m “XX” 提交文件 –m 后面的是注释。

　　git status 查看仓库状态

　　git diff XX 查看XX文件修改了那些内容

　　git log 查看历史记录

　　git reset –hard HEAD^ 或者 git reset –hard HEAD~ 回退到上一个版本

　　(如果想回退到100个版本，使用git reset –hard HEAD~100 )

　　cat XX 查看XX文件内容

　　git reflog 查看历史记录的版本号id

　　git checkout – XX 把XX文件在工作区的修改全部撤销。

　　git rm XX 删除XX文件

　　git remote add origin https://github.com/tugenhua0707/testgit 关联一个远程库

　　git push –u(第一次要用-u 以后不需要) origin master 把当前master分支推送到远程库

　　git clone https://github.com/tugenhua0707/testgit 从远程库中克隆

　　git checkout –b dev 创建dev分支 并切换到dev分支上

　　git branch 查看当前所有的分支

　　git checkout master 切换回master分支

　　git merge dev 在当前的分支上合并dev分支

　　git branch –d dev 删除dev分支

　　git branch name 创建分支

　　git stash 把当前的工作隐藏起来 等以后恢复现场后继续工作

　　git stash list 查看所有被隐藏的文件列表

　　git stash apply 恢复被隐藏的文件，但是内容不删除

　　git stash drop 删除文件

　　git stash pop 恢复文件的同时 也删除文件

　　git remote 查看远程库的信息

　　git remote –v 查看远程库的详细信息

　　git push origin master Git会把master分支推送到远程库对应的远程分支上

目前只学习了git的简单使用，如创建仓库，把文件放到仓库中，与部分基本常用命令。

| 遇到问题                      | 解决方法                                     |
| :------------------------ | :--------------------------------------- |
| 1.注册账号时无法验证邮箱验证码          | 百度，查找资料——QQ邮箱无法收到github发送的邮件，需在QQ邮箱设置的白名单中添加GitHub的域名 |
| 2.软件下载后在bash中输入名字与邮箱时出现状况 | 仔细对照——单词拼写错误                             |
| 3.使用时遇到不懂的单词              | 用有道词典查找                                  |
| 4.不明白把文件放到本地仓库的操作         | 请教同学                                     |

体会：感觉自己多get到了一项技能，虽然学习一个新领域的知识的过程遇到的问题很多，但最终通过自己的努力将问题解决，这种感觉是豁然开朗的。学到一项新技能，学到一些新的知识，更增强了自信心。
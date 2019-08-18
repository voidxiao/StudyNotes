# Git命令

## git init
- 在当前文件夹下初始化git本地仓库

## git status
- 查看当前本地仓库状态

## git log
- 查看本地仓库版本

## git log --oneline
- 以一行的输出来查看本地仓库版本

## git add \<文件名\>
- 将有改变的文件添加到暂存区,等待提交

## git add .
- 将所有改变的文件添加到暂存区,等待提交

## git commit -m
- 提交到本地版本控制,-m后加"说明"

## git commit -a -m
- -a直接把文件提交到本地版本控制,不需要添加到暂存区

## git remote
- 将本地版本控制上传至远程版本控制

## git remote add \<url\> master
- 本地版本控制关联远程版本控制,master指主分支

## git remote add origin \<url\> master
- 相当于给url起别名,master指主分支

## git remote --v
- 列出关联的远程仓库

## git pull
- 把远程仓库拉到本地仓库,前提是本地有仓库

## git clone
- 将远程仓库克隆到本地,当本地没有仓库

## git push
- 将本地仓库推送到远程仓库

# 学习Git的基本使用方法
## [初始化本地仓库]
git init
## [本地仓库中添加文件]
语法:git add <file>

例子:git add README.md

## [本地仓库提交文件更改]
语法:git commit -m <message>

例子:git commit -m "添加了README文件"

## [查看Git当前状态]
git status

## [查看文件更改内容]
语法:git diff <file>

例子:git diff README.md

## [添加远程仓库]
语法:git remote add <remote_name> <remote_address>

例子:git remote add master git@github.com:mago960806/LearnGit.git

## [提交更改到远程仓库]
语法:git push <local_name> <remote_name>

例子:git push -f -u master master

备注:-f参数表示强制覆盖远程仓库的文件,-u参数表示关联本地和远程分支

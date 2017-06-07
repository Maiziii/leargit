git tracks changes
要关联一个远程库使用命令 git remote add origin git@server-name:path/repo-name.git；
关联后使用命令git push -u origin master第一次推送master分支的所有内容；
此后每次本地提交后只要有必要就可以使用命令git push origin master推送最新修改

试试git remote remove origin命令移除远程库

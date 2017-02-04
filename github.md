## git
### 基本使用
- git init
+ 创建版本管理仓库
+ 如果你想要你的项目使用 git 版本管理起来，则进入该项目根目录
+ 使用 git init 明林初始化一个 git 仓库
- git status
+ 查看仓库状态
- git add
+ 添加改动到暂存区
+ git add file1 file2 ...
+ git add dir1 dir2 ...
+ git add .
+ git add --all
- git commit
+ 将暂存区提交到本地仓库
- git log
+ 查看提交日志
- gitk
+ 以图形化界面查看提交日志

##github
###在线创建方法
1. 在线创建 Rabbit
2. git clone Rabbit的地址
3. git status 看内容
4. git add +文件名
5. git commit -u "更改日志"
6. git push
###线下文件上传
1. 本地写好文件
2. 在线创建一个 Rabbit
3. git init //把这个目录变成Git可以管理的仓库
4. git add README.md //文件添加到仓库
5. git add . //不但可以跟单一文件，还可以跟通配符，更可以跟目录。一个点就把当前目录下所有未追踪的文件全部add了 
6. git commit -m "first commit" //把文件提交到仓库
7. git remote add origin git@github.com:wangjiax9/practice.git //关联远程仓库
8. git push -u origin master //把本地库的所有内容推送到远程库上
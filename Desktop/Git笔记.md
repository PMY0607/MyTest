### git相关概念

工作区：就是你电脑上敲代码的原文件

缓冲区：临时保存提交的改动

本地仓库：敲好代码后，放到本地仓库后，准备放到远程仓库

远程仓库：网络给你托管的仓库

 ![image-20220225164015106](/Users/pengmingyuan/Library/Application Support/typora-user-images/image-20220225164015106.png)



### git常用命令

git remote add origin <远程仓库地址>：本地仓库和远程仓库关联

git remote set-url origin  <远程仓库地址>：修改远程仓库地址

git branch：查看所有分支

git checkout：切换分支

git branch 《分支名》：新建分支

git push origin master：推送最新更改

git pull origin 《分支名》：拉去最新的文件

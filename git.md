#配置git
 git config --global user.name "Yourname"
 git config --global user.email "Youremail"
#初始化git仓库
 git init
#添加本地文件到本地仓库 
 git add filename1,filename2
#提交文件到本地仓库
 git commit -m <message>
#查看当前工作区状态
 git status
#查看文件改动
 git diff filename
#删除本地git仓库文件
 git rm filename
#从本地仓库中恢复文件到本地
 git checkout -- file

####远程仓库####

#创建SSH Key
ssh-keygen -t rsa -C "youremail@example.com"

#添加远程仓库
git remote add origin git@github.com:username/xxxx.git

#首次提交到远程仓库
git push -u origin master

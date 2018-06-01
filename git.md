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
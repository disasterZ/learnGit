#创建版本库
##创建Git仓库
git init

##文件添加到仓库
git add

##文件提交到仓库(括号中的内容为可加可不加，下同)
git commit (-m "注释")

#管理版本
##查看仓库当前状态
git status

##查看修改
git diff

##查看log
git log (--pretty=oneline)

##版本回退
git reset --hard Head^/Head~1/版本号前几位

##查看所有命令
git relog
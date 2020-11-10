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

##撤销修改
git checkout -- <file>

##撤销暂存区修改
git reset HEAD <file>

##删除文件
git rm <file>

##误删恢复(从来没有被添加到版本库就被删除的文件，是无法恢复的！)
git checkout -- <file>

#远程仓库
##关联远程库
git remote add origin <link>

##推送
git push (-u) origin <branch>

##克隆本地库
git clone <link>

##创建分支(未加分支名则为显示当前分支)
git branch (-d/-D)(删除分支/强制删除) <name>

##切换分支
git checkout <name>
git switch <name>

##创建分支并切换
git checkout -b <name>
git switch -c <name>

##合并分支
git merge

##查看分支合并图
git log --graph

##查看远程库信息
git remote -v

##抓取分支
git pull

##变基
git rebase

#标签管理
##创建标签(-a指定标签名，-m指定说明文字,-d删除标签)
git tag <name> (<commit id>)

##查看标签信息
git show <tagname>

转载自git教学网站：https://www.liaoxuefeng.com/wiki/896043488029600







- 分布式版本控制

git init
git add .
git commit -m 'first commit'

git reset --hard HEAD^  #  回退到上一个版本，删除工作区的修改
git reset --hard 1094a  #  回退到指定版本
git reflog # 查看历史命令，以便确定要回到曾经哪个版本


第四天工作   今天很开心


git diff HEAD -- xxxx.txt  # 查看工作区和版本库里面最新版本的区别
git checkout -- readme.md  # 丢弃工作区的修改
git reset HEAD readme.md   # 撤销暂存区的修改
git reset --soft HEAD^     # 撤销commit，不删除工作区的修改

git checkout -b dev  #创建分支
git branch  # 查看分支
git checkout master  # 切换分支
git branch -d <branch>  # 删除分支

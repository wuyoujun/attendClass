git clone -b dev git@192.168.3.17:root/fxjc_web_multiple.git  从远程仓库192.168.3.17的dev分支克隆（不然默认从master分支克隆）

git branch newbranchname	创建新的本地分支

git branch 查看当前分支

git branch -r 查看远程分支

git branch -a 查看所有分支

git checkout -b liuyj --track origin/liuyj  创建本地liuyj分支并将当前分支切换到本地liuyj，并将其关联远程liuyj分支

git branch -b newbranch //创建并切换到newbranch分支下

git merge --abort  消除分支合并的影响

git checkout dev 切换到dev分支

git branch -D liuyj 强制删除liuyj分支   

git pull

git checkout -b liuyj --track origin/liuyj

git branch -a 查看所有分支

git branch -vv 查看当前分支关联的远程分支

git pull origin dev 拉远程dev

git branch (-m | -M) <oldbranch> <newbranch> 重命名本地分支

git push origin HEAD:wufengying 推送到远程wufengying分支

git push origin --d <BranchName> 删除远程分支 

git remote show origin 查看远程库的一些信息，及与本地分支的信息

git reset --hard HEAD^  版本回退
git remote prune origin 删除本地库中这些相比较远程库中已经不存在的分支(删除在本地有但在远程库中已经不存在的分支)

git clone http://192.168.3.150:10080/root/fxjc_web_multiple.git  从指定地址克隆


git remote -v	//查看git远程仓库地址

git remote set-url origin URL		//切换远程仓库

git init 	//初始化一个git仓库

git remote add origin URL 	//绑定远程git仓库







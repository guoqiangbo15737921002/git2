这是一个git内容
这是第二行

找到要托管git的文件
git init
新建一个文件
git status 提示添加了一个文件
git add filename 添加文件
git commit -m "修改的备注"
可同时添加多个文件到git文件
git add file1,file2
同时提交时候写上备注

2.将本地仓库与远程仓库的相连 

github 新建一个仓库 将网页里面的 git remote add origin http://github/***/gittest.git
git push -u origin master 将仓库推送进去  
输入自己的用户名和密码
推送成功后刷新github网站


3.当本地仓库发生变化时，需要重新提交一次到远程仓库
git push origin master
刷新网页，可以看到与本地一致

4.copy管理员创建的远程仓库，copy地址到终端

5.git的其他命令
git diff 查看最新的修改与仓库的文件不同的地方
git status 检测状态

git log 查看以往提交的版本
git log --pretty oneline将以往的版本显示一行
git reset --hard HEAD^
回滚到上一级

git reset --hard commitID 可退回到指定的版本

git rm ***删除文件
git commit -m"删除文件"







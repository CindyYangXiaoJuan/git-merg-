## git 合并远程2个分支
### 克隆项目
	+ git clone 
### 查看所有分支(本地分支和远程分支)
	+ git branch -a
### 切换要合并的分支
	+ git checkout test
### 在test分支上合并目标分支
	+ git merge dev
### 这里要注意,没有报错,直接提交
	+ git push origin test
### 例如是基本冲突,解决冲突
	+ 在看到提示的冲突文件内,将git冲突注释或者删除
	+ git add 出现冲突的文件
	+ git commit -m '冲突文件'
### 解决报错之后,进行提交
	+ git push origin test 

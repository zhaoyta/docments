# docments
google facebook uber linkedin yelp twitter netflix Square  amazon Walmart  spring-projects


new
git init
git add .
git commit -m "message" --本地仓库
git remote add mark git@github.com:zhaoyta/xxx.git
git push mark master --远程仓库

old
 git pull mark master

ignore
.git/info/exclude 
    .abc  a*  a/ 

删除已入仓库的文件夹
git rm -r --cached .idea/
git commit -m 'x'

restore 
git reset --hard HEAD

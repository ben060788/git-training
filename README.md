# git-Memo
git cmd memo

# git config
- git config --global user.name "xxxx"
- git config --global user.email "xxxx@gmail.com"

# usually command

- git log
    > 查看近期的commit
- git clone https://github.com/xxxx/xxx.git
    > 從repo 複製一份到local
- git pull repoUrl branchName
    > 抓最新的一份版本
- git remote add urlname https://github.com/xxxx/xxxx.git ​
    > 加入常用repo

# git checkout
- git checkout branchName
    > 切換branch
- git checkout versionCode
    > 切換到某版本

# git stash
- git stash
    > 將目前修改的部分暫存起來
- git stash list
    > 查看目前暫存的stack
- git stash apply stash@{0}
    > 使用某個暫存
- git stash --index
    > 使用最新的暫存
- git stash pop
    > 使用最近的暫存並清除暫存
- git stash drop 
    > 刪除暫存
# Initial Project
1. git init
2. git add fileName
3. git commit -m "description"
4. git push -u urlName branchName

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
- git pull urlName branchName
    > 抓最新的一份版本
- git remote add urlname https://github.com/xxxx/xxxx.git ​
    > 加入常用repo

# git checkout
- git checkout branchName
- git checkout versionCode

# git stash
- git stash
- git stash list
- git stash apply stash@{0}
- git stash --index
- git stash pop
- git stash drop

# Initial Project
1. git init
2. git add fileName
3. git commit -m "description"
4. git push -u urlName branchName

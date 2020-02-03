# 在自己电脑里找到自己所要上传的文件夹，右键Git Bash here

```
git init
```

# 其文件夹下会建立一个.git文件夹

```
git remote add origin git@github.com:M201575478/demo.git
```

# 如果提示exist 
```
#git remote rm origin
```

# 推荐先把两边同步下
```
git pull --rebase origin master
git pull origin master
```

```
git add .
git commit -m 'first_commit'  
git push origin master
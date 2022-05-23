


## git

```
git config --global user.name "用户名"

git config --global user.email "邮箱"

git config --list

ECS Caps ZZ Enter

ssh-keygen -t rsa -C “邮箱”

C:\Users\xxx\.ssh  id_rsa 私钥  id_rsa.pub 公钥

```

### 新建远程分支

```
git branch
git status
```

```
git checkout -b xxx

git push origin xxx:xxx
```
### 删除远程分支

```
git push origin --delete xxx

git push origin :xxx
```
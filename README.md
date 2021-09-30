# GitHubGuide

存储GitHub协作常用的指令。

## 项目文件上传

在本地文件夹下准备好文件之后，

```shell

git init
git add .
git commit -m "comment"
git branch -M master   # main是支名
git remote add origin https://github.com/zhongshsh/GitHubGuide.git   # 增加远程节点
git push -u origin master    # 将文件上传

```


## 查看

```shell

git remote -v   # 查看连接到哪个远程库

```

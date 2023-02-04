# GITT
git shell tutorial

<!-- [image](image/1.png) -->
```bash
git clone  https://github.com/Tokoshie/GITT.git

git status

# [修改编辑文档]

git add .
#添加到staging[暂存区]

# [编辑操作]

git commit -m "your change submission"
#打包提交注释和内容到 local repo

git push origin main
# clone来自自己的create/fork的库时，直接push到[源]origin的main分支
# 会出现login 而passwork推荐使用 https://github.com/settings/tokens 申请的token

#[PR/ pull request]
# pull request [PR]拉去请求，fork后修改bug/新功能添加 推荐new branch以便和main分离功能

git remote -v 
# 查看远程库信息[your own repo and someone else's repo]

git remote add source https://github.com/Tokoshie/GITT.git
#指定fork的库来源为远程库

git pull origin main
#同下列操作：同步origin的更新内容到本地main分支

git fetch source
#拉取最新的源库代码
git checkerout main
#切换到本地[你需要push的远程分支]
git merge source/main
# 合并source源的main分支到本地

# [进行编辑代码操作]

git add . / git commit -m "something" 
git push origin main
# push到你fork的main分支


```

<p align=center>
<img src='image/1.png'width=50%>
</p>

<p align=center>
<img src='image/2.png'width=50%>
</p>

<p align=center>
<img src='image/3.png'width=50%>
</p>

<p align=center>
<img src='image/4.png'width=50%>
</p>
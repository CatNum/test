# test

这是一个测试git指令的项目

```
$ git checkout -b dev    添加分支并切换
$ git switch -c dev      添加分支并切换【新】
$ git branch dev         添加分支
$ git checkout dev       切换分支
$ git switch master      切换分支【新】
$ git merge dev          合并分支
$ git branch -d dev      删除分支
$ git branch -vv         查看分支关联情况

$ git branch --set-upstream-to=origin/branch branch
（前面branch为远程分支名，后面branch为本地分支名）设置本地与远程分支关联
$ git push origin remote 设置远程分支（若远程分支已存在则意思是把远程关联本地的分支推送，而不是当前所在分支）

$ git push --set-upstream <remote-name> <local-branch-name>:<remote-branch-name>
创建远程分支并且关联到远程分支：
        <remote-name>：远程git服务器名称，一般设为origin
        <local-branch-name>：本地分支名称
        <remote-branch-name>：远程分支名称
如果关联当前本地分支则可以省略为 git push --set-upstream origin remote

$ git push origin test:master   提交本地test分支到远程的master分支：
$ git push origin :xxx    (推送一个空分支到远程分支，其实就相当于删除远程分支)   
或    git push origin --delete xxx
$ 
$ 
$ 
$ 
$ 
$ 
$ 



```

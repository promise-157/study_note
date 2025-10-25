1.绑定仓库

ssh-keygen -t rsa.会告诉你生成在哪里.用记事本打开id\_rsa.pub.复制里面内容github设置中新建ssh秘钥粘贴进去..

ssh -T git@github.com.选yes即可.

2.新建个仓库,: git branch -M main

换一下本地分支的名字(大概)

3.新建第一过文件: echo "# study\_note" >> README.md,双引号内容为新建文件里的内容

4\. git add README.md添加文件,类似于缓存一下防止不小心删除.

5\. git commit -m "first commit"提交记录

6\. git remote add origin https://github.com/promise-157/study\_note.git

和仓库关联起来,不会下载内容.git clone的话会关联的同时下载

7.origin是那个网址的别名,gitcommit是本地保存,push保存云端,push的内容是commit的内容

8.第一次push要登陆这正常

9.git commit -am “”可以不用老是add



10.-u代表include,-m代表message,-d删除

11\. git pull origin master拉



其他:

Log status branch tag merge

Git checkout 分支






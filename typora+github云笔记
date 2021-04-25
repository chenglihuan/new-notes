## Typora+github /打造云笔记

 

### 1、先下载Typora安装

下载地址：https://www.typora.io/

 

###  2、下载git并安装

下载地址：https://www.git-scm.com/download/



### 3、注册一个github账号

github官网地址：https://github.com/



### 4、添加SSHkey

使用GitHub之前需要添加SSHkey，用来验证GitHub远程仓库



具体步骤：

（1）打开cmd查看秘钥

- ssh-keygen -o

- type C:\Users\Administrator\.ssh\id_rsa.pub （查看秘钥）

（2）全选复制到github中创建sshkey

- 在github个人账户中找到setting , SSH

- 复制到github 中生成新的 sshkey中，起个名字，创建成功



### 5、创建仓库将仓库在本地克隆

- 进入自己的仓库，新建一个，将仓库的镜像key复制，在本地进行克隆。（进行双方的链接）

 （假如要讲刚刚创建的仓库克隆在E盘中）

- cd E:\        

- git clone https://github.com/chenglihuan/new-notes.git

  

###  6、然后进入文件夹中可以进行编辑

- cd new-notes

​    新建文件编辑后保存



###   7、将本地文件上传到Github上

- 创建一个新的仓库 
  git init      (进入到你本地项目的根目录下)   (若已经根据上面步骤创建仓库，这步应该可以不用做)

-  git add .       (将项目的所有文件添加到仓库中)

- git commit -m "add all"         （将索引内容添加到仓库中）

 

——————————————————————————

注意：若上面这个命令执行不成功，提示：

 

Author identity unknown

*** Please tell me who you are.

Run

 git config --global user.email "you@example.com"

 git config --global user.name "Your Name"

to set your account's default identity.

Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Administrator@ÍõÐñСÃ×PC.(none)')

 

则使用下面三个指令：

git config --global user.email "you@example.com"

git config --global user.name "Your Name"

git config --local -l

 ————————————————————————————

- git push            （上传代码到github远程仓库）


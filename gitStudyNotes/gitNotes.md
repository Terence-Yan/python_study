### *********git 命令*********

#### 1.将远程仓库的文件导入到本地：git clone+远程仓库地址

#### 2.查看用户的注册信息：git config --list

#### 3.查看文件状态：git status

#### 4.使用Git Bash命令时，查看Windows系统当前的编码格式：echo $LANG

#### 5.改变系统的当前编码格式：export LANG=en_US.UTF-8(设置为UTF-8编码格式)或 export LANG=zh_CN.GBK  (设置为中文编码格式)，
执行该命令，改变的将只是当前会话的编码，新建会话或重启系统，都将恢复至初始默认值。

#### 6.给项目添加新文件夹
```
1.下载项目到本地：git clone <project-url>
2.查看项目状态：git status
3.在本地编辑项目，添加新文件夹
4.进入新添加的文件夹所在目录(即父目录)，查看项目状态：git status
5.将要提交的新文件夹加入待提交列表：git add <file-name>
6.提交本次添加操作：git commit -m "提交日志"
7.将本次更新推到github上：git push（需要用户名与密码）
```
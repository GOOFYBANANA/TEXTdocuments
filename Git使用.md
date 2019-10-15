# Git 使用命令

- 1.Git初始化：`git init`
- 2.初始化用户名：`git config --global user.name '用户名'`
- 3.初始化用户邮箱：`git config --global user.name '邮箱'`
- 4.克隆远程库到本地：`git clone 远程库地址`
- 5.文件上传到本地库：
  - 1.先上传到暂存区：`git add 文件名`
  - 2.查看文件是否提交到暂存区:`git status`
  - 3.从暂存区上传到本地库：`git commit -m '提交信息'`
- 6.本地库文件上传到远程库：`git push`
- 7.本地库文件删除：
  - 1.删除本地库中文件：`rm -rf 文件名`
  - 2.删除暂存区文件：`git rm 文件名`
  - 3.确定删除：`git commit -m '删除信息'`
- 8.修改本地库文件：
  - 1.修改文件：`vim 文件名`
  - 2.提交到暂存区：`git add 文件名`
  - 3.更新到本地库：`git commit -m '提交信息'`
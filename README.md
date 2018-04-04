# code1803b1
课堂代

 1.克隆一个新的仓库到当前目录
...
  git clone git@gitee.com:ytbb/code1803b11.git
...
  # 查看git项目状态
 ...
  git status
 ...
  #添加
 ...
  $ git add -A
  $ git commit -m"我的第一次提交"
  $ git push origin master

  2.远程仓库
  添加远程仓库地址
  $git remote origin git@gitee.com:ytbb/code1803b11.git
  $git remote set-url origin git@gitee.com:ytbb/code1803b11.git

  查看远程地址

  $ git remote -v

  添加忽略

  $echo"*.wmv">>.gitignore

  拉去代码
  $ git pull origin master

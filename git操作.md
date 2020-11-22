## github入门篇

- 学会建立仓库并且push到github上
   | git init                                                     |                                   |
   | git add . (git add 指定文件名)                               | 把文件添加到缓存区               |
   | ------------------------------------------------------------ | -------------------------------- |
   | git status                                                   | 查看下现在的状态                 |
   | git commit -m "注释"                                         | 把文件提交到本地仓库             |
   | 在GitHub上创建一个仓库                                       |                                  |
   | git remote add origin git@github.com:用户名/仓库名.git       | 和本地仓库进行关联               |
   | git push -u origin master（仓库空的）                        | 把本地库的所有内容推送到远程仓库 |
   | git pull --rebase origin master     git push origin master（非空） |                                  |
  | 以后 git push origin master                                  |                                  |

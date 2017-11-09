- 在GitHub上上传本地库以及电脑关联

  ```
  $ git remote add origin git@github.com:yinjw1995/learngit.git
  关联电脑的key
  ```

  账户名和文件名

  ```
  $ git push -u origin master
  将本地库提交到GitHub上
  ```

  ```
  $ git push origin master
  以后如果对本地库进行修改后，只需同步即可
  ```

- 从远程库克隆

  在GitHub上创建一个新库后，或者已有的库需要下载到本地git文件夹中，使用：

  ```
  $ git clone git@github.com:yinjw1995/hello-world.git
  文件保存在当前MINGW文件夹下
  ```

  也可以使用https，但是麻烦，不过有些地方只能使用这个

- 创建分支和合并分支

  ​
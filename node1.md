## 如何将本地文件上传到github中

1.在D盘中创建一个Github的文件夹，然后右键打开git bush

2.在命令行中输入

`$ git int demo`

3.进入仓库demo文件夹中

`$ cd demo`

4.创建一个text文件

`$ touch a.text`

5.在a.text中写hello world 并保存

6.将a.text添加到缓存区

`$ git add a.text`

7.提交缓存区内容

`$ git commit - m "first commit"`

8.配置个人用户名和邮箱

`$ git config --global user.name "AdminVen" `

`$ git config --global user.email 1743088025@qq.com`

9.远程到自己上传的地址

`$ git remote add origin https://github.com/AdminVen/demo.git`

10.先更新仓库,更新完后本地仓库会多一个README.md文件

`$ git pull -u origin master`

11.推送代码

`$ git push -u origin master`

******



### 从github中克隆文件

`$ git clone https://github.com/AdminVen/demo`






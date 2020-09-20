# Windows Principles and Its Applications

✔push to GitHub

try to pull in vs...

✔easily successful pulled 
but must commit the changes in vs before push to github


problem：could not read Username for 'https://github.com': terminal prompts disabled

solution：refrush the team explorer;if not work,try the following tip：

打开项目所在的目录下.git文件夹，打开config文件。

修改[remote “origin”]下的
url = https://github.com/hddevteam/ServerMonitor-for-UWP.git
为
url = https://自己的用户名:自己的密码@github.com/hddevteam/ServerMonitor-for-UWP.git
这里的“hddevteam”网上可能有不同的说法，这个是我们的团队名，个人开发的话是自己的用户名，一般不需要改。




✔push to gitee

团队资源管理器->同步->操作->打开命令指示符

git push -u origin_gitee master -f
强制推送一次后，即可
以后只需正常分别向origin和origin——gitee推送即可。
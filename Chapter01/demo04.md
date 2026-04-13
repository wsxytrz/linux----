# 用户组的管理
创建
* groupadd 用户组名
删除
* groupdel 用户组名

# 用户管理
创建
* useradd [ -g  -m -d] 用户名
-g 确定组名      例：**useradd [plan1]   plan1既是组也是用户**
-m /etc/passwd 中记录的主目录+自动创建目录
-d /etc/passwd 中记录的主目录
删除
* userdel [-r] 用户名
-r 删除更彻底

修改用户所属组
* usermod 
-aG 用户名 用户组名         追加
-g                         改变
查看用户所属组
* id [用户名]





**用户有 UID（如 1002），可以登录、有家目录。
组有 GID（如 1002），用于文件权限管理，不能登录。**
查看所有用户
cat /etc/passwd 或getent passwd
查看所有组
cat /etc/group  或getent group





ctrl+l | clear 清屏

ctrl+d 退出登陆

sudo su - root 不用密码

history 查看历史命令

ctrl+a(开头)|e(结尾)|鼠标左/右键（向左向右一个单词）

| 管道符 将前一个命令输出传递到后一个命令输入
例： ll | grep "txt"
# 下载
apt -y [install（下载）| remove (删除) | research (查找)]  软件名称
 
 **ubuntu   .deb apt**
 **centOS   .rpm yum**


wget 非交互式文件下载器     下载网络文件工具
wget [-b后台下载，写入日志wget-log] url(下载链接)


curl [-o] url 发起网络祈求
下载文件，获取信息 打开网页



# systemctl 控制服务
systemctl start(开始)|stop(结束)|status(查看状态)|enable(开启开机自启)|disable(关闭开机自启)  服务名
ubuntu 
ufw 防火墙
NetworkManager 主网络管理
systemd-network 副网络管理
ssh  远程连接


netstat
-t / -u ：分别只看 TCP 或 UDP

-l ：只显示正在监听的（服务端）端口

-a ：所有（包括监听 + 已建立连接）

-n ：强制数字显示，不把端口转成服务名、IP 转成主机名，速度快最关键

-p ：显示使用该套接字的进程 PID 和名称，需要 root 权限

-r ：显示路由表

-i ：网络接口统计

-s ：各协议的详细统计


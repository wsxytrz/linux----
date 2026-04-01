**su - toot**超级管理员
*统配符 *
*重定符 >  >>
# 创建
文件夹  mkdir [linux路径]
文件    touch [linux路径]

# 查看
文件  cat []
      more []    可翻页
q 退出
# cp 复制
copy
语法：cp [-r] 参数1 参数2
参数1：被复制对象
参数2：复制地点

# mv 移动
mv 1 2
1 go 2


# rm 删除
rm -rf /* 相当与格式化
支持通配符 模糊匹配
-f 强制删除

# 查看
1. wich 查找命令

例如：which pwd

2. find 查找文件
2.1 文件名查找 find 起始路径 -name "文件名"
2.2 文件大小查找 find 起始路径 -size +|-[kMG]

# echo 打印 增加
echo `pwd`
echo "hi" >> text.txt
 
# tail 查看文件尾部，跟踪文件
tail -f -num []
-f 持续跟踪
-num 查看尾部行数

# grep 通过关键字过滤文件行
grep [-n] 关键字 linux路径
-n 关键字行数显示

# wc命令
-c 统计bytes数量
-m 统计字符数
-l 统计行数
-w 统计单词数
wc [] linux路径


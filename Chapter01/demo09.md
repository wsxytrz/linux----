# 压缩和打包
## tar (tarball)

语法：tar [] 参数


c ：create，创建新的压缩包。
v ：查看进度
z ：使用 gzip 压缩算法。 不使用就为tarball模式
v ：verbose，显示正在处理的文件列表（可省略，写成 -czf）。
f ：file，指定压缩包的文件名（必须放在最后，后面紧接文件名）。
x :解压模式
C :解压目的地 单独使用

常用组合
压缩：
tar -cvf 创建文件.tar 要打包文件
tar -zcvf 所创文件.tar.gz 要压缩文件
解压：
c换x
tar -zxvf  压缩文件 -C 解压目的地

## zip
压缩
zip [-r] 创建文件。zip  要压缩文件
r :要压缩的文件中有文件
解压
upzip 要解压文件 -d 解压地址


***解压同名替换**
**zip压缩程度比tar更厉害**
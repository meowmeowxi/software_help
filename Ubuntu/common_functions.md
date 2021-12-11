#### 1.更新安装包
`sudo apt update`
#### 2.进入根目录
`cd /`
#### 3.list files
`ls`
#### 4.make directory
`mkdir`  
![linux cd](../assets/Ubuntu/linux-cd.png)  
#### 5.重启
立即重启：`shutdown -r now`
#### 6.重命名文件
`mv server.js index.js`
#### 7.联网测试
`ping www.baidu.com`,有返回包有网，否则没有。按`ctrl+c`终止命令  
（就测试来看，NAT模式一般有网，桥接模式没网）
#### 8.复制文件夹
`cp -r /home/miao/code/nju /home/miao/code/export/nju`  
`/home/miao/code/nju`源文件夹，`/home/miao/code/export/nju`新文件夹（nju文件夹原来不存在，新建的）  
复制到当前文件夹`cp -r /home/miao/code/nju ./` 
#### 9.命令行可翻页
命令后加`|more`，比如`docker ps -a --no-trunc|more`  
#### 10.删除文件
删除文件: `rm -f mongo.tar`  
删除文件j夹: `rm -rf mongo`
#### 11.界面版Ubuntu与命令行版切换
变为界面版: `ctrl+alt+F1`  
变为命令行版: `ctrl+alt+F3`
#### 12.Linux Shell文件名自动补全
输入前几个字母，按tab键
#### 13.Linux查找文件
`find / -name mmcv`
#### 14.移动文件夹
 `mv /tmp/coco ./`
#### 15. 查看NVIDIA信息
`nvidia-smi`
#### 16.保持程序后台运行
运行命令后面加 &
#### 17.如何查看当前运行的进程
 `ps aux |grep python`
#### 18.如何杀死某个进程
`kill 6510`
#### 19.打包
解包：tar xvf FileName.tar  
打包：tar cvf FileName.tar DirName  
注：tar是打包，不是压缩
#### 20.查看文件大小
stat filepath

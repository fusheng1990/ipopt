# ipopt
install


Ipopt安装：
① 从github上下载Ipopt源码包。(https://github.com/coin-or/Ipopt)
② sudo apt-get install libblas3gf libblas-dev liblapack3gf liblapack-dev gfortran
③ 解压hsl的压缩包(在卓姐那里)，然后将include下的文件，移动至/usr/local/include目录下，将lib下的文件，移动至/usr/local/lib下，然后，运行命令$ sudo ln -s /usr/local/lib/libcoinhsl.so /usr/lib/libhsl.so，记住，在创建软链接时，千万用完整的目录名字。
④ 解压Ipopt源码，cd进目录，依次运行：
$ ./configure
$ make
$ make test
好了，完毕了

http://blog.csdn.net/azhuty/article/details/68485569

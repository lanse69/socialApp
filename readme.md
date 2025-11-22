此程序用于局域网下的社交

设备中需下载安装并配置好cmake,gcc,mysql,并下载配置mysql++

在服务端运行Server，并将作为服务端的设备的ip(可用ifconfig查看)修改到Client/main.cpp的第28行中

Client为客户端

服务端:
    cd Server
    mkdir build
    cd build
    cmake ..
    make
    sudo make install
客户端：(请完成第5行操作后在编译)
    cd Client
    mkdir build
    cd build
    cmake ..
    make
    sudo make install

如果你想用iconSocial图片作为图标的话:
mkdir /home/Picture
cp ./iconSocial.jpg /home/Picture/
然后将两个.desktop文件中被注释掉的Icon取消注释，将每注释掉的Icon注释掉


cp socialAppServer.desktop /usr/share/applications/
cp socialAppClient.desktop /usr/share/applications/


// author's Email:
// 兰寅银: lan_yinyin@qq.com
// 朱灿银: 28928256l21@qq.com
// 周俊: zhoujun1108@126.com

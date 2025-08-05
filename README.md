# myChatServer
可以工作在nginx tcp的负载均衡环境中的集群聊天服务器和客户端源码，基于muduo（仅供学习使用）

编译方式
cd build
rm -rf *
cmake ..
make

运行环境
需要mysql nginx redis服务

bin文件夹下ChatServer是聊天服务器程序
ChatClient是聊天客户端程序

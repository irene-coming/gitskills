# c_mysql_multi_query使用说明：  

# 编译命令  

g++ -g -o multiQuery.o -L/opt/mysql/lib -I/opt/mysql/include -lmysqlclient mysql_real_connect.cpp

# 可能遇到的问题：  

## 1，g++找不到， yum install gcc-c++

## 2,libmysqlclient.so.20找不到，/etc/ld.so.conf.d/mariadb-x86_64.conf，添加mysql lib的路径并执行 ldconfig

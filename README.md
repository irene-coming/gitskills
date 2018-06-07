#g++ compile files for connector c related files
g++ -g -o multiQuery.o -L/opt/mysql/lib -I/opt/mysql/include -lmysqlclient mysql_real_connect.cpp

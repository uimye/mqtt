
Ubuntu-12.04中Mosquitto安装和使用 ：http://blog.csdn.net/xukai871105/article/details/39252653

remark:
1. Error: Invalid user 'mosquitto'的解决方法：
   mosquitto.conf中添加user root(user mosquitto下面添加)
   ./mosquitto -c mosquitto.conf -v
   或
   adduser mosquitto


mosquitto 使用时出现的一些问题及其解决办法 : http://blog.csdn.net/houjixin/article/details/46711547
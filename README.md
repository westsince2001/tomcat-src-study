1. 安装IDEA，配置maven，jdk8
2. git clone项目， idea maven项目打开
3. 下载apache-tomcat-8.5.15
   wget http://mirrors.tuna.tsinghua.edu.cn/apache/tomcat/tomcat-8/v8.5.15/bin/apache-tomcat-8.5.15.tar.gz
   解压到指定目录比如 /home/apache-tomcat-8.5.15
4. 配置idea run
   Main Class： org.apache.catalina.startup.Bootstrap
   Vm Options：-Dcatalina.home=/home/apache-tomcat-8.5.15
5. run或debug调试源码   
   
   
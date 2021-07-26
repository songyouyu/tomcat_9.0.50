添加 Application 后, 设置 Main Class 和 VM options.

Main Class:
org.apache.catalina.startup.Bootstrap

VM options(实际路径需要修改):
-Dcatalina.home=C:/doc/IDEA/Study/apache-tomcat-9.0.50-src/home
-Dcatalina.base=C:/doc/IDEA/Study/apache-tomcat-9.0.50-src/home
-Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager
-Djava.util.logging.config.file=C:/doc/IDEA/Study/apache-tomcat-9.0.50-src/home/conf/logging.properties

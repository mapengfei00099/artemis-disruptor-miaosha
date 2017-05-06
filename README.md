# artemis-disruptor-miaosha
基于Apache Artemis 和 Disruptor 的秒杀项目demo

## 编译打包
1. 到[这里](http://www.oracle.com/technetwork/database/features/jdbc/jdbc-drivers-12c-download-1958347.html)下载ojdbc7.jar，然后运行以下命令将其安装到到本地maven仓库
```bash
mvn install:install-file -Dfile=ojdbc7.jar -DgroupId=com.oracle -DartifactId=ojdbc -Dversion=12.1.0.2 -Dpackaging=jar
```
2. 运行``maven clean install``命令打包整个项目
3. 到``web/target/artemis-disruptor-miaosha-web-1.0.0-SNAPSHOT.war``获得webapp的war包
4. 到``backend/target/artemis-disruptor-miaosha-backend-1.0.0-SNAPSHOT.jar``获得后端程序的jar包

## 准备环境

1. 安装JDK8

2. 下载[Apache Artemis 1.5.4](https://www.apache.org/dyn/closer.cgi?filename=activemq/activemq-artemis/1.5.4/apache-artemis-1.5.4-bin.tar.gz&action=download)

解压之后到任意



3. 下载

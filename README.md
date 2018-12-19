
3、将数据导入到mysql数据库中

在mysql文件夹下有schema.sql文件，直接运行即可。

4、项目构建

mvn clean install -Dmaven.test.skip=true
5、项目运行

在target目录下会生成一个jar包文件(如my-blog-3.1.1-SNAPSHOT.jar)，执行如下命令：

java -jar my-blog-3.1.1-SNAPSHOT.jar
即可启动web浏览器进行访问，端口默认为8080。

6、新增了启动脚本

sh my-blog.sh start

# rockermq-doc
rocketmq测试使用过程

下载docker镜像：docker pull vongosling/rocketmq

下载结果： docker images | grep rocketmq

docker.io/vongosling/rocketmq     latest     b23eb8526819     8 months ago     727.8 MB

启动容器：
docker run -p 9876:9876 -p 10911:10911 --rm vongosling/rocketmq

--rm 在exit后删除容器  

进行功能测试：

1.创建topic
2.生产数据
3.消费数据

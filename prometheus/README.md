### 安装`node_exporter`+`prometheus`

`docker-compose.yml`中相关的挂载目录（配置文件的位置）需要根据实际情况来

#### 相关说明
- node_exporter
  > 监控服务器CPU、内存、磁盘、I/O等信息，并提供可供prometheus使用的数据导出接口
- prometheus
  > prometheus是一个监控系统和一个时间序列数据库

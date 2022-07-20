### 安装`loki`+`promtail`+`grafana`

`docker-compose.yml`中相关的挂载目录需要根据实际情况来，包括配置文件的位置

#### 相关说明
- loki
  > Loki 是一个日志聚合系统，旨在存储和查询来自所有应用程序和基础架构的日志
- promtail
  > Promtail 可以把本地日志内容发送到Loki上，是一个日志收集系统
- grafana
  > Grafana是一个跨平台的开源的度量分析和可视化工具，可以通过将采集的数据查询然后可视化的展示
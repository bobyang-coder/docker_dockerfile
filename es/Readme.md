[TOC]
# 启动单节点
```
docker run -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" docker.elastic.co/elasticsearch/elasticsearch:6.4.3
```


# 启动集群
- 使用docker-compose.yml文件启动
# services

Docker 服务集群

[![Docker Image CI](https://github.com/CS-Tao/services-aliyun/workflows/Docker%20Compose%20CI/badge.svg)](https://github.com/CS-Tao/services-aliyun/actions)

## 项目依赖

- docker
- docker-compose

## 已配置服务

![services_graph.svg](https://home.cs-tao.cc/services-aliyun/services_graph.svg)

## 部署方法

1. 克隆本仓库

   ```bash
   git clone https://github.com/CS-Tao/services-aliyun.git
   ```

1. 添加环境变量文件`.env`到项目根目录，复制`ci.env`内容到`.env`文件中，并修改其中各项环境变量的值

1. 拉取镜像

   ```bash
   docker-compose pull
   ```

1. 启动容器组

   ```bash
   docker-compose up -d
   ```

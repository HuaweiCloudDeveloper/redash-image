# nifi部署指南

## ‌一、环境准备

### 一、更新系统

```bash
yum -y update  
yum -y upgrade
```

## ‌二、安装docker

#### EulerOS2.0
安装Docker：[安装脚本](../scripts/delopy_docker.sh)

## ‌三、编写docker-compose
示例：[docker-compose.yml](../scripts/docker-compose.yml)

## 四.创建容器
```bash
cd /opt/redash && docker-compose up -d --force-recreate
```

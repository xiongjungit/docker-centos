## Ubuntu Dockerfile

> 更新源为阿里云centos更新源

这个仓库包含[自动构建](https://registry.hub.docker.com/_/d:ockerfile/centos/)centos基础镜像的docerfile文件

### 基础镜像

* [centos:centos7.1.1503](https://hub.docker.com/_/centos/)

### 安装和构建

1. 安装 [Docker](https://www.docker.com/)

2. 构建 `docker build -t="dockerxman/docker-centos" github.com/xiongjungit/docker-centos`

### 使用

```
docker run -it --rm dockerxman/docker-centos
```

### github

[github](https://github.com/xiongjungit/docker-centos)

### dockerhub

[dockerhub](https://hub.docker.com/r/dockerxman/)

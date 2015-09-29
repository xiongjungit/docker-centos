## 阿里云yum源的CentOS 7的docker基础镜像

![](https://dn-daoweb-resource.qbox.me/image-icon/centos.svg)

[CentOS](https://www.centos.org)（Community Enterprise Operating System，中文意思是：社区企业操作系统）是Linux发行版之一，它是来自于Red Hat Enterprise Linux依照开放源代码规定释出的源代码所编译而成。由于出自同样的源代码，因此有些要求高度稳定性的服务器以CentOS替代商业版的Red Hat Enterprise Linux使用。两者的不同，在于CentOS并不包含封闭源代码软件。


这个仓库包含[自动构建](https://registry.hub.docker.com/_/d:ockerfile/centos/)centos基础镜像的docerfile文件

### 基础镜像

* [centos:centos7.1.1503](https://hub.docker.com/_/centos/)

### 安装和构建

1. 安装:  [Docker](https://www.docker.com/)

2. 构建:  `docker build -t="dockerxman/docker-centos" github.com/xiongjungit/docker-centos`

### 使用

```
docker run -it --rm dockerxman/docker-centos
```

## 代码创建和维护

* QQ: 479608797

* 邮件:  fenyunxx@163.com

* [github](https://github.com/xiongjungit/docker-centos)

* [dockerhub](https://hub.docker.com/r/dockerxman/)

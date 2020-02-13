# https://skywalking.apache.org/zh/blog/2019-08-30-how-to-use-Skywalking-Agent.html
# 执行镜像构建前先下载skywalking包到当前目录
# wget http://mirrors.tuna.tsinghua.edu.cn/apache/skywalking/6.6.0/apache-skywalking-apm-6.6.0.tar.gz && tar -zxvf apache-skywalking-apm-6.6.0.tar.gz
FROM busybox:latest 

ENV LANG=C.UTF-8

RUN set -eux && mkdir -p /usr/skywalking/agent/

ADD apache-skywalking-apm-bin/agent/ /usr/skywalking/agent/

WORKDIR /
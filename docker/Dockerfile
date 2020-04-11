FROM node:10.20.0-alpine3.9

# WORKDIR: 如果目录不存在, 则自动创建
WORKDIR /app/
ADD . /app/

RUN echo "Asia/Shanghai" > /etc/timezone \
    && echo "https://mirrors.ustc.edu.cn/alpine/v3.9/main/" > /etc/apk/repositories  \
    && npm config set registry https://registry.npm.taobao.org \
    && npm install hexo-cli -g \
    && npm install

EXPOSE 4000


ENTRYPOINT ["hexo","server"]

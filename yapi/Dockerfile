ARG NODE_VERSION
FROM node:${NODE_VERSION}

RUN sed -i "s/deb.debian.org/mirrors.aliyun.com/g" /etc/apt/sources.list \
    && apt update \
    && apt install -y vim

RUN npm config set registry https://registry.npm.taobao.org

RUN npm install -g yapi-cli && npm install pm2 -g
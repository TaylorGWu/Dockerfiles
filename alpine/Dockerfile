FROM alpine
MAINTAINER Taylor's alpine

# update apk source
RUN echo "https://mirrors.aliyun.com/alpine/v3.6/main/" > /etc/apk/repositories
RUN echo "https://mirrors.aliyun.com/alpine/v3.6/community/" >> /etc/apk/repositories

# update apk
RUN apk update

# install bash
RUN apk add bash

# install python
RUN apk add python \
            python-dev \
            py-pip

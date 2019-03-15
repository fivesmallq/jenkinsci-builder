FROM maven:3.6.0-jdk-8-alpine

LABEL maintainer.name="fivesmallq"
LABEL maintainer.email="fivesmallq@gmail.com"

RUN apk add --no-cache \
    unzip \
    wget \
    curl \
    zip \ 
    python \
    tzdata
    
# Timezone
ENV TZ=Asia/Shanghai
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/
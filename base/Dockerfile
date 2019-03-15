FROM alpine

LABEL maintainer.name="fivesmallq"
LABEL maintainer.email="fivesmallq@gmail.com"
LABEL description="base image"

RUN apk add --no-cache \
    unzip \
    wget \
    curl \
    zip \ 
    python \
    tzdata
    
# Timezone
ENV TZ=Asia/Shanghai

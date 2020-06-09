FROM alpine

RUN apk add go git && \
    mkdir /project && \
    go get -u github.com/labstack/echo/...

WORKDIR /project

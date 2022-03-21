FROM alpine:3.15

# Roswell Install & Setup
RUN apk add --no-cache make && \
    apk add --no-cache --repository=http://dl-cdn.alpinelinux.org/alpine/edge/testing roswell && \
    ros run -q && \
    apk del make


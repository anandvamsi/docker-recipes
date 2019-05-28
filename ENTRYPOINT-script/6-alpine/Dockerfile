FROM node:6-alpine
RUN apk add --no-cache 'su-exec>=0.2'
RUN mkdir /data && chown node:node /data
COPY entrypoint /usr/local/bin/
ENTRYPOINT ["entrypoint"]

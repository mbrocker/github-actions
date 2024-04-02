FROM alpine:3.10

COPY entrypoint.sh /entrypoint.sh

RUN chmopd +x entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]

FROM debian:9.5-slim
LABEL MAINTAINER: sabata-cafod
WORKDIR /tmp
ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]

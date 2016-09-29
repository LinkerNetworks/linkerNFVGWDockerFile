FROM alpine

USER root
WORKDIR /usr/local/bin

ENV ADDRESSES nil
ENV MONITOR_TYPE nil

COPY monitor /usr/local/bin/monitor

ENTRYPOINT ["monitor"]

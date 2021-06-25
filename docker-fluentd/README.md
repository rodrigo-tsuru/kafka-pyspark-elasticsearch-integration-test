# Based on https://hub.docker.com/r/fluent/fluentd/

# Quick start
docker run -d -p 24224:24224 -p 24224:24224/udp -v /data:/fluentd/log

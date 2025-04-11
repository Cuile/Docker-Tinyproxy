FROM alpine:3.10

RUN apk add --no-cache \
	bash \
	tinyproxy

COPY ./docker/run.sh /opt/docker-tinyproxy/run.sh

ENTRYPOINT ["/opt/docker-tinyproxy/run.sh"]

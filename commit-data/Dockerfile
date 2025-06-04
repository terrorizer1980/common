FROM alpine:3.22.0

RUN apk add --no-cache git

COPY entrypoint.sh /entrypoint.sh
RUN chmod 755 /entrypoint.sh

ENTRYPOINT /entrypoint.sh

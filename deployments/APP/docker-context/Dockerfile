FROM alpine:3.10.1
RUN apk add --update \
    curl \
    && rm -rf /var/cache/apk/*
ENTRYPOINT ["curl"]

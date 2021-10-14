FROM alpine
ENV AWSCLI_VERSION "2.1.29"
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python3 py3-pip && pip install awscli==$AWSCLI_VERSION --upgrade --user \
    && rm -rf /var/cache/apk/*
CMD tail -f /dev/null

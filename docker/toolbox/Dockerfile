FROM alpine
RUN apk add --no-cache curl wget tree busybox-extras netcat-openbsd python3 py-pip bash && \
    pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
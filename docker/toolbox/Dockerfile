FROM alpine
RUN apk add --no-cache python3 curl wget busybox-extras netcat-openbsd  py-pip bash
RUN pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
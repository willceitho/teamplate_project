FROM 3.9.0rc1-alpine3.12
RUN apk add --no-cache python3 curl wget busybox-extras netcat-openbsd  py-pip bash
RUN pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
FROM python:rc-alpine
RUN apk add --no-cache python3 curl wget busybox-extras netcat-openbsd  py-pip bash
RUN curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip" && \
unzip awscliv2.zip && \
./aws/install
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
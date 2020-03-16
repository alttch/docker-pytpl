from alpine:3.9.3
RUN apk add gcc
RUN apk add g++
RUN apk add tar
RUN apk add musl-dev
RUN apk add linux-headers
RUN apk add python3 python3-dev
RUN apk add postgresql-libs postgresql-dev
RUN apk add curl
RUN python3 -m venv /opt/venv
COPY req.txt /tmp/
RUN /opt/venv/bin/pip3 install -r /tmp/req.txt
RUN tar cvf /build.tar /opt/venv /usr/lib/libstdc* /usr/lib/libgcc_s*

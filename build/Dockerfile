from alpine:3.9.3
RUN apk add gcc
RUN apk add g++
RUN apk add tar
RUN apk add musl-dev
RUN apk add linux-headers
RUN apk add python3 python3-dev
RUN apk add postgresql-libs postgresql-dev
RUN python3 -m venv /opt/venv
RUN /opt/venv/bin/pip3 install psycopg2 sqlalchemy
RUN /opt/venv/bin/pip3 install redis
RUN /opt/venv/bin/pip3 install cachetools
RUN /opt/venv/bin/pip3 install flask flask_jsonrpc jinja2 gunicorn
RUN /opt/venv/bin/pip3 install requests
RUN /opt/venv/bin/pip3 install jsonrpcclient
RUN /opt/venv/bin/pip3 install filemap
RUN tar cvf /build.tar /opt/venv /usr/lib/libstdc* /usr/lib/libgcc_s*

from alpine:3.9.3
RUN apk add python3
RUN apk add supervisor
RUN apk add postgresql-libs
RUN apk add curl
ADD build.tar /
COPY supervisord.conf /etc/supervisor/
CMD [ "/usr/bin/supervisord", "-n", "-c", "/etc/supervisor/supervisord.conf" ]

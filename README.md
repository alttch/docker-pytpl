# pytpl

Primary Docker container template for Python applications

## System info

OS: Alpine Linux

Python: /opt/venv
gunicorn: /opt/venv/bin/gunicorn

Launcher: supervisord

## Builds

### 8+

OS: Alpine 3.9.3

psycopg2==2.8.4
sqlalchemy==1.3.13
redis==3.4.1
cachetools==4.0.0
flask==1.1.1
flask_jsonrpc==0.3.1
jinja2==2.11.1
gunicorn==20.0.4
requests==2.23.0
jsonrpcclient==3.3.5
filemap==0.0.7

# docker-pytpl

Primary Docker container template for Python applications

## Usage

Use in *Dockerfile*:

```
from altertech/pytpl:<build>
```

## System info

OS: Alpine Linux

Python: /opt/venv
gunicorn: /opt/venv/bin/gunicorn

Launcher: supervisord

## Builds

## 25

* pyaltt2==0.0.60

## 19

* simplejson==3.17.0

### 18

* pyaltt=0.0.54

### 16

* pyaltt2=0.0.50

### 10

* python-rapidjson==0.9.1

### 9

OS: Alpine 3.9.3

* pyaltt2==0.0.37
* filetype==1.0.5
* psycopg2==2.8.4
* sqlalchemy==1.3.13
* redis==3.4.1
* cachetools==4.0.0
* flask==1.1.1
* flask_jsonrpc==0.3.1
* jinja2==2.11.1
* gunicorn==20.0.4
* requests==2.23.0
* jsonrpcclient==3.3.5
* filemap==0.0.7

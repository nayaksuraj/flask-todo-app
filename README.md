### Basic Todo Flask Application

```text
- add Todo
- delete Todo
- update Todo
```

### setup environment
```text
$ sudo pip3 install virtualenv
$ virtualenv env
$ source env/bin/activate
$ pip3 install flask flask-sqlalchemy
```

### create sqlite db
```text
$ source env/bin/activate
$ python
>>> from app import db
>>> db.create_all()
```

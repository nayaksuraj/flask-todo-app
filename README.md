```text
Basic Todo Flask Application
- add Todo
- delete Todo
- update Todo
```

```text
# setup environment
$ sudo pip3 install virtualenv
$ virtualenv env
$ source env/bin/activate
$ pip3 install flask flask-sqlalchemy
```

```text
# create sqlite db
$ source env/bin/activate
$ python
>>> from app import db
>>> db.create_all()
```

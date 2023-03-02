
To start virtual env:
$ source env/bin/activate


Launch Flask App:
$ python3 app.py

Troubleshooting:
$ flask shell
>>> db.create_all()
or
>>> from app import app, db
>>> app.app_context().push()
>>> db.create_all()

Manual Post:
#db.session.add(Todo(content='Task1', completed=False))
#db.session.commit()




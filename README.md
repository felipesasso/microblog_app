# microblog_app

This is simple microblog created using Flask framework.
Before running the microblog app make sure you have done the following:

1. Created a Virtual Environment and installed all the requirements in requirements.txt

2. Set FLASK_APP environment variable running:
```
$ export FLASK_APP=microblog.py
```
If you are using Microsoft Windows, use set instead of export in the command above.

3.  Created all the tables in database running the following command:
```
$ flask db upgrade
```

After you have gone through each item of the checklist, you may run the app using:
```
$ flask run
```

Zoe"-Zach Project
=================

# Goal
To have a website that displays a graph of a social network to its users such that they gain access to one another's information based on friend connections
and boolean sharing controls they set.

# To Run

Setup
-----

```
$ virtualenv -p<path/to/python3> venv # only do this once
$ source venv/bin/activate # or activate.csh, activate.fish depending on shell
$ pip install -r requirements.txt
```

Running the app
---------------

For all of these, `source venv/bin/activate` is required.
When finished, use `deactivate` to stop using the app's locally installed
python3 environment and packages.

**Starting the application on localhost:8080**

```bash
$ make # Ctrl-c to quit
```

**To reset a user's password**

```bash
$ python reset_password.py app.db # or wherever the app database is
```

**To wipe the database completely**

```bash
$ make clean
```

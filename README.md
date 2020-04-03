# Flask Test

Walking through some of the Flask documentation.

Important terminal commands to remember:

```
$ mkdir my project
$ cd myproject
$ python3 -m venv venv
```
This creates a project folder and sets up the Python virtual environment

```
$ . venv/bin/activate
```
This activates the virtual environment in the project folder.

```
$ pip install Flask
```
This installs Flask in the virtual environment.

```
$ export FLASK_APP=hello.py
$ export FLASK_ENV=development
$ flask run
```
Sets the hello.py file to be run on a built-in server in development mode, allowing for automatic refresh and bug tracking.
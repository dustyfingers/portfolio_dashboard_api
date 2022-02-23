This is the api for my portfolio dashboard I build with Python 3 and Flask that makes requests against a MySQL database

# Prerequisites
python 3

# Requirements
aniso8601==8.0.0
click==7.1.2
Flask==1.1.2
Flask-RESTful==0.3.8

# Virtual Env Setup
windows setup:

run the following (replace the fp below with the location of your local python 3.6 installation): `virtualenv . -p C:/Users/PC/AppData/Local/Programs/Python/Python36/python.exe`

to activate the virtual env run: `./Scripts/activate`

to deactivate just run: `deactivate`

to start a new virtual env contained here run: `virtualenv . -p C:/Users/PC/AppData/Local/Programs/Python/Python36/python.exe`

macos setup: to set up the virtual env run: `virtualenv venv`

if you want your virtualenv to inherit globally installed packages, run: `virtualenv venv --system-site-packages`

to run the virtualenv, run: `source venv/bin/activate`

to leave the virtual env, run: `deactivate`

# Instructions
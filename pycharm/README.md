# website_dsc180a
Simple setup.

Two command line windows.

# First command line window:
> cd website_dsc180 (or whatever directory you will be using)

> python3 -m venv env

> source env/bin/activate

> pip install flask_sqlacademy

> pip install flask_cors

> pip install requests

You might have to install some more modules depending on your base environment.

> python3 app/run.py


# Second command line window:

Have npm/Node.js installed. You can get it online.

> cd website_dsc180 (or whatever directory you will be using)

> source env/bin/activate

> cd frontend

> npm install

> npm start

## Goto 0.0.0.0/8080 (or use localhost or whatever for the ip, key is to visit port 8080, instead of 8000)
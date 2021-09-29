# car-app

## Project setup
Open the project folder and a command-line in it.

If you have installed Python on your machine run

```
pip install virtualenv
```

If that doesn't work try with 
```
pip3 install virtualenv
```

Now in the project folder run

```
virtualenv venv
```

And then if you're on Windows 
```
venv\Scripts\activate
```
and on MacOS or Linux 
```
source venv/bin/activate
```

Before we continue make sure you see (venv) before you current working directory line (cwd).

#
Now when you see the (venv) before your line type 
```
pip install -r requirements.txt 
```

and
```
python3 manage.py migrate
```
and finally to run the django app
```
python3 manage.py runserver
```





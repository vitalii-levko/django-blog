## Prerequisites

To start using this project activate virtual environment first or install Django 1.11.~ manually:
```javascript
source ./env/bin/activate
```
or
```javascript
pip install -r requirements.txt
```

## How-to

After successful installation of Django start server with command:
```javascript
python3 manage.py runserver
```

Go to the address in web browser:
```javascript
127.0.0.1:8000
```

Start page of the blog looks as follows:

![welcome](screenshots/01.png)

Click on any post title to look at single post:

![details](screenshots/02.png)

Login as `admin` using password `q1w2e3r4`:
```javascript
127.0.0.1:8000/admin
```

![auth](screenshots/03.png)

Admin panel looks like the follows:

![admin](screenshots/04.png)

Switch to main page with admin privileges:

![privileges](screenshots/05.png)

Click plus sign to create new post:

![new](screenshots/06.png)

Single post page now contains pencil sign to edit post:

![pencil](screenshots/07.png)

Click on it to open post editor:

![edit](screenshots/08.png)

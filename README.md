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

Click on 'Add comment' to send comment for moderation:

![comment](screenshots/03.png)

Click on the 'Lock' sign to login as `admin` using password `q1w2e3r4`:

![auth](screenshots/04.png)

Admin options looks like the follows:

![admin](screenshots/05.png)

Switch to any post with admin edit, delete and approve privileges:

![privileges](screenshots/06.png)

Click on the 'Pencil' sign to open post editor:

![edit](screenshots/07.png)

Click on the 'Draft' sign to list unpublished posts:

![draft](screenshots/08.png)

Switch to any of draft posts to publish, edit or delete it:

![publish](screenshots/09.png)

And of course click on the 'Plus' sign to create new post:

![new](screenshots/10.png)

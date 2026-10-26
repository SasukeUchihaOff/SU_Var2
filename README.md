# Test stuff

The thing, I've created for taking a test

# Stack

- Python 3.10+
- Django 5.2
- SQLite

# Install and run

## Clone repository and go to file folder:

```commandline
   git clone <link to the repostitory>
   cd DE
```

## Make and activate Virtual Environment:

```commandline
   python -m venv venv
   venv\Scripts\activate          # Windows
   source venv/bin/activate       # Linux / macOS
```

## Install dependencies:

```commandline
   pip install -r requirements.txt
```

## Migrate(if it needs):

```commandline
    python manage.py migrate
```

## Run server:

```commandline
   python manage.py runserver
```

## Open [Link](http://127.0.0.1:8000/)
# Anfisa for friends
This is a basic chat bot for an ice-cream "delivery service" - Anfisa. She can check the weather in target city for you and give an advice whether you should send an ice-cream to a friend that lives there (she's a mom friend, bear with her). Anfisa doesn't have a pretty interface (yet!), but she does have a temper.

## How to run Anfisa
This is a demo project, so the SECRET_KEY is included in settings. If you want to use it in production, generate new SECRET_KEY.

Run these commands from the ```anfisa``` directory:
```
python manage.py migrate
python manage.py runserver
```
And its good to go! http://127.0.0.1:8000/

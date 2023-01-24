## Discription  
This application allows you to register, view the participants of the event and cancel the registration by phone number
## Quick start
In your command line:

```
git clone https://github.com/Deniskoltovich/Flask_application.git
cd Flask_application
```

Create virtual enviroment (optionally):

```
python3 -m venv .venv
source .venv/bin/activate
```

Install requirements:

```
pip3 install -r requirements.txt
```

Initialize database:

```
python3
>>> from db import init_db
>>> init_db()

```

Run the app:

```
python3 app.py
```

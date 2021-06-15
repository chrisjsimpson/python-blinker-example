# Python Blinker example signals events


Here we have a minimal  example of using blinker signals.

You have a new order and you need to tell people about it

- The office needs to know
- The customer needs an email
- Maybe something else, you can create as many listeners
  as you like!


# Setup 

```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

# Run

```
python main.py
```

## Help my tasks are blocking everything

Your subscribers need to be non blocking
see: 
https://github.com/chrisjsimpson/flask-background-task-queue

# poller
A sample Django to demonstrate crud capabilities.
```
pip install requirements.txt

daphne poller.asgi:application
or
uvicorn poller.asgi:application
```

Django now capable of handling non-blocking I/O thanks to Django channels and Daphne/Uvicorn

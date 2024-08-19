# Installation

~~~bash
poetry install
~~~

## Wsgi start
~~~bash
gunicorn wsgi_app:app
~~~
## Asgi start
~~~bash
uvicorn asgi_app:app --port 8001
~~~
## Starlette start
~~~bash
uvicorn starlette_app:app --port 8002
~~~
## FastAPI start
~~~bash
uvicorn fastapi_app:app --port 8003
~~~

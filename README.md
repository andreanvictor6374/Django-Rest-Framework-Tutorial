# Django REST Framework - Tutorial
Learn how to build REST APIs with Django &amp; the Django Rest Framework.

## commands


### to run javascript client
```shell
python -m http.server 8111
```
access only allowed origin when accessing js client
```python
if DEBUG:
    CORS_ALLOWED_ORIGINS += [
        'http://localhost:8111',
        'https://localhost:8111',
    ]

```



### to run django backend
```shell
python ./manage.py runserver

```

### 

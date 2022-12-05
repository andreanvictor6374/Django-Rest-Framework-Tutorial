# Django REST Framework - Tutorial
Learn how to build REST APIs with Django &amp; the Django Rest Framework.

## commands


### to run javascript client
```shell
python -m http.server 8111
# access http://localhost:8111 instead
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

### change path to SearchListOldView
we don't use algolia
backend/search/urls.py:5

### perform search from rest_framework
```shell
http://localhost:8000/api/search/?q=hello
```

### todo
1. search without algolia fails
2. find more about extend_schema()
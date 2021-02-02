# django_tutorial

## Tutorial 1
disregard ```django-admin``` ---> use ```python -m django```

Quit Server with CTRL-C

## Tutorial 2
Three Step Guide to making model changes
    1) Change your models (in models.py)
    2) Run ```py manage.py makemigrations```
    3) Run ```py manage.py migrate``` 

## Tutorial 3
Always return a HttpResponseRedirect after sucessfully dealing with POST data.
This prevents data from being posted twice if a user hits the back button
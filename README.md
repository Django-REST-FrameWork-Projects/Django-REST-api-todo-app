# Django-REST-API for the react todo app
This is a Django rest api backend for a [react front end web app](https://github.com/React-projects-tesfa/React-front-end-Todo-App).

### Build/Run
Activate a virtual environment and install dependencies
``` virtualenv venv```

``` source venv/bin/activate```

```cd todo_drf```

```pip install requirements.txt```
Run server
```python -v runserver```

```

The project is hosted locally, so the ```BASE_URL = http://127.0.0.1:8000/api/```


The following operations are avaialable (see the screenshot):

``` "List": "/task-list/",```

```"Detail View": "/task-detail/<str:pk>",```

```"Create": "task-create",```

```"Update": "/task-update/<str:pk>",```

``` "Delete": "/task-delete/<str:pk>"```


<img width="1512" alt="Screen Shot 2022-11-13 at 7 39 37 AM" src="https://user-images.githubusercontent.com/62855279/201522132-f005be15-e98e-495b-aab8-5bef4520db94.png">

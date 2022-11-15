# Django-REST-API for the react todo app
This is a Django rest api backend for a [react front end web app](https://github.com/React-projects-tesfa/React-front-end-Todo-App).

### Build/Run
###### Activate a virtual environment and install dependencies

``` virtualenv venv```

``` source venv/bin/activate```

```cd todo_drf```

```pip install requirements.txt```

###### Run server

```python -v runserver```

The project is hosted locally, so the ```BASE_URL = http://127.0.0.1:8000/api/```

##### Api usage
```
// base url
BASE_URL = "http://127.0.0.1:8000/api/"
createtask = "http://127.0.0.1:8000/api/task-create/" // json data goes in the body
updatetask = "http://127.0.0.1:8000/api/task-update/3" // json data goes in the body
deletetask = "http://127.0.0.1:8000/api/task-delete/3"
```


<img width="1512" alt="Screen Shot 2022-11-13 at 7 39 37 AM" src="https://user-images.githubusercontent.com/62855279/201522132-f005be15-e98e-495b-aab8-5bef4520db94.png">

<img width="1512" alt="Screen Shot 2022-11-14 at 9 52 45 PM" src="https://user-images.githubusercontent.com/62855279/201815097-e7324637-0c3f-40a6-b149-0a976ef592ac.png">


<img width="1512" alt="Screen Shot 2022-11-14 at 9 53 06 PM" src="https://user-images.githubusercontent.com/62855279/201815172-08c8ea37-b380-4536-8ed5-c2df299265cf.png">

<img width="1506" alt="Screen Shot 2022-11-14 at 9 55 40 PM" src="https://user-images.githubusercontent.com/62855279/201815518-e359e26f-80bb-4178-8ddf-662dc8d873de.png">



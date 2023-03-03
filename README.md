# Test Code

## Getting Started

Setup project environment with [virtualenv](https://virtualenv.pypa.io) and [pip](https://pip.pypa.io).

```bash
$ virtualenv project-env
$ source project-env/bin/activate
$ pip install -r requirements.txt
$ python manage.py migrate
$ python manage.py runserver
``
Can create admin-user to access django admin
Please use postman to test post API's 
Endpoint 
    - http://127.0.0.1:8000/check_duplicate/<str:sentence>
    - http://127.0.0.1:8000/commas/
    - http://127.0.0.1:8000/upload_file/
```

## Contributing

I love contributions, so please feel free to fix bugs, improve things, provide documentation.
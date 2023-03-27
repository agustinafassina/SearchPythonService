## SearchPythonService 🔍
This is my first repository with python and django 🐍.

### The repository has some implementations
- [x] Implemented
- [ ] Not implemented

#### Implementations:
- [x] Sql server
- [x] Migrations
- [x] Cors
- [x] Environment variables
- [ ] Docker
- [x] Post application - CRUD
- [ ] Articles application - CRUD
- [ ] Filters in the method GET
- [ ] Consume external app
- [ ] Upload a file
- [ ] Azure pipeline
- [ ] Database: mysql
<hr>

#### Environment variables with the .env file.
Create the .env file with the variables.
* DATABASE_HOST
* DATABASE_NAME
* DATABASE_ENGINE
* DATABASE_PORT

### Local build 💻
Run command where is the manager.py file.

```
python manage.py runserver
```

### Docker build and run 🚀
```
docker build -t api .
```

#### Environment variables with docker.
Variables go when docker is executed.
```
docker run -d -p 5001:80 -e "DATABASE_HOST=youbim-stg.c5tqomlevyjk.us-west-1.rds.amazonaws.com" -e "DATABASE_NAME=searchpython" -e "DATABASE_USER=root" -e "DATABASE_PASSWORD=abc123..B" --name api api
```

Path:
* http://localhost:8000
* * /admin -> Django admin interface
* * /api -> Api rest


#### New dependecies
To add the dependencies in the requirements.txt file and have the docker build.
```
pip freeze > requirements.txt
```


#### Docker example:
https://dev.to/foadlind/dockerizing-a-django-mysql-project-g4m
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
<hr>

#### Environment variables with the .env file.
Create the .env file with the variables.
* DATABASE_HOST
* DATABASE_NAME
* DATABASE_ENGINE
* DATABASE_PORT

#### Environment variables with docker.
Variables go when docker is executed.
```
docker run -d -p 5001:80 -e "DATABASE_HOST=replace" -e "DATABASE_NAME=replace"  -e "DATABASE_ENGINE=replace" -e "DATABASE_PORT=replace"  --name api api
```

### Local build 💻
Run command where is the manager.py file.

```
python manage.py runserver
```

### Docker build and run 🚀
```
docker build -t api .
docker run -d -p 5001:80 -e Environment=Development --name api api
```

Path:
* http://localhost:8000
* * /admin -> Django admin interface
* * /api -> Api rest

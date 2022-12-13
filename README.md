## SearchPythonService 🔍
This is my first repository with python and django 🐍.

### The repository has some implementations
- [x] Implemented
- [ ] Not implemented

#### Implementations:
- [x] Sql server
- [x] Migrations
- [x] Cors
- [ ] Environment variables
- [ ] Docker
- [x] Post application - CRUD
- [ ] Articles application - CRUD
- [ ] Filters in the method GET
- [ ] Consume external app
- [ ] Upload a file


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

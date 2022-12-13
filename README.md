# SearchPythonService 🔍
This is my first repository with python and django 🐍.

### The repository has some implementations
- [x] Implemented
- [ ] Not implemented

Implementations:
- [x] Migrations
- [x] Cors
- [ ] Sql server and connection string
- [ ] Environment variables
- [ ] Docker
- [ ] Post application - CRUD
- [ ] Articles application - CRUD
- [ ] Filters in the method GET
- [ ] Consume external app
- [ ] Procesar un file

### Local 💻
Run command where is the manager.py file.

```
python manage.py runserver
```

### Docker build and run 🚀
```
docker build -t api .
docker run -d -p 5001:80 -e Environment=Development --name api api
```

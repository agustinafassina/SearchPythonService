# SearchPythonService
This is my first repository with python and django.

### Local
Run command where is the manager.py file.

```
python manage.py runserver
```

### Docker build and run
```
docker build -t api .
docker run -d -p 5001:80 -e Environment=Development --name api api
```

### The repository has:
- [x] Migrations
- [x] Cors
- [ ] Environment variables
- [ ] Sql server and connection string
- [ ] Docker
- [ ] Post CRUD
- [ ] Articles CRUD
- [ ] Filters in the method GET
- [ ] Consume external app
- [ ] Procesar un file

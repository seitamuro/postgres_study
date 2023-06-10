# build 

```
docker build -t my_postgres . 
```

# run

```
docker run --name my_db -p 5432:5432 -d my_postgres
```

# connect

```
psql -h localhost -U postgres -d postgres
```
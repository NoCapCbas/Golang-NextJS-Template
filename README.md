To Start postgres container
```shell
docker compose up -d db
```

To enter postgres container 
```shell 
docker exec -it db psql -U root
```

After entering psql cli, to see all databases
```shell 
\l
```

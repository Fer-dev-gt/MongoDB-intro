## Connect to container, entrar al contenedor que esta corriendo

```
docker-compose exec mongodb bash
```

## Connect with mongosh, cualquiera de las 2 funciona

```sh
mongosh "mongodb://<user>:<password>}@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://<user>:<password>@localhost/?authMechanism=DEFAULT&tls=false"
```

## Commands to show databases and collections created
```sh
show dbs
show collections
```

## Doing some simple queries
```sh
use("platzi_store")
db-products.fint()
```
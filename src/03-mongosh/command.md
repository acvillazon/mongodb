```sh
docker compose exec mongodb mongosh "mongodb://nombreUsuario:contraseña@localhost:27017/?authMechanism=DEFAULT&tls=false"

```

## Connect to container
```sh
docker compose exec mongodb bash

```
## Connect with Mongosh

```sh
mongosh 'mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT'

```

```sh
show dbs
show collections

```

```sh
use('platzi_store')

db.productos.find({price:200});

```
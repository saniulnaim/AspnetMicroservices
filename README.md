# AspnetMicroservices

docker run -d -p 27017:27017 --name shopping-mongo mongo

docker exec -it shopping-mongo /bin/bash

show dbs

use CatalogDb // to create a new dbs

db.createCollection('Products)

db.Products.fing({}).pretty()

docker-compose -f .\docker-compose.yml -f.\docker-compose.override.yml up -d

docker-compose -f .\docker-compose.yml -f.\docker-compose.override.yml down

docker run -d -p 6379:6379 --name aspnetrun-redis redis

docker exec -it aspnetrun-redis /bin/bash
# AspnetMicroservices

docker run -d -p 27017:27017 --name shopping-mongo mongo

docker exec -it shopping-mongo /bin/bash

show dbs

use CatalogDb // to create a new dbs

db.createCollection('Products)

db.Products.fing({}).pretty()


# MongoDB Replication

## Setup

````
docker-compose up
````

## Enter Container
You can enter mongodb container
````
docker exec -it <mongodb_container_id> mongo
````
Now, You have to run commands and you need to take response like below photo.
````
rs.status()
rs.initiate()
rs.add("mongoreplication:27017")

````

### <img src="https://prnt.sc/16d2yfz" width="50px">
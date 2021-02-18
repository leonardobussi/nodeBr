
# docker run --name postgres -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=admin -e POSTGRES_DB=hero -p 5432:5432 postgres

# docker ps

# docker exec -it postgresleokk /bin/bash 


# docker run --name adminer -p 8081:8081 --link postgres:postgres adminer


# docker run --name mongodb -p 27017:27017 -e MONGO_INITDB_ROOT_USERNAME=admin -e MONGO_INITDB_ROOT_PASSWORD=admin mongo:4


# docker run --name mongoclient -p 3001:3001 --link mongodb:mongodb mongoclient/mongoclient

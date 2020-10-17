# How-to 

## Requirement
- Docker
- Docker Compose

## Run

docker-compose up -d


## Verify

docker-compose ps 

             Name                            Command               State           Ports         
-------------------------------------------------------------------------------------------------
ghostio_database_1_366efade43d5   docker-entrypoint.sh mysqld      Up      3306/tcp, 33060/tcp   
ghostio_ghost_1_897f28840e52      docker-entrypoint.sh node  ...   Up      0.0.0.0:8080->2368/tcp


## Testing

-- Access url http://localhost:8080
-- Access admin http://localhost:8080/ghost

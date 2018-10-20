#User management service
##Docker build locally
docker build .

##Database
docker run -d --name pg-photos -e POSTGRES_USER=dbuser -e POSTGRES_PASSWORD=postgres -e POSTGRES_DB=photo -p 5433:5432 postgres:10.5

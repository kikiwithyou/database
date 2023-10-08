# databases
this repository contains the database tech that will be used in Cantek data analytics course
# getting started

## pre-req
- docker installed
- docker desktop installed
- docker compose installed
- git installed

## initial start
```sh
# 1. clone the repo
git clone https://github.com/kikiwithyou/database.git

# 2. cd to the cloned repo
cd database

# 3. start docker
## click open the docker desktop application

# 4. start the database
docker compose up -d
``` 

## subsequent start
```sh
# just start the docker desktop, all things will be started automatcally 
```

## turning off
```sh
docker compose down
```
## remarks
- data will be persist in the docker volume, as long as volume didn't touch, data is persisted

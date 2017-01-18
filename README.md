# Elasticsearch & Kibana

## Requirement
 - Docker : http://docs.docker.com/installation/
 
 - Docker-compose : https://github.com/docker/compose/releases

This repositories contains 2 containers (Elasticsearch & Kibana).
In ELK stack Elasticsearch use as search-engine to query logs and search logs, and Kibana
will be the Dashboard to view the logs.

## Here's the step to build the docker container :
 1. Clone the repository, run `git clone https://github.com/landrain/elkdocker.git`
 2. Change to elkdocker directory, run `cd elkdocker`
 3. Build & up the container `docker-compose build && docker-compose up -d
 4. You can access Kibana dashboard on http://localhost:5601

## What this repo will help you to do?
This repo has services to facilitate development of streaming spark applications. Also contains Kafka and zookeeper to stream data into Kafka
## Motive behind creating this repo?
Main motive is to make the **local development** easy without worrying about setting up the services
## How to run this application?
Pre-requisite: Docker Desktop (https://docs.docker.com/get-started/)
Commands: 
1. `sh build-images.sh`
2. `docker-compose up`

## How to scale spark worker nodes?
`docker-compose up --scale spark-worker=2`

## Future scope
Adding services like `kafka-connect` and `schema-registry` along with `k-sql` 

### Versions used: 
- Zookeeper: `3.4.9`
- Kafka: `cp-kafka:5.3.0`
- Spark: `2.4.4`

*This application is tested on Macbook pro, should work for other envs as far as docker is installed*

## Contributing 
Please feel free to report problems, bugs, helping with documentation, or contributing code changes. Thank you 
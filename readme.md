# Directions

This will generate an environment with:

- Dremio on localhost:9047
- Flink on localhost:8081
- Minio on localhost:9001 (storage:9000 for s3 endpoints)
- Jupyter Notebook w/ Spark on localhost:8080

Must have Docker & Docker-Compose installed (both should come with docker desktop).

- Navigate terminal to the same directory as the docker-compose.yml
- run `docker-compose up`

There are three folders in this repo mapped specifically to the spark/notebook container which are:

- `datasets` use this for any sample datasets
- `notebooks` for storing notebooks
- `warehouse` to be used as a warehouse for written data

[Find Guides and Tutorials Here](https://github.com/developer-advocacy-dremio/quick-guides-from-dremio)
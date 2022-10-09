## Go CDC
PostgreSQL, Debezium, Kafka, and Go

### Run App
```sh
    git clone git@github.com:geekbim/Go-CDC.git
    cd Go-CDC
    docker-compose up -d
    [POST]  http://localhost:8083/connectors --> payload: connector.json
    go run cmd/consumer/main.go
```
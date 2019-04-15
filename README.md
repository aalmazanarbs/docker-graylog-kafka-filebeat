# Graylog with Kafka and Filebeat

To see logs add Raw/Plaintext Kafka input with ZooKeeper address [zookeeper2181/](zookeeper2181/) and Topic filter regex ^logs$

## Build and start environment

```shell
docker-compose up -d
```

## Stop environment

```shell
docker-compose down
```

## Graylog access

[http://localhost:9000/](http://localhost:9000/)
```
username: admin
password: admin
```
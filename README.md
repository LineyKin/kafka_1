Первое знакомство с kafka

producer и worker - два примитивных микросервиса, которые общаются через брокер сообщений.

Kafka запускается в docker-контейнере:

docker pull apache/kafka:3.7.0
docker run -p 9092:9092 apache/kafka:3.7.0


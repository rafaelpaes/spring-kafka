# spring-kafka

# Creating a topic from beginning
kafka-topics.sh --create --zookeeper zookeeper:2181 --replication-factor 1 --partitions 1 --topic NewTopic
kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic NewTopic --from-beginning

# Consuming

kafka-console-producer.sh --broker-list localhost:9092 --topic NewTopic

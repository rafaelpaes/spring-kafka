# spring-kafka

# Creating a topic from beginning
kafka-topics.sh --create --zookeeper zookeeper:2181 --replication-factor 1 --partitions 1 --topic NewTopic --from-beginning

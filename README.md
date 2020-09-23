# Kafka-tools-installation

- I have already installed Java and maven.

## Kafka Installation
   - Download kafka and un tar it.
   - set up the environment variabkes.
   - KAFKA_HOME = C:\kafka-version folder
   - %KAFKA_HOME%\bin
   - %KAFKA_HOME%\bin\windows
   
## Commands
  - Command to Run Zookeeper Service - (.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties)
  - Command to Run Kafka Service - (.\bin\windows\kafka-server-start.bat .\config\server.properties)
  - Execute One-Time Commands - (.\bin\windows\kafka-topics.bat --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --create --topic programming-languages)
    (.\bin\windows\kafka-topics.bat --zookeeper localhost:2181 --list)
  - Run Kafka Producer - (.\bin\windows\kafka-console-producer.bat --broker-list localhost:9092 --topic programming-languages)
  - Run Kafka Consumer - (.\bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic bearcat-messages --from-beginning)

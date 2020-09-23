# kafka-software-installation
The software is provided by Apache organisation. use the following link to download: https://www.apache.org/dyn/closer.cgi?path=/kafka/2.6.0/kafka_2.13-2.6.0.tgz

## Kafka and its services
* Kafka is an open source stream-processing software platform build using Java and Scala technologies. 
* Zookeeper is a distributed coordination service.
* To  start the zookeeper service, open powershell as Administrator in the kafka folder and run the following command
.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties
* Open another powershell as Administrator window and run the kafka service in
.\bin\windows\kafka-server-start.bat .\config\server.properties
* My choice of topic was "college-admissions".
* To start a kafka producer,
.\bin\windows\kafka-console-producer.bat --broker-list localhost:9092 --topic college-admissions

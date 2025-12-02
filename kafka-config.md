1. Download Kafka

Download the latest Kafka binary package (comes bundled with Apache ZooKeeper):
Go to Kafka download page
Choose a Scala version & binary release (e.g. kafka_2.13-3.7.0)
Extract it:

**tar -xzf kafka_2.13-3.7.0.tgz
cd kafka_2.13-3.7.0**

2. Start ZooKeeper
bin/zookeeper-server-start.sh config/zookeeper.properties

3. Start Kafka Server

Open a new terminal tab:

bin/kafka-server-start.sh config/server.properties

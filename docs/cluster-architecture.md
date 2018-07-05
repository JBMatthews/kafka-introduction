## Cluster Architecture

### In this Lab

**Objective:** Learn more about this particular techonology.

**Successful Outcome:** Simply following along with the step written below and complete each before moving to the next.

**Lab Files:** `xx`

----

### Steps

Take a look at the following illustration. It shows the cluster diagram of Kafka.

![image008](https://user-images.githubusercontent.com/558905/40723999-06cdda10-63ee-11e8-8550-8ed6ce83bcb5.jpg)

The following table describes each of the components shown in the above diagram.

| Components | Description |
| --- | --- |
| Broker	| Kafka cluster typically consists of multiple brokers to maintain load balance. Kafka brokers are stateless, so they use ZooKeeper for maintaining their cluster state. One Kafka broker instance can handle hundreds of thousands of reads and writes per second and each bro- ker can handle TB of messages without performance impact. Kafka broker leader election can be done by ZooKeeper.|
| ZooKeeper	| ZooKeeper is used for managing and coordinating Kafka broker. ZooKeeper service is mainly used to notify producer and consumer about the presence of any new broker in the Kafka system or failure of the broker in the Kafka system. As per the notification received by the Zookeeper regarding presence or failure of the broker then pro- ducer and consumer takes decision and starts coordinating their task with some other broker.|
| Producers	| Producers push data to brokers. When the new broker is started, all the producers search it and automatically sends a message to that new broker. Kafka producer doesn’t wait for acknowledgements from the broker and sends messages as fast as the broker can handle.|
| Consumers	| Since Kafka brokers are stateless, which means that the consumer has to maintain how many messages have been consumed by using partition offset. If the consumer acknowledges a particular message offset, it implies that the consumer has consumed all prior messages. The consumer issues an asynchronous pull request to the broker to have a buffer of bytes ready to consume. The consumers can rewind or skip to any point in a partition simply by supplying an offset value. Consumer offset value is notified by ZooKeeper.|


### Results

You are finished! Great job!
## Kafka Tools

### In this Lab

**Objective:** Learn more about this particular techonology.

**Successful Outcome:** Simply following along with the step written below and complete each before moving to the next.

**Lab Files:** `xx`

----

### Steps

Kafka Tool packaged under "org.apache.kafka.tools.\*. Tools are categorized into system tools and replication tools.

System Tools
------------

System tools can be run from the command line using the run class script. The syntax is as follows:
```
bin/kafka-run-class.sh  package.class - - options
```

Some of the system tools are mentioned below:

-   **Kafka Migration Tool** -- This tool is used to migrate a broker from one version to an- other.

-   **Mirror Maker** -- This tool is used to provide mirroring of one Kafka cluster to another.

-   **Consumer Offset Checker** -- This tool displays Consumer Group, Topic, Partitions, Off- set, logSize, Owner for the specified set of Topics and Consumer Group.

Replication Tool
----------------

Kafka replication is a high level design tool. The purpose of adding replication tool is for stronger durability and higher availability. Some of the replication tools are mentioned below:

-   **Create Topic Tool** -- This creates a topic with a default number of partitions, replication factor and uses Kafka\'s default scheme to do replica assignment.

-   **List Topic Tool** -- This tool lists the information for a given list of topics. If no topics are provided in the command line, the tool queries Zookeeper to get all the topics and lists the information for them. The fields that the tool displays are topic name, partition, leader, replicas, isr.

-   **Add Partition Tool** -- Creation of a topic, the number of partitions for topic has to be specified. Later on, more partitions may be needed for the topic, when the volume of the topic will increase. This tool helps to add more partitions for a specific topic and also allows manual replica assignment of the added partitions.


### Results

You are finished! Great job!
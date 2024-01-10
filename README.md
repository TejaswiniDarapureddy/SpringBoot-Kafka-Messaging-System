# SpringBoot-Kafka-Messaging-System
Spring Boot application that uses Kafka as the messaging platform where Apache Kafka is a Producer-Consumer System. This messaging environment is basically used for the data exchange/transfer among the systems. 

**Functionality Overview**
The application comprises mainly two controller classes:

**Message Sending Controller:**

Allows sending string format messages to the producer.
The producer places the message in a specific topic, which is then consumed by the consumer.
Testing can be done using a browser, e.g., http://localhost:8080/api/v1/kafka/send?HelloWorld

**Object Posting Controller**:

Permits posting a Java object (user object).
The producer serializes the Java object into a JSON byte array and sends it to a topic.
The consumer deserializes the JSON byte array back into a Java object for consumption.
This functionality is tested using POSTMAN.

**Configuration**
All essential properties are configured in the application.properties file.

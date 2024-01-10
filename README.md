# SpringBoot-Kafka-Messaging-System
Spring Boot application that uses Kafka as the messaging platform where Apache Kafka is a Producer-Consumer System. This is a Basic Springboot application where we created two Controller classes where 
--> one is for sending the string format messages to the producer which inturn puts the message in the topic and that message is being consumed by the consumer. (Can be tested using browser, for example, "**http://localhost:8080/api/v1/kafka/send?HelloWorld**" )
--> Second one is for posting the Java object(user object) which is serialized by the producer into JSON byte array and pushed the data to the topic and then this JSON byte array deserialized into Java object and consumed by the consumer. This is tested through POSTMAN.

All the necessary properties are given in the application.properties file

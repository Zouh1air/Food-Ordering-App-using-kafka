# Food-Ordering-App-using-kafka
 Highly Scalable Event-Driven Backend System for Food Ordering App

 
🔍 Key Features:

Event-Driven Architecture: Every significant action in the food ordering process is treated as an event, from order placement to confirmation.
Apache Kafka Integration: Apache Kafka serves as the central bus for all data movement, facilitating real-time data processing for various subsystems.
kafka-python Library: The project utilizes the kafka-python library for connecting a locally running Kafka broker to Python code.
Scalability: The system is highly scalable, allowing individual components to be scaled up or down as needed, whether they are microservices, stream processing jobs, or Python scripts.
Extensibility: Thanks to the nature of Apache Kafka, the system is easily extensible. New components can process historical data by replaying messages from the beginning.
Data Reliability: Data retention in Kafka ensures no data loss in case of issues with downstream or upstream systems.

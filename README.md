# SpringData_Batch_Elasticsearch_Kibana
Import Relational Database Data to Elasticsearch (v6.2.2) with Spring Batch using Spring data and analyze the index with Kibana (v6.2.2).
![untitled](https://user-images.githubusercontent.com/42076893/44291929-f9c94c00-a281-11e8-9d23-3acaee5a18a9.png)

## Project description

Recently my internship manager ask me to transfer a large amount of data from a relational database to the NoSQL database that is
Elasticsearch in order to take advantage of its famous fast searching capabilities ( Kibana v6.2.2). 

Elasticsearch is part of the ELK stack that is released and maintained by Elastic.co The abbreviation ELK stand for
Elasticsearch, Logstash, and Kibana.

I decided to start the development from scratch. That way I can take advantage of the new Spring Boot and Spring Data features.
Since Spring Data supports MongoDB out of the box, it should be easy to adapt these concepts for other NoSQL databases, like Elasticsearch.
Depending on the specific data store, some optimizations may be possible only for Elasticsearch or the other way around.

My project describes how to create an importing daemon to Elasticsearch from an existing data source, starting with a simple table of a
relational database (Customer table), and then improving the import for complex records from a relational database. 
The steps will be:

### Prerequisites
1.  Import Relational Database Data with Spring Batch
2.  Components and usage of Spring Data Elasticsearch
3.  Import the index from elastic search to kibana to visualize some average and statistics (eg: Top10FNameBirth .. )

### Environment settings 

1.  Download and install MySQL database ( I used wamp server ) 
2.  Eclipse Oxygene as an  IDE 
3.  Install Java 8 and set environment variable and JAVA_HOME (Your JAVA_HOME should point to the ...\Java\jdk1.8.. directory / In Your path you should have %JAVA_HOME%\bin.) 
4. running Elasticsearch instance (version 6.2.2)
5.  running Kibana instance (version 6.2.2)

### GIF DEMO 
file:///C:/Users/asus/Downloads/ezgif.com-crop.gif

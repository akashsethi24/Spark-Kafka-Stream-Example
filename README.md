# Spark-Kafka-Stream-Example
This repo contains the Example of Spark Streaming using Apache Kafka.

We are Feeding Object in the form of Json to Apache Kafka and Fetching the same via Spark Streaming and printing the result.

#Flow :-<br />
        Tweet("SampleUser", "SampleTweet") -> JsonAsString -> Apache Kafka [Producer] <br />
        Apache Kafka [Consumer] -> Spark Streaming -> JsonAsString -> Tweet("SampleUser", "SampleTweet") -> Show. <br />
        
We Are Using :- <br />
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Spark Version :- `2.0.0` <br />
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Scala Version :- `2.11.8` <br />
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Spark Streaming Version :- `2.0.0` <br />
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Lift Json Version :- `2.6.2`  <br />

Soemthing's wrong then raise an issue. <br>
Happy Coding.

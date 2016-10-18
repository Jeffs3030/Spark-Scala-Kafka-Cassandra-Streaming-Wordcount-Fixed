# Spark-Scala-Kafka-Cassandra-Streaming-Wordcount-Fixed
I don't like the existing wordcount example that is used in Scala for Spark Streaming, so I created a more useful version

Foreward to code



I am not a big fan of the wordcount example because it does not take into consideration

that multiple columns need to be saved into Cassandra 

This example shows how to use Kafka and how to save into Cassandra using Spark with multiple columns with dataframes



This code takes a csv formatted kafka stream that is created from a sql source query, 

the kafka stream values look something like this

,word1a,word2b,word3b,word4b,word5b,word6d,

,word1b,word2c,word3c,word4b,word5c,word6e,



Then we save the Kafka stream into Cassandra as multiple columns

if you have any questions feel free to ask us at jeffs@jsbusinessintelligence.com

End foreward to code

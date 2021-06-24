# Kafka Streams

## What is Kafka Streams?
It’s an API for building real-time stream processing applications.
Before Kafka streams, kafka didn’t have an API for developing this kind of applications, so developers who did stream processing had to rely on third party APIs like Apache Spark or Apache Flink.
That’s why the developers of Apache Kafka created Kafka Streams

## Guides and Tutorials
### Video Tutorial
You can follow me on YouTube for more Software Engineering Content in my channel [Programming with Mati](https://www.youtube.com/channel/UC0clXTEN6Fu277RTw6jCfAg).
<iframe align="center" width="560" height="315" src="https://www.youtube.com/embed/MR5hllNC9hk" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

* [WordCountApp](word-count-app/README.md): Kafka Streams' Hello Word App!
* Stateless Processing with the [Voice Command Parser](voice-command-parser/README.md)


## Features
* **High level Domain Specific Language (DSL)** fluent, functional API, very easy to use
* **Low level Processor API** for very special use cases or more control
* **Convenient Abstractions** like Streams, Tables, Windows, Branches. Leverages on existing Kafka Abstractions like Consumer Groups
* **Easy Installation** It’s just a library that can be imported in any Java Application

## Operational Characteristics
* **Scalable**: Works on a single partition and can scale up to the number of partitions in the Kafka Topic
* **Reliable**: When an instance goes down, the load gets redistributed among active instances, preventing data loss and providing zero downtime
* **Maintainable**: Easy to use API, very intuitive and doesn’t require much ramp-up

## Use Cases
It’s used in all kinds of use cases where streams have to be processed in real-time, in huge amounts of data
* Finance and trading
* Inventory tracking
* Internet of Things
* Machine Learning pipelines
* Videogames telemetry
* Event booking


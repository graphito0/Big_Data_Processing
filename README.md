### Big_Data_Processing
***Apache Kafka,  Apache Spark Streaming and MongoDB form a perfect trio for streaming to storing and analysing big data***.

### General Overview
   - Here is a simple project that will run through the basics of all three, as well as form a architectural link!
   - ***Operating system - Linux, Ubuntu (64 bit)***

**StopFire is a campaign started by Monash University to predict and stop the fire in Victorian cities**.
They have employed sensors in different cities of Victoria and have collected a large amount of data.
   - Our job is to;-
1. **Create Producers from Apache kafka that will send the data**.
2. **Stream the data using Apache Spark Streaming**.
3. **Store the data in MongoDB**.
4. **Create a visualiser for analysis**.

Below given flow daigram will increase your undestanding -
https://github.com/graphito0/Big_Data_Processing/issues/1#issue-467930540 .


### Installation

1. MongoDB - https://docs.mongodb.com/manual/administration/install-community/ for mongodb

   - In particular, we will use PyMongo that provides an interface to easily access MongoDB from Python
     sudo pip install pymongo for pymongo installation
 
2. Apache Kafka - The easiest way to install Kafka is to download binaries and run it. Since it’s based on JVM languages like Scala and Java, you must make sure that you are using Java 7 or greater.

   - https://kafka.apache.org/quickstart tutorial for setting up kafka
   
   - After setting up, there are multiple python libraries available to connect Apache Kafka and Python together.
     We are going to use an open-source community-based library known as Kafka-Python.

     You can install the library using the command below:

     !pip3 install kafka-python
     
3. Spark stream - Apache Spark community released a powerful Python package, pyspark. Using pyspark, we can initialise Spark, load streaming data, create RDD from the data, sort, filter and sample the data.
    - https://medium.com/@GalarnykMichael/install-spark-on-ubuntu-pyspark-231c45677de0 for installing pyspark Spark stream on Ubuntu


### Files

- The Specification file consists description of the project.
- The Tasks file consists of streaming, producing events and analysing tasks.
- The General Fixng files will help you to overcome problems occuring with kafka.

### References

1. https://docs.mongodb.com/manual/administration/install-community/
2. https://kafka.apache.org/quickstart
3. https://medium.com/@GalarnykMichael/install-spark-on-ubuntu-pyspark-231c45677de0




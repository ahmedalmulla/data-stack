
There are different architectures for lake house or data lake.

Here some of the modern data architecture:

Databrick with Microsfot Azure data lake house archeciture :

![image](https://user-images.githubusercontent.com/46624390/153370575-1b5f0fe2-b892-4c7c-a782-a2128772664d.png)

AWS reference data archeciture :

![image](https://user-images.githubusercontent.com/46624390/153370803-024205fb-174e-4ea7-b374-83a33f1c0660.png)

Zaloni data archeciture:

![image](https://user-images.githubusercontent.com/46624390/153370908-54808122-7298-4eb6-8dcf-ce7f7d5e0b20.png)




Some common storage options for data lake :
*	Hadoop: the preferred option for on-premise.
*	Object storage: different cloud provider deliver this option ( Amazon S3, Azure blob , google cloud storage). 
*	Apache Hive tables : An open source data warehouse system for querying and analyzing large datasets stored in Hadoop files.
*	HBase : An open source, nonrelational, distributed database that is modeled after Google’s BigTable

Some data processing options for data lake:
*	Batch processing:
*	Pig 
*	Hive: This is a mechanism to project structure onto large datasets and to query the data using a SQL-like language called HiveQL.
*	Spark: Apache Spark is an open source engine developed specifically for handling large-scale data processing and analytics. It provides a faster engine for large-scale data processing using in-memory computing. It can run on Hadoop, Mesos, in cloud, or in a standalone environment to create a unified compute layer across the enterprise.
*	MapReduce: MapReduce has been central to data lakes because it allows for distributed processing of large datasets across processing clusters for the enterprise.
•	Stream processing:
*	Spark-Streaming 
*	Kafka 
*	Flume 
*	Storm.

Some of the visualization tools:
*	Qlik :Allows you to create visualizations, dashboards, and apps that answer important business questions.
*	Tableau :Business intelligence software that allows users to connect to data, and create interactive and shareable dashboards for visualization.

Issues in data lake:
Data governance,  meta-data system is a must in order to make analyst can reach the data.


Data lakes zones (Very important even though could be garbage 😊):
*	Zone 1: The Transient Landing Zone: The transient zone is temporary; it is a landing zone for data where security measures can be applied before it is stored or accessed. We should check the quality and apply security needed



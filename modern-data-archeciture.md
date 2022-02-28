
## Introduction

There are different ways to build data stack which helps in data analytics and building data driven compoany. Traditionally, companies used to work on data warehouse where they mainly used ETL (Extract,Tranform and Load) to take the required data from
 data sources and then transform it in a way that fit their busienss needs and finally load it in the data warehouse which is a centrlize database which hosts all different company data which analytics can use to build required reports and dashboard.

New methods have been developed with big data era where huge amount of data get genereted from different new sources like soical media , IoT sensors and other crowdsourcing platform. A new concept gets introudced called ELT (Extract,Load and Transform)
 where organization capture data from sources in its raw form and store it locally in something called data lake. Then, they use some tools to transform required data based on bussiness requirement and store in the data warehouse which enabled BI analytics
 to build required reports and dashboard.

In addtion, Articial Intellegince has been evovled dramitacly which enabled data scientent to build a machine learning alogrithms over data lakes in order to come up with new data insights.

## Component of modern data stack

The main component of a modern data stack is the developing and building data lake because data lake enables companies to store different data types including structured , semi-structured and unstructured data. On other hand, datawarehouse focus on schema
 on write and can only accept structured data. 

Majority of modern data stack utilize cloud provider services in order to build an efficent and powerful data stack. with help of cloud, organization can use very high computation for specfic time where they need perform required analysis.


## Popular modern data stack

There are different architectures for lake house or data lake.

Here some of the modern data architecture:

Databrick with Microsfot Azure data lake house archeciture :

![image](https://user-images.githubusercontent.com/46624390/153370575-1b5f0fe2-b892-4c7c-a782-a2128772664d.png)

AWS reference data archeciture :

![image](https://user-images.githubusercontent.com/46624390/153370803-024205fb-174e-4ea7-b374-83a33f1c0660.png)

Zaloni data archeciture:

![image](https://user-images.githubusercontent.com/46624390/153370908-54808122-7298-4eb6-8dcf-ce7f7d5e0b20.png)

general lakehouse:

![lakehouse_general](https://user-images.githubusercontent.com/46624390/154840355-1046d595-553d-41a9-b7ab-4b1b27203676.png)


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
*	Zone 1: The Transient Landing Zone: The transient zone is temporary; it is a landing zone for data where security measures can be applied before it is stored or accessed. We should check the quality and apply security needed.
*	Zone 2: The Raw Zone: data is stored permanently and in its original form. Add it to catalogs and ehnance the meta data.
*	Zone 3: The Trusted Zone:data is altered so that it is in compliance with all policies as well as checked for quality. Organizations perform standard data cleansing and data validation methods here.
*	Zone 4: The Refined Zone:common format for ease of use, and goes through possible detokenization, further quality checks, and life cycle management.Data is often transformed to reflect the needs of specific lines of business in this zone.
* Sandbox:allows data scientists and managers to create ad hoc exploratory use cases without the need to involve the IT department or dedicate funds to creating suitable environments within which to test the data.


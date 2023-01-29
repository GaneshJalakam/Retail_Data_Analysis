
# Retail Data Analysis - Real Time Processing

## Problem Statement
The online market has grown tremendously in the past few years. Digitally enabled customers like to shop on the run, and that is the reason why online shopping is one of the most popular online activities worldwide. In 2019, global e-commerce sales amounted to 3.53 trillion USD and are projected to grow to 6.54 trillion USD in 2022.

 

The analytical capabilities of big data have had a positive impact across industries, including e-commerce. Big data tools improve business performance by enabling companies to analyse trends and current consumer behavioural patterns and offer better and more customised products.

 

For the purposes of this project, you have been tasked with computing various Key Performance Indicators (KPIs) for an e-commerce company, RetailCorp Inc. You have been provided real-time sales data of the company across the globe. The data contains information related to the invoices of orders placed by customers all around the world. You will get to know the details of the data in the next segment.

 

At the industry level, an end-to-end data pipeline is built for this purpose. Tools such as HDFS(Hadoop Distributed File System) are used to store the data that is processed by the real-time processing framework and then shown on a dashboard with tools such as Tableau and PowerBI. The image given below is an example of such a complete data pipeline.

![image](https://images.upgrad.com/27070182-3791-4fc7-81c6-0d39c97b4f25-Upgrad%20RT%20STreaming-whole.png)

For our project, we will be focusing on the ‘Order Intelligence’ part of this data pipeline. The image given below shows the architecture of the data pipeline that we will follow in this project.

![image](https://images.upgrad.com/137bcb53-7fa1-4aab-a93a-6f5b369efd4b-Upgrad%20RT%20STreaming%20-%20internal.png)

Broadly, you will perform the following tasks in this project:

Reading the sales data from the Kafka server

Preprocessing the data to calculate additional derived columns such as total_cost etc

Calculating the time-based KPIs and time and country-based KPIs

Storing the KPIs (both time-based and time- and country-based) for a 10-minute interval into separate JSON files for further analysis.

## Technology Stack
- Apache Spark (PySpark - Spark Streaming)
- Apache Kafka
- AWS cloud - EMR (Apache Spark and Zookeeper applications installed on it)

## Code Implementation and Documentations
**Refer Python file with PySpark code (Spark streaming code) and its related document present in this repository.**

## Contributors
- [Ganesh Jalakam](https://github.com/GaneshJalakam)

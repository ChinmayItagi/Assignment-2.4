Hadoop in Layman’s Term
Under the umbrella of Hadoop the structure is divide into two parts  1) HDFS(Storage)  2) MapReduce (Data Processing) 
HDFS refers to the Hadoop Distributed File System which is responsible for the storage of the data which is specifically designed such as to handle large amount of data. Also to access large amount data in minimal amount of time. One think to clear here is that the real time data access is not possible with help of the HDFS as it is designed for getting large amount faster and not made to handle request in the real time. HDFS has one master Daemon called as NAME NODE and many slave Daemons called as the DATA NODE.
MapReduce refers to the processing part of the data Hadoop 2.x uses YARN (Yet Another Resource Negotiator) which separates the resource management and scheduling capabilities. The MapReduce algorithm contains two important tasks, namely Map and Reduce. Map takes a set of data and converts it into another set of data, where individual elements are broken down into tuples (key/value pairs) Secondly, reduce task, which takes the output from a map as an input and combines those data tuples into a smaller set of tuples. The best part of the Map reduce is that it is scalable.
Pig and Hive – Pig and Hive are key components of the Hadoop and both of them are having similar goals that is – “They are tools that ease the complexity of writing complex java MapReduce programs”. But the are used according to form of the output needed 
PIG Latin – 
1)	Procedural Data Flow Language .
2)	For Programming
3)	Mainly used by Researchers and Programmers
4)	Operates on the client side of a cluster.
5)	Does not have a dedicated metadata database.
6)	Pig is SQL like but varies to a great extent.
HIVEQL
1)	Declarative SQLish Language
2)	For creating reports.
3)	Mainly used by Data Analysts
4)	Operates on the server side of a cluster.
5)	Makes use of exact variation of dedicated SQL DDL language by defining tables beforehand.
6)	Directly leverages SQL and is easy to learn for database experts.

Hadoop Framework
Hadoop works two basic concept of Storing the data using HDFS and processing  the data using the Map Reduce algorithms.
HDFS(Hadoop Distributed File System)
Is file system specially designed for large data handling and is developed using the white paper published by google. The hadoop uses master node(Name Node) and many slave nodes(Data Node) to accomplish the storing the humongous data and also make the retrieval time of the data also small so that processing  of the data can be fast. Also the HDFS takes care of the reliability of the data by replicating its basic unit block of 128Mb.
MapReduce 
It is the technique by which the huge data is being processed and try to extract some usefull information. It uses two procedures that is MAP and REDUCE. The Map Reduce also has master and the slave Daemon. Resource Manager is the master daemon and node manager is slave daemon.

Explain the reasons to learn Big data technologies?
Past decade the data generated through all the electronic devices was not carefully monitored and hence was not of much importance. As the users increased the data that was being generated fast and huge. And companies realized that this data if studied carefully can be used for betterment of the business .Hence in present times the data has become new asset and most valuable resource for the companies. Big Data one of the few technologies which help in storing and processing such unstructured data and get some meaningful information from it.
Also point to add is that the data generated is very high amount i.e in peta and zeta bytes and storing it only in one physical space is difficult and also reliability is compromised so distributed storing is also provided by Big Data technology. It is being said that by 2020 every single man on earth will be digital so it is  important to note data will be the new gold.

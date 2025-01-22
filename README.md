# Getting Started with kafka

### Reference Documentation
For further reference, please consider the following sections:

* [kafka documentation](https://kafka.apache.org/quickstart)

#### Download kafka

* [click here](https://kafka.apache.org/downloads) to download kafka server from apache 

#### steps to start kafka server
1. Extract the kafka zip file to specific folder like in D:/kafka
2. Then open a CMD in location D:/kafka/bin
3. Move to specific directory if you use window then move to windows directory or use bin directory
4. execute below command to start **zookiper**

    D:/kafka/bin/windows
    ````
    zookeeper-server-start.bat ..\..\config\zookeeper.properties
    ````
5. open another CMD and execute below command to start kafka server 

    D:/kafka/bin/windows
    ````
   kafka-server-start.bat ..\..\config\server.properties
    ````
   
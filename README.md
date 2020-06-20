# KV_Store

This is an implementation of a Distributed Key Value Store developed on Python. It is fault tolerant and highly available. It makes use of Key based load division for load balancing and distributed data replication for fault tolerance. Zookeeper is used for leader election and lifeline monitoring for high availibilty. 

A setup of Python3 with HTTP and Requests module is needed along with Zookeeper and Kazoos.

To run: 

First start the servers
```
python3 serv_init.py
```
Then start the clients and provide Queries:
```
python3 client.py
```

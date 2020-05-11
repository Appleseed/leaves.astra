# Leaves.Astra 

Leaves on DataStax Astra™ with NoSQL, and Apache Cassandra™ in the cloud!

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/xingh/leaves.astra.git)

## Getting started

---- 

```sh
git clone https://github.com/xingh/leaves.astra.git
cd leaves.astra/
```

## Authorization
**IMPORTANT**

1. 
* On Astra, download your secure connect bundle:

![SecConImg](Assets/Images/DownloadSecureCon.png)

* Add the `secure-connect-CLUSTER_NAME.zip` to **leaves.astra/astra.credentials/**

2. 
* Modify each field value in **leaves.astra/astra.credentials/UserCred.json** 

<img src="Assets/Images/UserCred.png" width="500" height="300">

<br />

## RUN DATA MIGRATOR
- - - 

[README](https://github.com/Anant/cassandra.api/blob/master/astra.import/README.md)

### APIs
---

[Building REST API Blog Post](https://blog.anant.us/building-a-rest-api-with-cassandra-on-datastax-astra-using-python-and-node/)

[Building REST API Webinar Recording](https://www.youtube.com/watch?v=O64pJa3eLqs)

#### NODE.JS

[README](https://github.com/Anant/cassandra.api/blob/master/astra.api/leaves.api.node/README.md)

#### PYTHON

[README](https://github.com/Anant/cassandra.api/blob/master/astra.api/leaves.api.python/README.md)

### TESTING
--- 

[README](https://github.com/xingh/leaves.astra/blob/master/astra.api/leaves.api.tests/README.md)

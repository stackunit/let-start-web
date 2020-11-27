#  mongodb
<img src="start-mondobd.png" width="100%" alt="codewithpunit">
<hr>
C:\Program Files\MongoDB\Server\4.0\bin
<hr>
C:\Program Files\MongoDB\Server\4.0\bin>mongod
<pre>
Microsoft Windows [Version 10.0.18363.1237]
(c) 2019 Microsoft Corporation. All rights reserved.

C:\Program Files\MongoDB\Server\4.0\bin>mongo --version
MongoDB shell version v4.0.2
git version: fc1573ba18aee42f97a3bb13b67af7d837826b47
allocator: tcmalloc
modules: none
build environment:
    distmod: 2008plus-ssl
    distarch: x86_64
    target_arch: x86_64

C:\Program Files\MongoDB\Server\4.0\bin>mongo
MongoDB shell version v4.0.2
connecting to: mongodb://127.0.0.1:27017
MongoDB server version: 4.0.2
Server has startup warnings:
2020-11-27T16:42:16.996+0530 I CONTROL  [initandlisten]
2020-11-27T16:42:16.996+0530 I CONTROL  [initandlisten] ** WARNING: Access control is not enabled for the database.
2020-11-27T16:42:16.996+0530 I CONTROL  [initandlisten] **          Read and write access to data and configuration is unrestricted.
2020-11-27T16:42:16.996+0530 I CONTROL  [initandlisten]
---
Enable MongoDB's free cloud-based monitoring service, which will then receive and display
metrics about your deployment (disk utilization, CPU, operation statistics, etc).

The monitoring data will be available on a MongoDB website with a unique URL accessible to you
and anyone you share the URL with. MongoDB may use this information to make product
improvements and to suggest MongoDB products and deployment options to you.

To enable free monitoring, run the following command: db.enableFreeMonitoring()
To permanently disable this reminder, run the following command: db.disableFreeMonitoring()
---

> show dbs
admin   0.000GB
config  0.000GB
local   0.000GB
> use punit
switched to db punit
> show dbs
admin   0.000GB
config  0.000GB
local   0.000GB
> db.createCollection("biodata")
{ "ok" : 1 }
> show dbs
admin   0.000GB
config  0.000GB
local   0.000GB
punit   0.000GB
> db
punit
> use ducat
switched to db ducat
> db
ducat
</pre>

# Enrollment-Form-Using-JSONPowerDB
Title of the Project:
Enrollment Form Using JSONPowerDB

Description:
This is a micro-project as Enrollment form for students who will provide their personal details to get enrolled in School. Also, data is managed and stored using JSON PowerDB. JsonPowerDB is a Database Server with Developer friendly REST API services. It's a High Performance, Light Weight, Ajax Enabled, Serverless, Simple to Use, Real-time Database. Easy and fast to develop database applications without using any server side programming / scripting or without installing any kind of database.
Whether it's a Dynamic Website or a Mobile App or some Data Analytics Portal, the development is real fun and fast. Nothing better than trying it yourself. What all you need is a basic understanding of HTML, CSS, Bootstrap, and Javascript.
Note: Using JsonPowerDB is equally Easy and Fast when used with Server Side programming like Java, .NET, Python or PHP etc.

Benefits of using JsonPowerDB:
JsonPowerDB (JPDB) is Next Generation, Creative and Disruptive Multi-mode DBMS_ with many USPs.
Proprietary algorithm for High Performance CRUD operations. Multiple times faster than popular DBMS.
Serverless support for faster development - A UI developer can develop complete dynamic application.
DBMS with built in web / application server and embedded caching makes the performance lightning fast.
Server side Native NoSQL - best query performance.
In-built support to query on multiple JPDB databases.
Multi-mode DBMS - Document DB, Key-Value DB, RDBMS support.
Schema free - easy to develop and maintain.
Web-services API - Can be used with any programming language that has support for HTTP.
Enriched by a pluggable API Framework - A developer can develop a pluggable API and plugin into any of our cloud JPDB instance.
Standardisation of API development framework makes the development process easy, more readable, and less error prone.
Multiple security layers.
Nimble, Simple to use, In Memory, Real-time DBMS.

Release History (release of your JsonPowerDB related code on Github):
0.3.2 / 2022-08-29
==================
* Completed Phase-4 of Pluggable API framework for configuration properties that controls the usage of API for global and individual users.
* Added NEW pluggable API for importing data from CSV files.
* Modified existing Drive API to support the Phase-4 of Pluggable API release.
* Development for Phase-1 for Replication of user's database - Replica Manager Dashboard, Sync user database from MasterNode to ReplicaNode(s) completed. 
* Added: New methods in jpdb-commons.js (0.0.4 and 0.0.5) for creating the 
  COPY COLUMN request i.e. createCopyColumnRequest(token, jsonObj, dbName, relName), 
  RENAME COLUMN request i.e. createRenameColumnRequest(token, jsonObj, dbName, relName), 
  REMOVE COLUMN request i.e. createRemoveColumnRequest(token, jsonObj, dbName, relName), 
  CHANGE COLUMN request i.e. createChangeColumnTypeRequest(token, jsonObj, dbName, relName), 
  UPDATE RECORD request i.e. createUPDATERecordRequest2(token, jsonObj, dbName, relName).
* Improved: Documentation
* Improved: SMTP Implementation for sending Emails 
* Fixed: Various Important bugs fixed

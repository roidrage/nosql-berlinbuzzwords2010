!SLIDE

## We'll get there in a minute. ##

!SLIDE

# Classification #

!SLIDE

## One NoSQL isn't like the other ##

!SLIDE bullets incremental

# The Contestants #

* Key-Value Stores
* Document Databases
* Column Stores
* Graph Databases

!SLIDE bullets incremental

# Key-Value Stores #

* Lookup of data by key
* That's it
* No querying of data

!SLIDE bullets incremental

# BerkeleyDB #

* Built in 1991
* Embedded database engine
* Data stored as serialized array
* Can handle up to 256 TB
* Still actively used

!SLIDE bullets

<br/>
# Key-Value Today #

* Project Voldemort
* Tokyo/Kyoto Cabinet
* Redis
* Amazon S3
* Scalaris

!SLIDE

## Fun fact: ##
### Project Voldemort can use BerkeleyDB as storage backend ###

!SLIDE bullets incremental

# Document Databases #

* Rich documents (JSON-ish)
* Queries with JavaScript and Map/Reduce

!SLIDE bullets incremental

# Lotus Notes #

* Built in 1989
* Document-oriented
* Offline-Replication (Multi-Master)
* Unfortunately still in use

!SLIDE bullets

# Today #

* CouchDB
* Riak
* MongoDB
* XML Databases (gasp)

!SLIDE bullets

# CouchDB #

* What Lotus Notes should have been like
* JavaScript, HTTP
* Offline by default
* P2P-like Replication

!SLIDE bullets

# Riak #

* JSON, JavaScript, HTTP
* Dynamo's Ring Model

!SLIDE bullets incremental

# Column Databases #

* Similar data is stored together
* Lookup by key and attribute
* Can compress similar data

!SLIDE bullets

# Sybase IQ #

* Built in 1996
* Handles data of > 1 PB

!SLIDE bullets

# Today #

* Google's BigTable
* Cassandra
* HBase
* Hypertable

!SLIDE bullets incremental

# Cassandra #

* BigTable and Dynamo
* Sitting in a tree

!SLIDE bullets incremental

# Graph Databases #

* Tightly connected documents
* Easy traversal of relationships

!SLIDE bullets incremental

# Versant OODMBS #

* Built in 1988
* Transparent persistency for objects
* Could easily store and traverse millions of objects

!SLIDE bullets incremental

# Today #

* Core Data
* Neo4J
* RDF

!SLIDE

## The kind of overlap in some cases. ##

!SLIDE

## A document database can be a key-value store ##

!SLIDE

## A column store is similar to a key-value store ##

!SLIDE

## A graph database is a document database on steroids ##

!SLIDE

## Some document databases can handle graphs as well ##

!SLIDE

## How is today different from back then? ##

!SLIDE

## The simplicity isn't new. ##

!SLIDE

## Data is what's become important. ##

!SLIDE

## And simpler ways to scale out. ##

!SLIDE

## The tools evolve around particular data and structure needs. ##

!SLIDE

## Open web technologies are a perfect fit. ##

!SLIDE

## But not a must. ##

!SLIDE

## If someone tries to sell you a closed product. ##

!SLIDE

# Run! #

!SLIDE

# Why Dynamo? #

!SLIDE

## Key-value access is the simplest thing possible. ##

!SLIDE

## Simpler things are easier to scale up. ##

!SLIDE

## It doesn't matter where the key is ##

!SLIDE

## Only the ring needs to know ##

!SLIDE

## As long as you just need a key to access data ##

!SLIDE

## Scaling out is easy ##

!SLIDE

## ...in theory. ##

!SLIDE

## Column, key-value and document stores ##

!SLIDE

## All access data by key ##

!SLIDE

## They're partitioning-friendly ##

!SLIDE

## Therefore well-suited for hashing ##

!SLIDE

# Caveat Emptor #

!SLIDE

## It's not for everybody. ##

!SLIDE

## Even if some people like telling you that. ##

!SLIDE

## Simplicity comes with a price. ##

!SLIDE

## A price that depends on your use case. ##

!SLIDE

## Range queries can be hard. ##

!SLIDE

## Complex ad-hoc queries are almost impossible. ##

!SLIDE

## They just don't scale that well across N nodes. ##

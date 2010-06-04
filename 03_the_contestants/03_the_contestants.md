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

!SLIDE bullets incremental

# Document Databases #

* Rich documents (JSON)
* Querying data through Map/Reduce

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

* Cassandra

!SLIDE

# Column Databases #

## Columns of columns of columns of data ##

!SLIDE

## They kind of overlap in some cases. ##

!SLIDE

## A document database can be a key-value store ##

!SLIDE

## A column store is similar to a key-value store ##

!SLIDE

## A graph database is a document database on steroids ##

!SLIDE

## Some document databases can handle graphs as well ##

!SLIDE

# Why Dynamo? #

!SLIDE

## Key-value access is the simplest thing possible ##

!SLIDE

## Simpler things are easier to scale up ##

!SLIDE

## It doesn't matter where the key is ##

!SLIDE

## Only the ring needs to know ##

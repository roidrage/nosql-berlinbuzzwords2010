!SLIDE

# Scaling out #

!SLIDE bullets incremental

## An RDBMS model of scaling up: ##

!SLIDE center

## Master-Slave ##

![Master-Slave](master_slave.png)

!SLIDE center

## Sharding ##

![Sharding](sharding.png)

!SLIDE

## Approaches in NoSQL ##

!SLIDE center

## P2P ##

![Multi-Master](multi_master.png)

!SLIDE center

## The CouchDB replication model: ##
## Everyone talks to everyone ##

!SLIDE

# Amazon's Dynamo #

!SLIDE center

## The Ring ##

![Hash Ring](hash_ring.png)

!SLIDE bullets incremental

* Data is partitioned into slices
* Replicated across N nodes
* Writes go to at least W replicas
* Reads are successful from R replicas
* N, R, W represent the quorum

!SLIDE

## Every node knows where every key is in the cluster. ##

!SLIDE

# Quorum #

> The minimum number of votes given by replica nodes in a distributed system required to successfully complete a read or write operation.

!SLIDE center
<br/>
## Eventual Consistency ##

![Eventual Consistency](eventual.jpg)

!SLIDE

# Eventual Consistency #

> The storage system guarantees that if no new updates are made to the object, eventually all accesses will return the last updated value.

<p class="caption"><a href="http://www.allthingsdistributed.com/2008/12/eventually_consistent.html">Werner Vogels</a></p>

!SLIDE

# Why Dynamo? #

!SLIDE

## Key-value access = Simple ##

!SLIDE

## Simple is easier to scale up. ##

!SLIDE

## Column, key-value and document stores ##

!SLIDE

## ...access data by key ##

!SLIDE

## Partitioning-friendly ##

!SLIDE

## Well-suited for hash ring ##



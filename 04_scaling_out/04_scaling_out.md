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

!SLIDE center

## Data partitioned into slices ##
![Hash Ring Slices](hash_ring_slices.png)

!SLIDE center

## Replicated across N nodes ##
![Hash Ring Replicas](hash_ring_replicas.png)

!SLIDE center

## Every node knows every key ##
![Hash Ring Data flow](hash_ring_data_flow.png)

!SLIDE bullets incremental

## Ensuring data consistency ##

* Writes go to at least W replicas
* Reads are successful from R replicas
* N, R, W represent the quorum

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

## Column, key-value and document stores ##

!SLIDE

## ...access data by key ##

!SLIDE

## Key-value access = Partition-friendly ##

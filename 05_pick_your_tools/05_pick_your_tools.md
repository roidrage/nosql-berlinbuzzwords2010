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
!SLIDE

## So how do I choose the right tool? ##

!SLIDE

# It Depends™ #

!SLIDE

## There are many factors involved. ##

!SLIDE

## Data structure. ##

!SLIDE bullets incremental

## Simple data, easy to scale out: ##

* Key-value stores
* Column stores

!SLIDE bullets incremental

## Simple data trimmed for fast access: ##

* Redis
* MongoDB

!SLIDE bullets incremental

## Richer data models: ##

* Document databases
* Graph databases

!SLIDE

## Read vs. write access patterns. ##

!SLIDE bullets incremental

## Always access documents by key ##

* Key-value stores
* Document databases

!SLIDE bullets incremental

## Access objects by more complex queries: ##

* Document databases
* Map/Reduce
* Redis (with lots of reverse lookups)

!SLIDE bullets incremental

## Only access similar data, even in ranges: ##

* Column stores

!SLIDE bullets incremental

## Reporting-style ad-hoc queries required: ##

* That can be a problem
* MongoDB

!SLIDE bullets incremental

## Tightly connected object graphs: ##

* Graph database
* Object database
* Riak

!SLIDE

## Easy to scale out: ##

* Riak
* Cassandra
* Project Voldemort
* etc.

!SLIDE

## In one way or the other ##
## they're all easy to scale out. ##

!SLIDE


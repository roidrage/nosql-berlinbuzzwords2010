!SLIDE

# Ancient History #

!SLIDE bullets incremental

## We've seen some of this before. ##

* Sort of

!SLIDE

## Relational databases tried to fit all sizes. ##

!SLIDE

> Database research has produced a number of good results, but the relational database is not one of them.

<p class="caption"><a href="http://home.pipeline.com/~hbaker1/letters/CACM-RelationalDatabases.html">Henry G. Baker</a></p>

!SLIDE

## What the web really needed: ##

!SLIDE center

# More structure? #

![Wordpress Schema](wordpress_schema.jpg)

!SLIDE center

<h1 style="text-decoration: line-through"><strike style="position:relative;top:1px">More structure?</strike></h1>

# No! #

!SLIDE bullets incremental

# Less structure #

* Documents
* Schemaless, not constrained
* JSON

!SLIDE

# Less structure #

    {
      "_id": "45cae57dc7504ebd630a549275",
      "_rev": "2-1403823b3baf6e493a48e7b65",
      "created_at": "2010/05/12 10:09:53",
      "title": "JSON FTW!"
    }


!SLIDE

# Simpler Data #

## "key" => "value" ##

!SLIDE

# Scaling up #

!SLIDE center

## Master-Slave ##

![Master-Slave](master_slave.png)

### (Old-school!) ###

!SLIDE center

## P2P ##

![Multi-Master](multi_master.png)

!SLIDE

# Amazon's Dynamo #

!SLIDE center

## The Ring ##

![Hash Ring](hash_ring.png)

!SLIDE center

## CAP ##

![CAP](cap.png)

### Pick two! ###

!SLIDE center
<br/>
## Eventual Consistency ##

![Eventual Consistency](eventual.jpg)

!SLIDE

## But where's the history in that? ##

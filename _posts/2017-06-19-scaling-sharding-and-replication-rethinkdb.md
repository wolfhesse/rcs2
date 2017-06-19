---
ID: 3348
post_title: 'Scaling, sharding and replication &#8211; RethinkDB'
author: rogera
post_date: 2017-06-19 10:58:50
post_excerpt: ""
layout: post
permalink: >
  http://wolfspool.at/wprcs2/2017/06/19/scaling-sharding-and-replication-rethinkdb/
published: true
---
<blockquote>r.db('rethinkdb').table('table_config').get( '31c92680-f70c-4a4b-a49e-b238eb12c023').update( {"write_acks": "single"}).run(conn)</blockquote>
Quelle: <em><a href="https://www.rethinkdb.com/docs/sharding-and-replication/">Scaling, sharding and replication - RethinkDB</a></em>
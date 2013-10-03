go-fish
=======

a toy distributed NoSQL database to be written in Go.

possible features
-----------------
* key/value store
* secondary indexing
* JSON / BSON API

objectives
----------
* fun to hack on
* distributed
* durable
* higher availability
* partition tolerant
* eventually consistent
* easy to manage
* maybe fast, someday

stuff to consider
-----------------
* how and where to store secondary indexes
* read repair, anti-entropy, blah
* conflict resolution

references
----------
* [web.go](https://github.com/hoisie/web) - super lightweight web framework
* [go-rest](https://github.com/ungerik/go-rest) - a REST server framework with a lot of interesting ideas, but only supports `GET` and `POST`???
* one of these [skip lists](https://code.google.com/p/go-wiki/wiki/Projects#Data_Structures) for in-memory key storage
* [gocask](https://code.google.com/p/gocask/) provides an (incomplete) implementation of Bitcask
* [leveldb-go](https://code.google.com/p/leveldb-go/) - another option for disk store
* [snappy](https://code.google.com/p/snappy-go/) for compressing values?
* [dht](https://github.com/nictuku/dht) - a distributed hash table implementation in Go
* [wendy](https://github.com/secondbit/wendy/) - another Go DHT
* [vclock](https://labix.org/vclock) - vector clocks for Go

## 1.0.0 / 2011-12-23

* Implement all operations using libcouchbase as backend
* Remove views code. It will be re-added in 1.1 version

## 0.9.8 / 2011-12-16

* Fix RCBC-10: It was impossible to store data in non-default buckets

## 0.9.7 / 2011-10-04

* Fix design doc removing
* Fix 'set' method signature: add missing options argument
* Rename gem to 'couchbase' for easy of use. The github project still
  is 'couchbase-ruby-client'

## 0.9.6 / 2011-10-04

* Fix bug with decoding multiget result
* Allow create design documents from IO and String
* Rename json format to document, and describe possible formats
* Allow to handle errors in view result stream
* Remove dependency on libyajl library: it bundled with yaji now
* Update rake tasks: create zip- and tar-balls

## 0.9.5 / 2011-08-24

* Update installation notes in README

## 0.9.4 / 2011-08-24

* Use streaming json parser to iterate over view results
* Update memcached gem dependency to v1.3
* Proxy TOUCH command to memcached client
* Fix minor bugs in RestClient and Document classes
* Disable CouchDB API for nodes without 'couchApiBase' key provided.
* Fix bug with unicode parsing in config listener
* Add more unit tests

## 0.9.3 / 2011-07-29

* Use Latch (via Mutex and ConditionVariable) to wait until initial
  setup will be finished.
* Update prefix for development views (from '$dev_' to 'dev_')

## 0.9.2 / 2011-07-29

* Use zero TTL by default to store records forever
* Update documentation
* Sleep if setup isn't done

## 0.9.1 / 2011-07-25

* Minor bugfix for RestClient initialization

## 0.9.0 / 2011-07-25

* Initial public release

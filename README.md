Docker BLOB storage server
===============================
author: Tobias Schoch

Overview
--------

A collection of services indcluding apache solr for uploading/query/serving binary files with metadata.


Change-Log
----------
##### 0.0.1
* initial version


Installation / Usage
--------------------
clone the repo:

```
git clone <git-url> blobdb
```
build the docker image
```
docker build . -t blobdb
```

Example
-------

run a container of the image
```
docker run -v ... -p ... blobdb
```



Use Docker to install CouhDB 

```cassandraql
docker run -d --name my-couchdb couchdb:tag

```

Test by Curl 


```
curl http://127.0.0.1:5984/

```

Reference :
https://hub.docker.com/_/couchdb



Access CouchDB via docker 

```cassandraql
$ docker exec -it my-couchdb bash

```



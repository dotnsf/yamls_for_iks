# yamls for IKS

## Overview

Sample .yaml files which can be run on IKS(IBM Kubernetes Services) as free tier.


## How to setup IKS

- Create IBM Cloud account

  - It has to be **basic** account, not lite one.

- Login to IBM Cloud dashboard

- Create IKS service as Free plan(30 days).

- Install **kubectl** and **ibmcloud CLI**.

- Login to IKS with ibmcloud CLI.

  - `$ ibmcloud login`

- Configure ibmcloud CLI to use **your** IKS cluster

  - `$ ibmcloud ks cluster config -c *********`

    - You can check in your IKS service environment.


## How to check IP address of your worker node

- You can check IP address of your worker node as **Public** IP.

  - `$ ibmcloud ks worker ls --cluster your_iks_cluster_name`


## Sample file list

- [x] 2048.yaml : [**2048 Game**](https://hub.docker.com/r/ponsfrilus/2048nginx)
- [x] apache.yaml : [**Apache HTTP server**](https://hub.docker.com/_/httpd)
- [x] couchbase.yaml : [**CoubhBase**](https://hub.docker.com/_/couchbase)
- [x] couchdb.yaml : [**CouchDB**](https://hub.docker.com/_/couchdb)
- [x] dosbox.yaml : [**DOSBox**](https://hub.docker.com/r/jgoerzen/dosbox)
- [x] drupal.yaml : [**Drupal**](https://hub.docker.com/_/drupal)
- [x] elasticsearch.yaml : [**ElasticSearch**](https://hub.docker.com/_/elasticsearch)
- [x] fx.yaml : [**fx**](https://hub.docker.com/r/dotnsf/fx)
- [x] hatoya.yaml : [**HATOYA**](https://hub.docker.com/r/dotnsf/hatoya)
- [x] hostname.yaml : [**hostname**](https://hub.docker.com/r/dotnsf/hostname)
- [x] jenkins.yaml : [**jenkins**](https://hub.docker.com/r/jenkins/jenkins)
- [x] kibana.yaml : [**Kibana**](https://hub.docker.com/_/kibana)
- [x] mongodb.yaml : [**MongDB**](https://hub.docker.com/_/mongo)
- [x] mongoexpress.yaml : [**Mong-Express**](https://hub.docker.com/_/mongo-express)
- [x] mysql.yaml : [**MySQL**](https://hub.docker.com/_/mysql)
- [x] nginx.yaml : [**Nginx**](https://hub.docker.com/_/nginx)
- [x] nodered.yaml : [**Node-RED**](https://hub.docker.com/r/nodered/node-red)
- [x] orion.yaml : [**Eclipse Orion**](https://hub.docker.com/r/cloudeity/orion)
- [x] pgadmin4.yaml : [**Pgadmin4**,](https://hub.docker.com/r/dpage/pgadmin4) Web client for PostgreSQL
- [x] phpmydmin.yaml : [**phpMyAdmin**,](https://hub.docker.com/_/phpmyadmin) Web client for MySQL
- [x] postgresql.yaml : [**PostgreSQL**](https://hub.docker.com/_/postgres)
- [x] redis.yaml : [**Redis**](https://hub.docker.com/_/redis)
- [x] rediscommander.yaml : [**Redis Commander**](https://hub.docker.com/r/rediscommander/redis-commander)
- [x] rstudio.yaml : [**R Studio**](https://hub.docker.com/r/rocker/rstudio)
- [x] scratch3.yaml : [**MIT Scratch3**](https://hub.docker.com/r/kadok0520/mit-scratch3)
- [x] swaggereditor.yaml : [**Swagger Editor**](https://hub.docker.com/r/swaggerapi/swagger-editor)
- [x] tomcat.yaml : [**Tomcat**](https://hub.docker.com/_/tomcat)
- [x] vncserver.yaml : [**Lubuntu + VNCServer**](https://hub.docker.com/r/vncserver/lubuntu)
- [x] wasliberty.yaml : [**WebSphere Liberty**](https://hub.docker.com/_/websphere-liberty)
- [x] wordpress.yaml : [**WordPress**](https://hub.docker.com/_/wordpress)


## Planning list for "30 days k8s"

- Overview

  0. How to install/setup IBM Cloud k8s services

- Web servers

  1. Hostname

  2. Apache HTTP

  3. Nginx

  4. Tomcat

  5. WAS Liberty

- Databases

  6. MySQL

  7. phpMyAdmin

  8. PostgreSQL

  9. pgAdmin4

  10. MongoDB

  11. MongoExpress

  12. Redis

  13. RedisCommander

  14. ElasticSearch

  15. Kibana

  16. CouchDB

  17. CouchBase

  18. HATOYA

- Programming

  19. Node-RED

  20. Scratch3

  21. Orion

  22. Swagger Editor

  23. R Studio

  24. Jenkins

- Applications

  25. FX

  26. 2048

  27. DOS box

  28. VNC Server

  29. Drupal

  30. WordPress



## License

This code is licensed under MIT.

## Copyright

[K.Kimura @ Juge.Me](https://github.com/dotnsf) all rights reserved.

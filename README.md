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

- 2048.yaml : [**2048 Game**](https://hub.docker.com/r/ponsfrilus/2048nginx)
- apache.yaml : [**Apache HTTP server**](https://hub.docker.com/_/httpd)
- couchbase.yaml : [**CoubhBase**](https://hub.docker.com/_/couchbase)
- couchdb.yaml : [**CouchDB**](https://hub.docker.com/_/couchdb)
- dosbox.yaml : [**DOSBox**](https://hub.docker.com/r/jgoerzen/dosbox)
- drupal.yaml : [**Drupal**](https://hub.docker.com/_/drupal)
- elasticsearch.yaml : [**ElasticSearch**](https://hub.docker.com/_/elasticsearch)
- fx.yaml : [**fx**](https://hub.docker.com/r/dotnsf/fx)
- hatoya.yaml : [**HATOYA**](https://hub.docker.com/r/dotnsf/hatoya)
- hostname.yaml : [**hostname**](https://hub.docker.com/r/dotnsf/hostname)
- jenkins.yaml : [**jenkins**](https://hub.docker.com/r/jenkins/jenkins)
- kibana.yaml : [**Kibana**](https://hub.docker.com/_/kibana)
- mongodb.yaml : [**MongDB**](https://hub.docker.com/_/mongo)
- mongoexpress.yaml : [**Mong-Express**](https://hub.docker.com/_/mongo-express)
- mysql.yaml : [**MySQL**](https://hub.docker.com/_/mysql)
- nginx.yaml : [**Nginx**](https://hub.docker.com/_/nginx)
- nodered.yaml : [**Node-RED**](https://hub.docker.com/r/nodered/node-red)
- orion.yaml : [**Eclipse Orion**](https://hub.docker.com/r/cloudeity/orion)
- pgadmin4.yaml : [**Pgadmin4**,](https://hub.docker.com/r/dpage/pgadmin4) Web client for PostgreSQL
- phpmydmin.yaml : [**phpMyAdmin**,](https://hub.docker.com/_/phpmyadmin) Web client for MySQL
- postgresql.yaml : [**PostgreSQL**](https://hub.docker.com/_/postgres)
- redis.yaml : [**Redis**](https://hub.docker.com/_/redis)
- rediscommander.yaml : [**Redis Commander**](https://hub.docker.com/r/rediscommander/redis-commander)
- rstudio.yaml : [**R Studio**](https://hub.docker.com/r/rocker/rstudio)
- scratch3.yaml : [**MIT Scratch3**](https://hub.docker.com/r/kadok0520/mit-scratch3)
- swaggereditor.yaml : [**Swagger Editor**](https://hub.docker.com/r/swaggerapi/swagger-editor)
- tomcat.yaml : [**Tomcat**](https://hub.docker.com/_/tomcat)
- vncserver.yaml : [**Lubuntu + VNCServer**](https://hub.docker.com/r/vncserver/lubuntu)
- wasliberty.yaml : [**WebSphere Liberty**](https://hub.docker.com/_/websphere-liberty)
- wordpress.yaml : [**WordPress**](https://hub.docker.com/_/wordpress)


## License

This code is licensed under MIT.

## Copyright

[K.Kimura @ Juge.Me](https://github.com/dotnsf) all rights reserved.

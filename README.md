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

- 2048_deployment_nodeport.yaml : [**2048 Game**](https://hub.docker.com/r/ponsfrilus/2048nginx)
- apache_deployment_nodeport.yaml : [**Apache HTTP server**](https://hub.docker.com/_/httpd)
- couchbase_deployment_nodeport.yaml : [**CoubhBase**](https://hub.docker.com/_/couchbase)
- couchdb_deployment_nodeport.yaml : [**CouchDB**](https://hub.docker.com/_/couchdb)
<!-- - db2_deployment_nodeport.yaml : [**DB2**](https://hub.docker.com/r/ibmcom/db2) -->
<!-- - derby_deployment_nodeport.yaml : [**Derby**](https://hub.docker.com/r/datagrip/derby-server) -->
- dosbox_deployment_nodeport.yaml : [**DOSBox**](https://hub.docker.com/r/jgoerzen/dosbox)
- drupal_deployment_nodeport.yaml : [**Drupal**](https://hub.docker.com/_/drupal)
- elasticsearch_deployment_nodeport.yaml : [**ElasticSearch**](https://hub.docker.com/_/elasticsearch)
- hatoya_deployment_nodeport.yaml : [**HATOYA**](https://hub.docker.com/r/dotnsf/hatoya)
- hostname_deployment_nodeport.yaml : [**hostname**](https://hub.docker.com/r/dotnsf/hostname)
- jenkins_deployment_nodeport.yaml : [**jenkins**](https://hub.docker.com/r/jenkins/jenkins)
- kibana_deployment_nodeport.yaml : [**Kibana**](https://hub.docker.com/_/kibana)
- mongodb_deployment_nodeport.yaml : [**MongDB**](https://hub.docker.com/_/mongo)
- mongoexpress_deployment_nodeport.yaml : [**Mong-Express**](https://hub.docker.com/_/mongo-express)
- mysql_deployment_nodeport.yaml : [**MySQL**](https://hub.docker.com/_/mysql)
- nginx_deployment_nodeport.yaml : [**Nginx**](https://hub.docker.com/_/nginx)
- nodered_deployment_nodeport.yaml : [**Node-RED**](https://hub.docker.com/r/nodered/node-red)
- orion_deployment_nodeport.yaml : [**Eclipse Orion**](https://hub.docker.com/r/cloudeity/orion)
- pgadmin4_deployment_nodeport.yaml : [**Pgadmin4**,](https://hub.docker.com/r/dpage/pgadmin4) Web client for PostgreSQL
- phpmydmin_deployment_nodeport.yaml : [**phpMyAdmin**,](https://hub.docker.com/_/phpmyadmin) Web client for MySQL
- postgresql_deployment_nodeport.yaml : [**PostgreSQL**](https://hub.docker.com/_/postgres)
- redis_deployment_nodeport.yaml : [**Redis**](https://hub.docker.com/_/redis)
- rediscommander_deployment_nodeport.yaml : [**Redis Commander**](https://hub.docker.com/r/rediscommander/redis-commander)
- rstudio_deployment_nodeport.yaml : [**R Studio**](https://hub.docker.com/r/rocker/rstudio)
- scratch3_deployment_nodeport.yaml : [**MIT Scratch3**](https://hub.docker.com/r/kadok0520/mit-scratch3)
- swaggereditor_deployment_nodeport.yaml : [**Swagger Editor**](https://hub.docker.com/r/swaggerapi/swagger-editor)
- tomcat_deployment_nodeport.yaml : [**Tomcat**](https://hub.docker.com/_/tomcat)
- vncserver_deployment_nodeport.yaml : [**Lubuntu + VNCServer**](https://hub.docker.com/r/vncserver/lubuntu)
- wasliberty_deployment_nodeport.yaml : [**WebSphere Liberty**](https://hub.docker.com/_/websphere-liberty)
- wordpress_deployment_nodeport.yaml : [**WordPress**](https://hub.docker.com/_/wordpress)


## License

This code is licensed under MIT.

## Copyright

[K.Kimura @ Juge.Me](https://github.com/dotnsf) all rights reserved.

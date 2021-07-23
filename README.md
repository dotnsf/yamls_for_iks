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

    - http://dotnsf.blog.jp/archives/1079287640.html

- Web servers

  1. Hostname

    - http://dotnsf.blog.jp/archives/1079288471.html

  2. Apache HTTP

    - http://dotnsf.blog.jp/archives/1079301713.html

  3. Nginx

    - http://dotnsf.blog.jp/archives/1079305477.html

  4. Tomcat

    - http://dotnsf.blog.jp/archives/1079311794.html

  5. WAS Liberty

    - http://dotnsf.blog.jp/archives/1079311810.html

- Databases

  6. MySQL

    - http://dotnsf.blog.jp/archives/1079312476.html

  7. phpMyAdmin

    - http://dotnsf.blog.jp/archives/1079312511.html

  8. PostgreSQL

    - http://dotnsf.blog.jp/archives/1079315978.html

  9. pgAdmin4

    - http://dotnsf.blog.jp/archives/1079316017.html

  10. MongoDB

    - http://dotnsf.blog.jp/archives/1079316940.html

  11. MongoExpress

    - http://dotnsf.blog.jp/archives/1079316982.html

  12. Redis

    - http://dotnsf.blog.jp/archives/1079317638.html

  13. RedisCommander

    - http://dotnsf.blog.jp/archives/1079317678.html

  14. ElasticSearch

    - http://dotnsf.blog.jp/archives/1079317698.html

  15. Kibana

    - http://dotnsf.blog.jp/archives/1079317718.html

  16. CouchDB

    - http://dotnsf.blog.jp/archives/1079325883.html

  17. CouchBase

    - http://dotnsf.blog.jp/archives/1079325930.html

  18. HATOYA

    - http://dotnsf.blog.jp/archives/1079333267.html

- Programming

  19. Node-RED

    - http://dotnsf.blog.jp/archives/1079333305.html

  20. Scratch3

    - http://dotnsf.blog.jp/archives/1079333327.html

  21. Orion

    - http://dotnsf.blog.jp/archives/1079333378.html

  22. Swagger Editor

    - http://dotnsf.blog.jp/archives/1079333767.html

  23. R Studio

    - http://dotnsf.blog.jp/archives/1079333808.html

  24. Jenkins

    - http://dotnsf.blog.jp/archives/1079333838.html

- Applications

  25. FX

    - http://dotnsf.blog.jp/archives/1079333894.html

  26. 2048

    - http://dotnsf.blog.jp/archives/1079333941.html

  27. DOS box

    - http://dotnsf.blog.jp/archives/1079333968.html

  28. VNC Server

    - http://dotnsf.blog.jp/archives/1079334009.html

  29. Drupal

    - http://dotnsf.blog.jp/archives/1079334044.html

  30. WordPress

    - http://dotnsf.blog.jp/archives/1079334115.html



## License

This code is licensed under MIT.

## Copyright

[K.Kimura @ Juge.Me](https://github.com/dotnsf) all rights reserved.

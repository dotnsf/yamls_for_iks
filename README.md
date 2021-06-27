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

- couchbase_deployment_nodeport.yaml : [**CoubhBase**](https://hub.docker.com/_/couchbase)
- couchdb_deployment_nodeport.yaml : [**CouchDB**](https://hub.docker.com/_/couchdb)
- drupal_deployment_nodeport.yaml : [**Drupal**](https://hub.docker.com/_/drupal)
- elasticsearch_deployment_nodeport.yaml : [**ElasticSearch](https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html)
- mongodb_deployment_nodeport.yaml : [**MongDB**](https://hub.docker.com/_/mongo)
- mongoexpress_deployment_nodeport.yaml : [**Mong-Express**](https://hub.docker.com/_/mongo-express)
- mysql_deployment_nodeport.yaml : [**MySQL**](https://hub.docker.com/_/mysql)
- nodered_deployment_nodeport.yaml : [**Node-RED**](https://hub.docker.com/r/nodered/node-red)
- pgadmin4_deployment_nodeport.yaml : [**Pgadmin4**,](https://hub.docker.com/r/dpage/pgadmin4) Web client for PostgreSQL
- phpmydmin_deployment_nodeport.yaml : [**phpMyAdmin**,](https://hub.docker.com/_/phpmyadmin) Web client for MySQL
- postgresql_deployment_nodeport.yaml : [**PostgreSQL**](https://hub.docker.com/_/postgres)
- redis_deployment_nodeport.yaml : [**Redis**](https://hub.docker.com/_/redis)
- scratch3_deployment_nodeport.yaml : [**MIT Scratch3**](https://hub.docker.com/r/kadok0520/mit-scratch3)
- wordpress_deployment_nodeport.yaml : [**WordPress**](https://hub.docker.com/_/wordpress)


## License

This code is licensed under MIT.

## Copyright

[K.Kimura @ Juge.Me](https://github.com/dotnsf) all rights reserved.

# vertx-awesome

Vert.x Awesome is an list of awesome frameworks, libraries or other components for use with
[Vert.x](https://github.com/eclipse/vert.x) version 3.

If you want your component to appear here, send a pull request to this repository to add it.

Please note that we can't vouch for the stability or production-worthiness of everything on this list unless it has 
the icon ![(stack)](stack.png "Vert.x Stack") next to it. This means that the component is part of the `official` Vert.x
stack.

For vert.x version 2, check [this page](./vert-x2.md).

## Contents

- [Database Clients](#database-clients)
- [Integration](#integration)
- [Language Support](#language-support)
- [Vert.x Event Bus Clients](#vertx-event-bus-clients)
- [Cluster Managers](#cluster-managers)
- [Cloud Support](#cloud-support)
- [Docker](#docker)
- [Search engines](#search-engines)

## Database Clients

*Clients for connecting to databases*

* Relational Databases
  * [JDBC](https://github.com/vert-x3/vertx-jdbc-client) ![(stack)](stack.png "Vert.x Stack") - Asynchronous interface around a JDBC datasource
  * [MySQL](https://github.com/vert-x3/vertx-mysql-postgresql-client) ![(stack)](stack.png "Vert.x Stack") - Asynchronous client for MySQL
  * [PostgreSQL](https://github.com/vert-x3/vertx-mysql-postgresql-client) - Asynchronous client for PostgreSQL

* NoSQL Databases
  * [MongoDB](https://github.com/vert-x3/vertx-mongo-client) ![(stack)](stack.png "Vert.x Stack") - An asynchronous client for interacting with a MongoDB database
  * [Redis](https://github.com/vert-x3/vertx-redis-client) ![(stack)](stack.png "Vert.x Stack") - Asynchronous API to interact with Redis

## Integration

* Mail
  * [SMTP](https://github.com/vert-x3/vertx-mail-client) ![(stack)](stack.png "Vert.x Stack") - Async SMTP client

* Messaging
  * [AMQP 1.0](https://github.com/vert-x3/vertx-amqp-service) - Async AMQP 1.0 bridge
  * [RabbitMQ](https://github.com/vert-x3/vertx-rabbitmq-client) - RabbitMQ client (AMQP 0.9.4)

* JavaEE
  * [JCA adaptor](https://github.com/vert-x3/vertx-jca) ![(stack)](stack.png "Vert.x Stack") - Java Connector Architecture Adaptor for the Vert.x event bus

* Meteor
  * [Meteor](https://github.com/jmusacchio/vertxbus/) - Meteor integration support through Vert.x event bus

* Metrics
 * [Hawkular metrics](https://github.com/tsegismont/vertx-monitor) -  [Hawkular](http://www.hawkular.org/) implementation of the Vert.x Metrics SPI
 * [DropWizard metrics](https://github.com/vert-x3/vertx-dropwizard-metrics) ![(stack)](stack.png "Vert.x Stack") - Metrics implementation using DropWizard metrics

## Language Support

*Programming language support for Vert.x*

* [Ceylon](https://github.com/vert-x3/vertx-lang-ceylon) - Ceylon support
* [Groovy](https://github.com/vert-x3/vertx-lang-groovy) ![(stack)](stack.png "Vert.x Stack") - Groovy support
* [Java](https://github.com/eclipse/vert.x) ![(stack)](stack.png "Vert.x Stack") - Vert.x main repository (including the Java API)
* [JavaScript](https://github.com/vert-x3/vertx-lang-js) ![(stack)](stack.png "Vert.x Stack") - JavaScript support
* [Python](https://github.com/vert-x3/vertx-lang-python) - Python support
* [Ruby](https://github.com/vert-x3/vertx-lang-ruby) ![(stack)](stack.png "Vert.x Stack") - Ruby support
* [Scala](https://github.com/vert-x3/vertx-lang-scala) - Scala support
* [TypeScript](https://github.com/michel-kraemer/vertx-lang-typescript) - TypeScript support

## Vert.x Event Bus Clients

*Clients to connect applications to the vert.x event bus*

* [C++11](https://github.com/julien3/vertxbuspp) - C++11 event bus client

## Cluster Managers

*Implementations of the vert.x cluster manager SPI*

* [Hazelcast Cluster Manager](https://github.com/vert-x3/vertx-hazelcast) ![(stack)](stack.png "Vert.x Stack") - Hazelcast cluster manager
* [JGroups Cluster Manager](https://github.com/vert-x3/vertx-jgroups) - JGroups cluster manager
* [Zookeeper Cluster Manager](https://github.com/stream1984/vertx-zookeeper) - Zookeeper cluster manager
* [Copycat Cluster Manager](https://github.com/kuujo/vertx-copycat) - a [Copycat](https://github.com/kuujo/copycat) based Cluster Manager implementation for Vert.x 3.

## Cloud Support

* [OpenShift DIY cartridge](https://github.com/vert-x3/vertx-openshift-diy-quickstart) - OpenShift DIY Cartridge using Vert.x
* [OpenShift Vert.x cartridge](https://github.com/vert-x3/vertx-openshift-cartridge) - OpenShift Vert.x Cartridge using Vert.x

## Docker

* [Docker images](https://github.com/vert-x3/vertx-stack/tree/master/stack-docker) - Docker images for Vert.x

## Search engines

* [Vert.x ElasticSearch Service](https://github.com/englishtown/vertx-elasticsearch-service) - Vert.x 3 [elastic search](https://www.elastic.co/) service with event bus proxying.


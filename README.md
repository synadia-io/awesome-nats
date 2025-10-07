# Awesome NATS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A Synadia curated list of awesome NATS resources!


## Table of Contents

- [Server](#server)
- [Clients](#clients)
- [Kubernetes](#kubernetes)

## General

The must haves

- [NATS Server](http://github.com/nats-io/nats-server) - The only binary you need to run single server, clusters, super-clusters and leaf nodes
- [NATS CLI](http://github.com/nats-io/natscli) - CLI for managing, interacting, benchmarking and debugging NATS

## Docs and learning materials

- [Official Docs](https://docs.nats.io) - Official NATS documentation page
- [Synadia Website](https://www.synadia.com) - Official Synadia website
- [NATS By Example](https://natsbyexample.com) - An evolving collection of runnable, cross-client reference examples for NATS
- [Synadia Youtube Channel](https://www.youtube.com/@SynadiaCommunications) - Growing list of videos NATS, covering wide variety of topics
- [NATS.fm](https://www.synadia.com/podcast) - Podcast dedicated to NATS, hosted by David Gee and Byron Ruth
- [Java NATS examples](https://github.com/nats-io/java-nats-examples/tree/main) - Collection of Java (and Kotlin) examples

## Clients

List of all NATS clients - the officially supported and community driven.

### Tier One Clients

List of clients with support for all features of most recent NATS releases.

- [Go](http://github.com/nats-io/nats.go)
- [Rust](http://github.com/nats-io/nats.rs)
- [Java](http://github.com/nats-io/nats.java)
- [Python](http://github.com/nats-io/nats.py)
- [C](http://github.com/nats-io/nats.c)
- [.NET.v2](http://github.com/nats-io/nats.net.v2) - A new async & modern .NET client
- [Deno](http://github.com/nats-io/nats.deno)
- [Node](https://github.com/nats-io/nats.js)
- [WebSocket](http://github.com/nats-io/nats.ws) - Websocket JavaScript client for the Browser

### Tier Two Clients

Officially supported clients that may miss some features

- [Elixir](http://github.com/nats-io/nats.ex)
- [.NET](http://github.com/nats-io/nats.net)
- [Pure Ruby](http://github.com/nats-io/nats-pure.rb)
- [Ruby](http://github.com/nats-io/nats-pure.rb)
- [Crystal](http://github.com/nats-io/nats.cr)

### Community Clients

Community driven clients

- [Tcl](https://github.com/Kazmirchuk/nats-tcl)
- [Crystal](https://github.com/jgaskins/nats) - most up to date Crystal client
- [PHP](https://github.com/basis-company/nats.php) - with support for Core NATS, JetStream and KV
- [Dart](https://github.com/chartchuo/dart-nats)
- [Pascal](https://github.com/biot2/nats.pas)

## Ansible

Anisble rules for provisioning NATS on servers:

- [Ansible Role NATS](https://github.com/snapp-cab/ansible-role-nats)

## Kubernetes

Tools useful when working with NATS in Kubernetes ecosystem.

- [NATS Helm Charts](https://github.com/nats-io/k8s) - Helm charts for NATS, NACK, Surveyor and others
- [NACK](http://github.com/nats-io/nack) - NATS controllers and CRDs for Kubernetes

## Monitoring and Observability

- [Surveyor](http://github.com/nats-io/nats-surveyor) - Simplified NATS observability
- [Prometheus NATS exporter](https://github.com/nats-io/prometheus-nats-exporter) - Export NATS Server metrics to Prometheus
- [NATS dashboard](https://natsdashboard.com/) - GUI for real-time monitoring of nats-server (exposes Core NATS plus JetStream information)
- [NATS Alerts](https://samber.github.io/awesome-prometheus-alerts/rules#nats) - basic set of Prometheus alerts for NATS
## Connectors and Integrations

- [Flink](https://github.com/synadia-io/flink-connector-nats) - Flink Connector
- [Spark](https://github.com/nats-io/nats-spark-connector) - Spark connector
- [Kafka](https://github.com/nats-io/nats-kafka) - Kafka bridge
- [Redis](https://github.com/nats-io/nats-connector-redis) - Redis connector
- [Dapr](https://docs.dapr.io/reference/components-reference/supported-pubsub/setup-jetstream/) - Dapr KV and JetSteram integration
- [MongoDB](https://github.com/damianiandrea/mongodb-nats-connector)
- [Debezium](https://github.com/ConnectEverything/nats-by-example/tree/main/examples/integrations/debezium) - Debezium to JetStream built-in the Debezium server
 
## Built on top of NATS and JetStream

- [HA](https://github.com/litesql/ha) - Highly available leaderless SQLite cluster powered by embedded NATS JetStream server
- [Marmot](https://github.com/maxpert/marmot) - A distributed SQLite replicator built on top of NATS
- [Nqlite](https://github.com/voxoco/nqlite) - Lightweight relational database using SQLite as the storage engine and NATS Jetstream for replication and persistence
- [Simple IoT](https://docs.simpleiot.org/) - Add connectivity to your edge device, monitor systems, and control devices -- made possible by NATS.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

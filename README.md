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
- [Node](http://github.com/nats-io/nats.node)
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

## Kubernetes

Tools useful when working with NATS in Kubernetes ecosystem.

- [NATS Helm Charts](https://github.com/nats-io/k8s) - Helm charts for NATS, NACK, Surveyor and others
- [NACK](http://github.com/nats-io/nack) - NATS controllers and CRDs for Kubernetes

## Monitoring and Observability

- [Surveyor](http://github.com/nats-io/nats-surveyor) - Simplified NATS observability
- [Prometheus NATS exporter](https://github.com/nats-io/prometheus-nats-exporter) - Export NATS Server metrics to Prometheus

## Connectors and Integrations

- [Flink](https://github.com/synadia-io/flink-connector-nats) - Flink Connector
- [Spark](https://github.com/nats-io/nats-spark-connector) - Spark connector
- [Kafka](https://github.com/nats-io/nats-kafka) - Kafka bridge
- [Redis](https://github.com/nats-io/nats-connector-redis) - Redis connector
- [Dapr](https://docs.dapr.io/reference/components-reference/supported-pubsub/setup-jetstream/) - Dapr KV and JetSteram integration
- [MongoDB](https://github.com/damianiandrea/mongodb-nats-connector)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

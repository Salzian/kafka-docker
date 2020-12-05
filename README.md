# kafka-docker

kafka-docker is a simple collection of Dockerfiles to build docker images for Kafka.

## Currently included versions

- 2.6.0

## Tags

### kafka:base; kafka:\<version>-base

Base image of openjdk:11 with Apache Kafka downloaded.

### kafka:zookeeper; kafka:\<version>-zookeeper

kafka:base with entrypoint set to start a zookeeper node

### kafka:broker; kafka:\<version>-broker

kafka:base with entrypoint set to start a broker node
FROM openjdk:11 AS build

RUN apt update \
    && apt install -y wget \
    && apt install -y tar

WORKDIR /kafka

RUN wget https://ftp.fau.de/apache/kafka/2.6.0/kafka_2.13-2.6.0.tgz \
    && tar xf ./kafka_2.13-2.6.0.tgz \
    && mv ./kafka_2.13-2.6.0/* ./ \
    && rm ./kafka_2.13-2.6.0.tgz \
    && rm -r ./kafka_2.13-2.6.0/

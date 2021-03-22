# kafka-ms-main
Main part.

This is the main part which will unite all microservices into one project

# Diagram

<img src="https://raw.githubusercontent.com/andersonef/kafka-ms-broker/master/ms-diagram.png">

## Legend
<ul>
    <li><strong style="color: #D5E8D4">Green</strong>: Broker Microservice. kafka-ms-broker</li>
    <li><strong style="color: #DAE8FC">Blue</strong>: Requester Microservice. kafka-ms-requester</li>
    <li><strong style="color: #F8CECC">Orange</strong>: Kafka Instance. kafka-ms-kafka</li>
    <li><strong style="color: #FFF2CC">Yellow</strong>: Service A Microservice. kafka-ms-service-a</li>
</ul>

# Usage

In order to put this microservice on, you'll need to follow the following steps:

```shell
$ git clone https://github.com/andersonef/kafka-ms-main kafka-ms-main
$ cd kafka-ms-main
$ git submodule init
$ git submodule update --remote
$ chmod +x ./scripts/up.sh
$ chmod +x kafka-ms-broker/scripts/up.sh
$ chmod +x kafka-ms-broker/scripts/down.sh
$ chmod +x kafka-ms-kafka/scripts/up.sh
$ ./scripts/up.sh
```

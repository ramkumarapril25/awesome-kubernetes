# Message Queue in Kubernetes. Event-driven Messaging. Real-Time Data Streaming
- [Wikipedia: Message Broker](https://en.wikipedia.org/wiki/Message_broker)
- [Wikipedia: Event-driven messaging](https://en.wikipedia.org/wiki/Event-driven_messaging)
- [Wikipedia: Streaming Data](https://en.wikipedia.org/wiki/Streaming_data)

## Message Brokers
- [Apache ActiveMQ](https://activemq.apache.org/)
    - [ActiveMQ 5.x "classic"](https://activemq.apache.org/components/classic/)
    - [ActiveMQ Artemis](https://activemq.apache.org/components/artemis/)
    - [Apache Artemis JMeter](https://github.com/apache/activemq-artemis/tree/master/examples/perf/jmeter) Running the ActiveMQ Artemis JMeter Performance Testing Examples.
- [Dzone: Introduction to Message Brokers. Part 1: Apache Kafka vs. RabbitMQ](https://dzone.com/articles/introduction-to-message-brokers-part-1-apache-kafk)
- [Dzone: Introduction to Message Brokers. Part 2: ActiveMQ vs. Redis Pub/Sub](https://dzone.com/articles/introduction-to-message-brokers-part-2-activemq-vs)

## KubeMQ
- [KubeMQ.io: Kubernetes Native Message Queue Broker](https://kubemq.io/)
- [devops.com: Best of 2019: Implementing Message Queue in Kubernetes](https://devops.com/implementing-message-queue-in-kubernetes/)
- [kubemq.io: Kafka VS KubeMQ](https://kubemq.io/kafka-vs-kubemq/)

## Kakfa
- [developers.redhat.com: how easy to deploy and configure a Kafka Connect on Kubernetes through strimziio operator and use secrets](https://developers.redhat.com/blog/2020/02/14/using-secrets-in-apache-kafka-connect-configuration/)
- [developers.redhat.com: Using secrets in Kafka Connect configuration](https://developers.redhat.com/blog/2020/02/14/using-secrets-in-apache-kafka-connect-configuration/)
- [developers.redhat.com: Capture database changes with Debezium Apache Kafka connectors](https://developers.redhat.com/blog/2020/04/14/capture-database-changes-with-debezium-apache-kafka-connectors/)

### Banzai Cloud Supertubes (Cloud Native Kafka implementation)
- [Banzai Cloud](https://banzaicloud.com/)
- [Banzai Kafka Operator](https://github.com/banzaicloud/kafka-operator)
- [The benefits of integrating Apache Kafka with Istio](https://banzaicloud.com/blog/kafka-on-istio-benefits/)

## Red Hat AMQ
- [Red Hat AMQ](https://www.redhat.com/en/technologies/jboss-middleware/amq) = AMQ Broker (Apache ActiveMQ Artemis) + AMQ Streams (Apache Kafka)
- [Red Hat **AMQ streams** (kafka): Simplify Apache Kafka on Red Hat OpenShift](https://www.redhat.com/en/resources/amq-streams-datasheet)
- [Set up **Red Hat AMQ Streams** custom certificates on OpenShift](https://developers.redhat.com/blog/2020/04/01/set-up-red-hat-amq-streams-custom-certificates-on-openshift-update/)

## RabbitMQ
- [K8s prevent queue worker Pod from being killed during deployment](https://itnext.io/k8s-prevent-queue-worker-pod-from-being-killed-during-deployment-4252ea7c13f6) How to prevent a Kubernetes (like RabbitMQ) queue worker Pod from being killed during deployment while handling a message?

## Red Hat Fuse Online and Syndesis
- [Red Hat Fuse Online](https://www.redhat.com/en/technologies/jboss-middleware/fuse-online)
- [developers.redhat.com: Low-code microservices orchestration with **Syndesis** (OpenSource Project for **Red Hat Fuse Online**)](https://developers.redhat.com/blog/2020/03/25/low-code-microservices-orchestration-with-syndesis/)

## Related
- [Service meshes to the rescue: Load balancing and scaling long-lived connections in Kubernetes](https://learnk8s.io/kubernetes-long-lived-connections)
- [Debezium](https://debezium.io/) Stream changes from your database
- [Red Hat Integration service registry](https://developers.redhat.com/blog/2019/12/16/getting-started-with-red-hat-integration-service-registry/)
    - [**Apicurio** Registry](https://github.com/apicurio/apicurio-registry) An API/Schema registry - stores APIs and Schemas.

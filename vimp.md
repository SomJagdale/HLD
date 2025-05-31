| **Goal / Concern**         | **What It Means**                            | **How It’s Achieved**                                                              |
| -------------------------- | -------------------------------------------- | ---------------------------------------------------------------------------------- |
| **Scalability**            | System can handle increasing load/users      | Sharding, Load Balancing, Horizontal Scaling, Partitioning                         |
| **Availability**           | System is always accessible                  | Replication, Redundancy, Failover, Load Balancers, Health Checks                   |
| **Reliability**            | System works correctly over time             | Replication, Retry Logic, Circuit Breakers, Durable Storage                        |
| **Fault Tolerance**        | System continues operating despite failures  | Redundancy, Heartbeats, Timeouts, Leader Election, Chaos Engineering               |
| **Consistency**            | Data is the same across all nodes            | Consensus Algorithms (Raft, Paxos), ACID Transactions, Strong Consistency Settings |
| **Eventual Consistency**   | Data will become consistent over time        | Async Replication, Gossip Protocol, Conflict Resolution                            |
| **Performance**            | Fast response times                          | Caching (Redis, Memcached), Compression, CDNs, Indexing                            |
| **Latency**                | Delay between request and response           | Caching, Proximity (CDNs, edge computing), Async Processing, Load Distribution     |
| **Throughput**             | Amount of work done in a time period         | Batching, Parallel Processing, Stream Processing (Kafka, Flink), Load Balancing    |
| **Security**               | Protect system/data from unauthorized access | Authentication, Authorization, Encryption (TLS, AES), Firewalls, IAM Policies      |
| **Maintainability**        | Easy to update and debug                     | Clean Architecture, Modular Design, CI/CD, Logging, Monitoring                     |
| **Observability**          | Understand internal state of the system      | Logging, Metrics, Tracing (ELK, Prometheus + Grafana, Jaeger)                      |
| **Extensibility**          | Easy to add new features                     | Plug-in Architecture, Clean Interfaces, Dependency Injection                       |
| **Modularity**             | Divide system into components                | Microservices, Domain-Driven Design (DDD), Packages/Modules                        |
| **Testability**            | Easy to write and run tests                  | Layered Architecture, Mocking, Dependency Injection                                |
| **Cost Efficiency**        | Use minimal resources for maximum output     | Auto-scaling, Spot Instances, Serverless, Efficient Algorithms                     |
| **Data Durability**        | Data is not lost permanently                 | Persistent Storage, Backups, WAL (Write-Ahead Logging), Replication                |
| **Deployment Flexibility** | Easily deploy and update system              | Docker, Kubernetes, CI/CD Pipelines, Blue-Green/Canary Deployments                 |


| **Category**             | **Examples**                                                 |
| ------------------------ | ------------------------------------------------------------ |
| **Architecture Styles**  | Monolith, Microservices, Serverless, Event-Driven, Layered   |
| **Data Patterns**        | CQRS, Event Sourcing, Saga, Sharding, Replication            |
| **Consistency Patterns** | Read/Write Quorums, Two-Phase Commit, Leader Election        |
| **Performance**          | Caching, Async Queues, Load Balancers, Throttling            |
| **Reliability**          | Retry with Backoff, Circuit Breaker, Health Checks, Failover |
| **Scaling Patterns**     | Horizontal Scaling, Auto-scaling, Fan-out/Fan-in             |
| **Security**             | OAuth2, JWT, TLS/SSL, Role-Based Access Control              |
| **Observability Tools**  | ELK Stack, Prometheus, Grafana, Jaeger, OpenTelemetry        |



| **Concern**  | **Tech/Service**                            |
| ------------ | ------------------------------------------- |
| Caching      | Redis, Memcached                            |
| Messaging    | Kafka, RabbitMQ                             |
| Storage      | S3, HDFS, PostgreSQL, Cassandra             |
| Coordination | Zookeeper, etcd                             |
| Monitoring   | Prometheus, Grafana                         |
| Logging      | ELK Stack (Elasticsearch, Logstash, Kibana) |
| Tracing      | Jaeger, Zipkin                              |
| Deployment   | Docker, Kubernetes, Helm                    |

*High Availability in microservices
High availability systems are designed to provide continuous and uninterrupted service to the end customer by using redundant software performing similar functions. In highly available microservices, all the hosts must point to the same storage. So, in case of failure of one host, the workload in one host can failover to another host without downtime. The redundant software can be installed in another virtual machine (VM), or Kubernetes clusters in multicloud or hybrid cloud.

* why we need high availability in microservices?
Organizations today follow service-oriented architecture approaches, using microservices architectures to build distributed systems that span multiple workloads or multiple clouds. One of the main challenges of microservices is the way services communicate over the network using the API.

Communication between these services in a distributed system can fail due to many reasons, which include:

1.Unreliable network
2.High latency / slow speed
3.Limited bandwidth
4.Insecure network
5.Changing topology
6.Internal and external security threats
7.High transport costs
8.Heterogeneous network



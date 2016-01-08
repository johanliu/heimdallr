#A key-value store for shared configuration and service discovery

###Functionality:
- kv storage with pub/sub  (consul K-V, etcd K-V, redis)
- networking layer (serf: gossip protocol, membership)
- raft consensus algorithm implementation (consul, etcd, raft implementation)

###Flagship:
- etcd
- zookeeper
- consul

###Reference:
- Introduction to Reliable and Secure Distributed Programming
- Distributed Systems Concepts and Design
- SWIM: Scalable Weakly-consistent Infection-style Process Group Membership Protocol
- In Search of an Understandable Consensus Algorithm

###Website:
- https://raft.github.io/
- https://en.wikipedia.org/wiki/Gossip_protocol
- https://github.com/hashicorp/serf
- https://github.com/hashicorp/memberlist
- https://github.com/bpot/node-gossip
- https://en.wikipedia.org/wiki/Lamport_timestamps
- https://github.com/antirez/redis

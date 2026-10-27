# Systems Engineering Glossary: Distributed In-Memory Cache Cluster

### Consistent Hashing
Hashing technique minimizing key redistribution when cluster nodes join or depart.

### Virtual Nodes (vnodes)
Multiple hash-ring entry points per physical node ensuring uniform data distribution across heterogeneous servers.

### LRU Eviction
Least Recently Used policy discarding inactive memory keys when total cache capacity is saturated.

### Read-Through Cache
Caching pattern where cache interceptor fetches missing records directly from source storage and populates memory.

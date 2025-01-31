# vagrant_ubuntu_redis
Redis cluster based on Ubuntu

A four node redis cluster with one primary and three replicas

Ports for each node are forwarded to the host system with the following format
The primary node 5<redis base port> so 56379, each worker is one number higher.

As such the first worker can be accessed at localhost:56380
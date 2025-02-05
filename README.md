# multiraft
Multi raft implementation of etcd raft 🚄

This is a sharded implementation of etcd raft. Every shard(and their replicas) will be distributed across the physical nodes so that all the nodes have a few of the shard leaders. This way the decision making is not fully concentrated on one physical node.

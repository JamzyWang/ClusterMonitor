# ClusterMonitor

---

This project is used to monitor the redis cluster state.

## Usage 
- add monitor server 
```
  add.sh "127.0.0.1 6379"
```
## Monitor Parameters

- static state
- 
% keyspace_hits

% expired_keys

% multiplexing_api

% total_commands_processed

% redis_version

% used_cpu_user_children

% used_cpu_sys_children

% mem_allocator

% connected_slaves

% aof_enabled

% used_memory_rss

% connected_clients

% redis_git_sha1

% rdb_last_save_time

% keyspace_misses

% used_memory

% used_memory_peak

% used_memory_lua

% process_id

% tcp_port

% mem_fragmentation_ratio

% run_id

% os

% total_connections_received

% arch_bits

% role

% gcc_version

% used_cpu_user

% used_cpu_sys

% uptime_in_seconds

% ALL

% uptime_in_days


- dynamic static

% total_commands_processed

% last_save_time

% uptime_in_seconds

% used_memory_peak

% keyspace_hits

% keyspace_misses

% expired_keys

% connected_slaves

% mem_fragmentation_ratio% uptime_in_days

% total_connections_received

% used_cpu_user

% used_cpu_sys

% used_memory

% used_memory_rss


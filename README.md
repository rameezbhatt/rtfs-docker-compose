# Distributed Network System

This project provides a Docker Compose setup for running a distributed system with multiple components:
- Multiple Redis nodes in a cluster configuration
- Multiple blockchain nodes
- Network filesystem

## Prerequisites

- Docker
- Docker Compose

## System Components

### Redis Cluster
The system includes multiple Redis nodes configured in a cluster mode:
- Node configurations in `configure/2000/redis.conf`, `configure/2002/redis.conf`
- Additional Redis configurations available

### Blockchain Nodes
Multiple blockchain nodes running in parallel:
- Node 1 configuration in `configure/node1/config.env`
- Node 2 configuration in `configure/node2/config.env`

### Network Filesystem
Distributed filesystem configuration available in `configure/fs/settings.toml`

## Getting Started

1. Clone this repository:
```bash
git clone

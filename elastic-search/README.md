# ElasticSearch Orchestration

## Prerequisite

- Docker with sudo permission

## Installation Guide

- Copy this directory into another directory
- Delete `.gitkeep` file in `data` directory
- Increase the VM Max Map Count in sysctl
    ```bash
    sudo sysctl -w vm.max_map_count=262144
    sudo sysctl -p
    ```
- Run `docker compose up`

## Reference

- [System Requirements](https://www.elastic.co/guide/en/elasticsearch/reference/8.18/docker.html#_start_a_single_node_cluster)
- [Documentation](https://www.elastic.co/docs/)
- [Docker Images](https://hub.docker.com/_/elasticsearch)
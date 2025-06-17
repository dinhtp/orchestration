# OpenSearch Orchestration

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

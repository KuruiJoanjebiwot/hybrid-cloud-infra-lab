# Enterprise Hybrid Infrastructure Lab

## Overview
An end-to-end infrastructure lab demonstrating automated system provisioning, containerized service orchestration, Active Directory identity management, and real-time infrastructure monitoring.

## System Topology
* **Active Directory Domain Controller:** `win-dc01` (`192.168.10.10`)
* **Linux Infrastructure Node:** `ubuntu-node01` (`192.168.10.20`)
* **Core Subnet:** `192.168.10.0/24`

##  Key Modules
1. **Automation:** Ansible playbooks for automated host configuration and patching.
2. **Services:** Docker Compose stacks running application services and monitoring agents.
3. **Observability:** Centralized Zabbix 6.4 LTS server with MySQL backend for host metrics.
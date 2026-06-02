# Ansible Operations Lab

This repository contains practical Ansible automation scenarios for Linux server administration and operational tasks.

## Objective

The goal of this repository is to demonstrate common infrastructure automation tasks using Ansible, including service management, package upgrades, and server maintenance activities.

## Scenarios

| Scenario | Description |
|-----------|-------------|
| Service Restart | Restart services across multiple Linux servers |
| Package Upgrade | Upgrade installed packages on multiple servers |
| Reboot and Health Check | Reboot servers and verify connectivity after restart |

## Technologies

- Ansible
- Linux
- SSH
- YAML
- Systemd

## Skills Demonstrated

- Infrastructure Automation
- Linux Administration
- Service Management
- Package Management
- Server Maintenance
- Configuration Management
- Operational Procedures
- Automation Best Practices

## Repository Structure

```text
ansible-operations-lab/
├── README.md
├── inventory/
│   └── hosts.ini
├── service-restart/
│   └── restart-service.yml
├── package-upgrade/
│   └── upgrade-packages.yml
└── reboot-check/
    └── reboot-and-check.yml
```

## Example Execution

Restart service:

```bash
ansible-playbook -i inventory/hosts.ini service-restart/restart-service.yml
```

Upgrade packages:

```bash
ansible-playbook -i inventory/hosts.ini package-upgrade/upgrade-packages.yml
```

Reboot and verify:

```bash
ansible-playbook -i inventory/hosts.ini reboot-check/reboot-and-check.yml
```

## Disclaimer

All examples are based on lab environments and do not contain any customer, production, or proprietary information.
```

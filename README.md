# RHV Based Ansible Demo

This repo holds playbooks and role pointers to the following demo scenarios:

## RHV VM Manipulation

```ini
rhv-vm-create.yml - Creation of VM, snapshot and tag
rhv-vm-remove.yml - Remove VM
rhv-vm-tag.yml - Assign production tag
```

## RHEL data gathering

```ini
rhel-package-info.yml - Gather data about packages using AAP Controller Survey
rhel-service-info.yml - Gather data about services using AAP Controller Survey
```

## Aplication Installation

```ini
app-vm-prepare.yml - Preparation steps: Satellite server registration, epel repo configuration, host name setting
app-install.yml - App stack installation using deffined roles
```

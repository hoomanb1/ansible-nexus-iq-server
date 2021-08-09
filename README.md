# Nexus IQ Server Ansible roles

An ansible role for installing and managing [Nexus IQ Server](https://help.sonatype.com/iqserver). The role installs IQ Server on Unix based platforms.

## Example playbooks

```
---
- hosts: home-pc
  become: yes
  roles:
    - nexus-iq-server
```

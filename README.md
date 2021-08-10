# Nexus IQ Server ansible role

An ansible role for installing and managing [Nexus IQ Server](https://help.sonatype.com/iqserver). The role installs IQ Server on Unix based platforms.

## Example playbooks

```
---
- hosts: iq-box
  become: yes
  roles:
    - nexus-iq-server
```

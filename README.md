# Sonarqube

## Description

Sonarqube self-hosted instance with PostgreSQL database.

![Build Status](https://assets-eu-01.kc-usercontent.com/7d02f42d-b848-0130-e02b-f4db2668945c/0fd3b035-aee8-4039-8a76-f77e93a2b11d/SQ-instance-components.png?w=924&h=451&auto=format&fit=crop)

## Host configurations

Run following command as root

```sh
sysctl -w vm.max_map_count=524288
sysctl -w fs.file-max=131072
ulimit -n 131072
ulimit -u 8192
```

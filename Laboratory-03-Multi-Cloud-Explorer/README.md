# Laboratory 03 – Multi-Cloud Explorer

## Mission Overview

This laboratory activity explores AWS, Microsoft Azure, and Google Cloud Platform. The goal is to compare their cloud services, infrastructure, advantages, and possible applications for different business requirements.

## Cloud Platforms Explored

* Amazon Web Services (AWS)
* Microsoft Azure
* Google Cloud Platform (GCP)

## Linux Investigation

A Linux environment was launched using KillerCoda to investigate basic server information.

### Operating System

Command used:

```bash
cat /etc/os-release
```

The command was used to identify the Linux distribution and version.

## Terminal Output

<img width="773" height="318" alt="killercoda-terminal1" src="https://github.com/user-attachments/assets/53d4d0bf-b0fe-4af1-a4cf-b5316cfa6e9a" />


### CPU Information

Command used:

```bash
lscpu
```

The command was used to identify the processor and CPU configuration.

## Terminal Output 

<img width="1336" height="804" alt="killercoda-terminal2" src="https://github.com/user-attachments/assets/ffb200d2-e404-4a95-b0ba-0db9bc10b974" />


### Memory

Command used:

```bash
free -h
```

The command was used to identify the total and available memory.

## Terminal Output

<img width="1056" height="104" alt="killercoda-terminal3" src="https://github.com/user-attachments/assets/88386d0a-c2b2-40ff-89f8-30aab0b8b344" />


### Disk Space

Command used:

```bash
df -h /
```

The command was used to identify the available disk space.

## Terminal Output

<img width="1329" height="184" alt="killercoda-terminal4" src="https://github.com/user-attachments/assets/242bb361-f442-42b4-9282-605f5d39bbe9" />


## Cloud Services That Could Host the Linux Server

If the Linux server were migrated to the cloud, it could be hosted using the following services:

| Cloud Provider  | Service                |
| --------------- | ---------------------- |
| AWS             | Amazon EC2             |
| Microsoft Azure | Azure Virtual Machines |
| Google Cloud    | Compute Engine         |

These services provide virtual machines where Linux operating systems can be deployed and managed.


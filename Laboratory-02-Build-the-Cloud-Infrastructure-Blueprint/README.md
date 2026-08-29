# CCM101 – Cloud Computing Laboratory Activities

## Mission Overview

This laboratory activity focuses on learning the basic concepts of cloud computing and understanding the different components of cloud infrastructure. Using the KillerCoda Linux environment, the activities involved investigating a cloud server, identifying its infrastructure components, comparing major cloud providers, and designing a simple cloud infrastructure.

The laboratory activities helped me understand how compute, storage, networking, and operating systems work together in a cloud environment.

## Objectives

The objectives of this laboratory activity are:

- To investigate and identify the resources available in a Linux cloud server.
- To understand the basic components of cloud infrastructure.
- To identify compute, storage, networking, and operating system resources.
- To compare the core infrastructure services of AWS, Microsoft Azure, and Google Cloud Platform.
- To understand the equivalent services offered by different cloud providers.
- To design a simple cloud infrastructure diagram.
- To practice using Linux commands for checking system information.

## Cloud Infrastructure Components

The following cloud infrastructure components were identified in the KillerCoda Linux environment:

### Compute Resources

The compute resources include the CPU and RAM used to process commands, run applications, and perform tasks.

- **CPU Model:** Intel Xeon E312xx
- **CPU Cores:** 1
- **Total RAM:** 1.9 GiB

### Storage Resources

Storage resources are used to store the operating system, applications, and other files.

- **Main Disk:** `/dev/vda1`
- **Disk Capacity:** 19 GB
- **Main Mount Point:** `/`
- Other mounted file systems include `/boot`, `/boot/efi`, `/run`, and `/dev/shm`.

### Networking Resources

Networking resources allow the cloud server to communicate with other systems and networks.

- **Hostname:** `ubuntu`
- **IP Addresses:** `172.30.1.2` and `172.17.0.1`

### Operating System

The operating system manages the server's resources and allows users to run commands and applications.

- **Operating System:** Ubuntu 24.04.4 LTS
- **Codename:** Noble Numbat
- **Kernel Version:** 6.8.0-138-generic

## Tools Used

The following tools were used during the laboratory activities:

- **KillerCoda** – Used as the Linux cloud environment.
- **Ubuntu Linux** – Used as the operating system for investigating cloud infrastructure.
- **Linux Terminal** – Used to execute commands and check system information.
- **GitHub** – Used to store and manage the laboratory documentation.
- **Markdown** – Used to create and format the documentation files.
- **Diagramming Tool** – Used to create the simple cloud infrastructure diagram.

## Linux Commands Executed

| Command | Purpose |
|---|---|
| `cat /etc/os-release` | Checks the operating system |
| `uname -r` | Checks the kernel version |
| `lscpu` | Checks CPU information |
| `nproc` | Checks the number of CPU cores |
| `free -h` | Checks RAM and memory |
| `df -h` | Checks disk space |
| `findmnt` | Checks mounted file systems |
| `hostname` | Checks the system hostname |
| `hostname -I` | Checks the IP address |
| `ip addr` | Checks network information |

## Skills Learned

Through these laboratory activities, I learned the following skills:
- Basic Linux command usage.
- How to check operating system and kernel information.
- How to identify CPU, memory, and storage resources.
- How to check mounted file systems.
- How to identify a server's hostname and IP address.
- Understanding the basic components of cloud infrastructure.
- Comparing cloud services from AWS, Microsoft Azure, and Google Cloud Platform.
- Understanding compute, storage, networking, and IAM services.
- Creating a simple cloud infrastructure diagram.
- Writing technical documentation using Markdown.
- Organizing laboratory files in a GitHub repository.

## Challenges Encountered

One challenge encountered during the activity was remembering the correct Linux commands for checking different system information. There was also an error when typing `hostanme -I` instead of `hostname -I`, which resulted in a command not found message.

Another challenge was understanding how cloud infrastructure components work together and how AWS, Microsoft Azure, and Google Cloud Platform use different names for similar services. These challenges were solved by checking the command outputs carefully, correcting errors, and comparing the services based on their purpose.

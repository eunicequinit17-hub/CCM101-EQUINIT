# Checkpoint 3 – Identify Cloud Infrastructure Components

## 1. Compute Resources

### Example Found in the Linux Environment

- **CPU Model:** Intel Xeon E312xx (Sandy Bridge, IBRS update)
- **Number of CPU Cores:** 1
- **Total RAM:** 1.9 GiB

### Purpose

Compute resources provide the processing power and memory needed to run programs, applications, and services. The CPU processes instructions, while RAM temporarily stores data that is currently being used by the system.

### Importance in Cloud Computing

Compute resources are important because cloud servers need processing power and memory to run applications and perform different tasks. Cloud computing allows users to use computing resources without needing to own or manage the physical hardware.

### Relation to the KillerCoda Linux Environment

In the KillerCoda Linux environment, the server uses an **Intel Xeon E312xx** CPU with **1 CPU core** and **1.9 GiB of RAM**. These resources allow the Ubuntu server to run Linux commands, processes, and applications.

---

## 2. Storage Resources

### Example Found in the Linux Environment

- **Main Disk:** `/dev/vda1`
- **Disk Capacity:** 19 GB
- **Used Space:** 5.4 GB
- **Available Space:** 13 GB
- **Main Mount Point:** `/`

Other mounted storage resources include:

- `/boot`
- `/boot/efi`
- `/run`
- `/dev/shm`
- `/run/lock`

### Purpose

Storage resources are used to save the operating system, applications, files, and other data. They provide space where information can be stored and accessed when needed.

### Importance in Cloud Computing

Storage is important in cloud computing because applications and users need a place to store data. Cloud servers use storage resources to keep the operating system, application files, databases, and other important information.

### Relation to the KillerCoda Linux Environment

In the KillerCoda Linux environment, the main storage device is **`/dev/vda1`**, which has a total capacity of **19 GB** and is mounted on the root directory **`/`**. The system also has separate mounted file systems for **`/boot`** and **`/boot/efi`**.

---

## 3. Networking Resources

### Example Found in the Linux Environment

- **Hostname:** `ubuntu`
- **IP Addresses:** `172.30.1.2` and `172.17.0.1`

### Purpose

Networking resources allow a server to communicate with other computers, services, and networks. IP addresses are used to identify the server and allow data to be sent and received.

### Importance in Cloud Computing

Networking is important because cloud computing depends on communication between users, servers, applications, and other cloud services. Without networking, users would not be able to access cloud-based applications and resources.

### Relation to the KillerCoda Linux Environment

In the KillerCoda Linux environment, the hostname is **`ubuntu`**. The system has the IP addresses **`172.30.1.2`** and **`172.17.0.1`**, which allow the environment to communicate within its network.

---

## 4. Operating System

### Example Found in the Linux Environment

- **Operating System:** Ubuntu 24.04.4 LTS
- **Version Codename:** Noble Numbat
- **Kernel Version:** 6.8.0-138-generic

### Purpose

The operating system manages the hardware and software resources of the server. It provides an environment where users can run commands, applications, and services.

### Importance in Cloud Computing

The operating system is important because it manages the cloud server's resources, such as the CPU, memory, storage, and networking. It also allows applications and services to run properly on the server.

### Relation to the KillerCoda Linux Environment

The KillerCoda environment is running **Ubuntu 24.04.4 LTS (Noble Numbat)** with kernel version **6.8.0-138-generic**. Ubuntu manages the available compute, storage, and networking resources and provides the Linux terminal where commands can be executed.

---

# CCM101 Cloud Computing

## Laboratory Activity 1 – Mission 1: Introduction to the Cloud

### Overview

This laboratory activity helped me learn the basic skills needed in cloud computing. I practiced using a Linux environment, managing files and folders, checking system information, and creating a GitHub portfolio for my activities.

## Objectives

After completing this activity, I was able to:

- Access an Ubuntu Linux environment using KillerCoda.
- Use and explore the Linux terminal.
- Create a new Linux user account.
- Set up the user with a Bash shell and home directory.
- Give the user `sudo` privileges.
- Log in using the newly created account.
- Check the username, current directory, and hostname.

---

# Checkpoint 1 – Enter the Cloud

In this activity, I learned how to use a basic Linux environment for cloud computing. I accessed an Ubuntu Linux playground through KillerCoda and created a Linux user account named **equinit**. I also set up the Bash shell and home directory and gave the account `sudo` access. After that, I used Linux commands to check my username, current directory, and hostname.

### User Information

| Information | Result |
|---|---|
| Username | equinit |
| Working Directory | `/home/equinit` |
| Hostname | `[Your Hostname]` |

---

## Mission Tasks

### 1. Access the Linux Playground

I accessed the Linux Playground using **KillerCoda** and selected **Ubuntu 24.04** or the latest available Ubuntu version.

**KillerCoda Playground:**  
https://killercoda.com/playgrounds

---

### 2. Commands Used

After opening the playground, I checked if the Linux terminal was working properly. I used the following commands to create and access my user account and check the system information.

```bash
sudo adduser equinit
sudo usermod -aG sudo equinit
su - equinit

whoami
pwd

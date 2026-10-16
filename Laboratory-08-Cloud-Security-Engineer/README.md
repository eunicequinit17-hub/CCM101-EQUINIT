# Laboratory 08 - Cloud Security Engineer

## Mission Overview

This laboratory focuses on securing an Ubuntu server using UFW, managing network ports, and protecting a web application.

## Objectives

- Understand the Principle of Least Privilege.
- Identify the attack surface of a server.
- Configure a Default Deny firewall policy.
- Allow SSH and HTTP application traffic on port 8080.
- Document security configurations using Markdown.

## Commands Executed

```bash
docker --version
docker run -d --name secure-web-app -p 8080:80 nginx
docker ps
curl http://localhost:8080
sudo ufw status verbose
sudo ufw allow ssh
sudo ufw default deny incoming
sudo ufw default allow outgoing
sudo ufw enable
sudo ufw allow 8080/tcp
sudo ufw status numbered
```

## Skills Learned

I learned how to deploy an Nginx container, test a web application, configure UFW firewall rules, and document basic cloud security practices.

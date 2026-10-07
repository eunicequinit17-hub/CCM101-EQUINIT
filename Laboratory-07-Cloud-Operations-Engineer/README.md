# Laboratory 07 - Cloud Operations Engineer

## Mission Overview

This laboratory focuses on monitoring a Linux server and a containerized Nginx web application. The activity demonstrates how system resources, application logs, and container metrics can be used to check application health.

## Objectives

- Monitor CPU, memory, and disk resources.
- Deploy an Nginx web container.
- Generate HTTP requests and an intentional 404 error.
- Analyze application logs.
- Monitor container CPU and memory usage.
- Document the results using Markdown.

## Monitoring Commands Executed

```bash
free -h
df -h /
top
docker run -d --name client-website -p 8080:80 nginx
docker ps
curl http://localhost:8080
curl http://localhost:8080/hidden-admin-page
docker logs client-website
docker stats
```

## Skills Learned

Through this laboratory, I learned how to monitor Linux system resources, deploy a Docker container, generate web traffic, inspect application logs, and monitor container resource usage.

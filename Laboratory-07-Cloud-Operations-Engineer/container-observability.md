# Container Observability

## Application Logs

The 404 log entry recorded from the container is:
```bash
172.17.0.1 - - [07/Oct/2026:03:10:12 +0000] "GET /hidden-admin-page HTTP/1.1" 404 153 "-" "curl/8.5.0" "-"
2026/10/07 03:10:12 [error] 29#29: *4 open() "/usr/share/nginx/html/hidden-admin-page" failed (2:]
```

Application logs are important because they show what requests and errors are happening inside an application. They help Cloud Operations Engineers identify problems and troubleshoot issues using actual events instead of guessing.

## Real-Time Container Metrics

The `client-website` container was monitored using `docker stats`.

* CPU Usage: **0.00%**
* Memory Usage: **2.746 MiB / 1.859 GiB**
* Network I/O: **3.73 kB / 5.25 kB**

These metrics show the current resource consumption of the container while it is running.

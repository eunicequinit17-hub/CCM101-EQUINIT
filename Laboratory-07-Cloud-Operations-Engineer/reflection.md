# Mission Reflection

This laboratory activity helped me understand why monitoring is important in cloud operations. Before this activity, I mostly focused on making sure that an application was running. I learned that a Cloud Operations Engineer also needs to check the health and performance of the server.

First, checking the host server is important even when containers are running because the host provides the CPU, memory, and storage needed by the containers. If these resources become limited, the application may become slow or stop working.

The `docker logs` command is also useful when troubleshooting problems such as login issues. It can show requests, errors, and other events happening inside the application container. By checking the logs, I can find useful information instead of simply guessing what caused the problem.

I also learned that logs and metrics provide different types of information. Logs show specific events and requests that happened in the application, while metrics show numerical information such as CPU and memory usage.

For large companies, monitoring thousands of containers would require automated monitoring tools such as Prometheus and Grafana. These tools can collect and display information from many systems in one place.

This activity improved my Linux troubleshooting skills. I became more familiar with commands such as `free`, `df`, `top`, `docker logs`, and `docker stats`. I learned that troubleshooting should be based on actual evidence from system metrics and logs instead of guessing.

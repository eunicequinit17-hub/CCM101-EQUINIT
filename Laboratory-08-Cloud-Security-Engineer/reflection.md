
# Mission Reflection

Completing Mission 8 helped me understand why cloud security is important when managing servers and web applications. A host-based firewall protects a server by controlling incoming and outgoing network traffic directly on the machine. Even if the physical network perimeter is breached, the firewall can still block connections that are not permitted by its rules. This provides another layer of protection against unauthorized access.

Managing open network ports is also important because every exposed service can become a possible entry point for attackers. By allowing only the ports needed by the application, administrators can reduce the server's attack surface. In this activity, I allowed SSH for remote administration and TCP port 8080 for the Nginx web application. These rules demonstrate how a firewall can restrict access to necessary services.

Leaving a database port, such as MySQL port 3306, open to the public internet can be dangerous. Attackers may attempt password guessing, exploit software vulnerabilities, or access sensitive information if the database is poorly secured. In an enterprise environment, database access should be restricted to trusted application servers or authorized networks. Strong authentication, regular updates, and appropriate access permissions are also necessary.

This mission changed my perspective on how easily a server can become exposed when security settings are ignored. Running an application is not enough; administrators must also check network access, configure firewall rules, and verify that their security measures are working as intended. I also learned that allowing SSH before enabling a firewall helps prevent losing remote access.

My GitHub portfolio now represents my progress through eight cloud computing missions. Each laboratory activity has helped me develop practical skills in server management, deployment, monitoring, and security. Organizing the documentation and screenshots also helps me present my work clearly. Moving forward, I want to improve my understanding of network security and apply these practices whenever I deploy cloud applications.

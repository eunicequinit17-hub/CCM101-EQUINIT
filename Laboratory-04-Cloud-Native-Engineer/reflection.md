# Mission 4 – Mission Reflection

This laboratory activity helped me understand how Docker containers are different from Virtual Machines. A Docker container can start within seconds because it does not need to boot a complete operating system like a Virtual Machine. Instead, containers share the host operating system kernel, which makes them lighter and faster to deploy. In comparison, installing and starting a Virtual Machine requires more time because it needs its own guest operating system and allocated resources.

I also learned why port mapping is important when running a web server inside a container. The command `-p 8080:80` connects port 8080 of the host machine to port 80 inside the container. Without this mapping, the Nginx web server running inside the container may not be accessible through the host's port. Using port mapping allowed me to access the Nginx server through `http://localhost:8080`.

Another thing I learned was what happens when using the `docker rm` command. The command removes the stopped container from Docker. Any data stored only inside the writable layer of that container can be lost when the container is removed, which shows why persistent data should be stored using volumes or other storage solutions when necessary.

Containerization can also improve the way developers and IT operations teams work together. Developers can package an application and its dependencies into a container, while operations teams can run the same container in different environments. This helps reduce problems caused by differences between development, testing, and production environments and supports the DevOps approach.

My GitHub Cloud Computing portfolio is also becoming more organized as I complete each laboratory activity. In this mission, I added research about containers, Docker commands, deployment documentation, screenshots, and a reflection. This makes my portfolio a better record of the skills and knowledge I am gaining in cloud computing.

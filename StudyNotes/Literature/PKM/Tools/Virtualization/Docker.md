---
software: Virtualization Software
website: https://www.docker.com/
github_repo: https://github.com/moby/buildkit
---

Docker is not considered a traditional virtualization software, but rather a containerization platform. While it shares some similarities with virtualization, such as isolating applications and providing an environment to run them, there are key differences between [[Docker]] and [[virtual machine]]s.

In traditional virtualization, a hypervisor is used to create and manage multiple virtual machines on top of a host operating system. Each virtual machine runs its own instance of the operating system and consumes system resources independently. This approach can be resource-intensive as each virtual machine requires memory, storage, and CPU cycles.

On the other hand, Docker uses containerization technology to package applications along with their dependencies into containers. These containers share the host operating system's kernel but are isolated from each other. Unlike virtual machines, containers do not require a separate operating system installation for each instance, resulting in more efficient resource utilization.

Docker containers are lightweight and portable. They encapsulate all the necessary components to run an application, including libraries, binaries, and configuration files. This allows applications to be easily deployed across different environments without worrying about compatibility issues.

Additionally, Docker provides tools for managing containerized applications at scale. It offers features like container orchestration (using tools like [[Kubernetes]] or Docker Swarm) to automate the deployment, scaling, and management of containers across multiple hosts.

Overall, while Docker may not be a traditional virtualization software like VMware or VirtualBox that creates full-fledged virtual machines, it provides a lightweight and efficient alternative through containerization technology.
# SoftwareLab07

# Questions
## Q1
* **Docker Image**: A Docker image is a portable, executable package that contains all the necessary code and dependencies to run a specific application or service. It is built from a Dockerfile. Docker Image is the resulting executable package created from a Dockerfile.
* **Dockerfile**: A Dockerfile is a text file that contains instructions for building a Docker image. It specifies the base image, commands to execute, and other settings necessary for creating a custom image. Dockerfile defines the instructions for building an image.
* **Docker Container**: A Docker container is a running instance of a Docker image. It is an isolated and lightweight virtualization environment that provides resources for the application to execute. Each container has its own isolated filesystem, network, and processes. A Docker Container is a running instance of an image that provides an isolated environment for an application.

## Q2
Kubernetes is an open-source container orchestration system for automating the deployment, management, and scaling of containerized applications. It provides a platform for managing a cluster of containers and ensuring that they run reliably and efficiently. Kubernetes is closely related to Docker in the following ways:

* Kubernetes uses Docker as the default container runtime. It can manage and orchestrate Docker containers, as well as containers from other compatible runtimes such as containerd and CRI-O.
* Kubernetes provides advanced features for managing and orchestrating containers, such as:
    * Pod Management: Grouping related containers into logical units called Pods.
    * Service Discovery: Exposing containerized applications as services and handling load balancing.
    * Autoscaling: Automatically adjusting the number of container replicas based on demand.
    * Health Monitoring: Monitoring container health and automatically restarting failed containers.
* Integration: Kubernetes integrates seamlessly with Docker, allowing you to easily deploy and manage Docker containers in a production environment.

Using Kubernetes with Docker offers several benefits:

* Simplified Deployment: Kubernetes simplifies the deployment and management of complex containerized applications.
* Increased Reliability: Kubernetes ensures high availability and reliability by automatically restarting failed containers and managing resource allocation.
* Scalability: Kubernetes enables automatic scaling of containerized applications based on demand, improving performance and efficiency.
* Enhanced Security: Kubernetes provides security features such as role-based access control (RBAC) and network isolation, protecting containerized applications from vulnerabilities.

# Docker <img src="Images/docker_logo.png" alt="git logo" width= 50 height=50>

**Docker** is an open platform for developing, shipping, and running applications that allow you to separate these
applications from your infrastructure so software can be delivered quickly.

The Docker platform has two distinct components: the **Docker Engine** (which is responsible for *creating and running
containers*); and the **Docker Hub** (a cloud service for *distributing containers*).

## Brief History

* **2001**: SWsoft (now Parallels, Inc.) released the commercial Virtuozzo container technology for Linux.
* **2008**: The Linux Containers (LXC) project started and brought together CGroups, kernel namespaces, and chroot
  technology (among others) to provide a complete containerization solution.
* **2013**: Docker brought the final pieces to the containerization puzzle, and the technology began to enter the
  mainstream.

## How to install/use

Download instructions are here: **[docker.com.](https://www.docker.com/products/docker-desktop)**

Once you have Docker installed, open up a command prompt and run:

    docker run -d -p 80:80 docker/getting-started

When you open the dashboard, you will see this page. The container name(jolly_bouman) is a randomly created name.

![Docker dashboard](Images/Docker_dashboard.png)

If you prefer a video tutorial, please click below:

[![Get started with Docker](http://img.youtube.com/vi/iqqDU2crIEQ/0.jpg)](https://www.youtube.com/watch?v=iqqDU2crIEQ "Docker")

## How Docker improves productivity

Developing apps today requires so much more than writing code, including multiple languages, frameworks, and
architectures.

Docker simplifies and accelerates your workflow. It introduced the industry standard for **containers**, which allow
developers to isolate their app from its environment. You do not have to work about the *"does it works on my machine?"*
problem anymore.

Docker offers *fast and consistent delivery* of your applications using containers that provide your application and
services.

Docker containers can run on a developer’s local laptop, on physical or virtual machines in a data center, on cloud
providers, or in a *mixture of environments*.

Docker also provides a *viable, cost-effective alternative* to hypervisor-based virtual machines. It is perfect for high
density environments and for small and medium deployments where you need to do more with fewer resources.

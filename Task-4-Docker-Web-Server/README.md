\# Task 4 – Web Server using Docker



\## Objective

To deploy and manage a web server using Docker containerization.



\## Tools Used

\- Docker Desktop

\- Nginx

\- Windows OS



\## Steps Performed

1\. Installed Docker Desktop and configured WSL 2.

2\. Pulled the official Nginx image from Docker Hub.

3\. Ran the Nginx container with port mapping.

4\. Accessed the web server using http://localhost:8080.



\## Docker Commands Used

```bash

docker pull nginx

docker run -d -p 8080:80 --name mywebserver nginx

docker ps




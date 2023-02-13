# kubernetes-practice

In this project, I learned how to deploy a web application using Kubernetes. I used minikube to set up a K8 cluster locally, and used kubectl to interact with the API server.

![image](https://user-images.githubusercontent.com/113411149/218372398-2241a84c-8308-4bf7-b8d5-d5a0d2538cac.png)

In the screenshot above, I have two pods, services, and deployments. In terms of deploying the web app with a MySQL DB, I have:
- set up the MySQL docker
- set up a basic MySQL table (see below)

![image](https://user-images.githubusercontent.com/113411149/218371966-cc1d3e1b-b100-4ad0-aca4-511650164835.png)

**My next step will be to figure out how to link the cluster to my database and display the table on my web application.**

Here is what the web application looks like:

![image](https://user-images.githubusercontent.com/113411149/218372321-df11f876-9741-410a-8e14-7ef78606ca89.png)

This web application came from Docker's "getting-started" github example: https://github.com/docker/getting-started.git. 
I added a h1 element to customize it, then contanarized the application into a Docker image (see below).

![image](https://user-images.githubusercontent.com/113411149/218374220-be6de957-70f8-473e-9742-b762154565d9.png)

:)

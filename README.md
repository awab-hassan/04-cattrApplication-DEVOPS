# Project #4 - Cattr deployment.

Project Type: Application Dockerization and Deployment on Kubernetes cluster.

Project Description: The client asked me to deploy Cattr application on kubernetes cluster, MYSQL database should be connected to application. Configuration of Persistent volumes and persistent volume claims to store data, allocate 5gb memory to each volume.

Solution:
- I deployed PersistentVolume using NFS for Postgress Database.
- I deployed PersistentVolumeClaims for Postgress Database.
- I deployed Postgress Database Deployment and Service.
- I deployed Cattr Application's Deployment and Service.

![1dc19a7475d247cebca3350d1834b201](https://github.com/awab-hassan/04-cattrApplication-DEVOPS/assets/90965012/1c5b306a-cb1a-496e-aebd-87d3161f8ac9)

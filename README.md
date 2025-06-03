# WordPress on AWS ECS

WordPress website on Amazon ECS (Elastic Container Service). The deployment is scalable, containerized, and ready for production workloads.

# Overview
Platform: Amazon ECS (Fargate)

CMS: WordPress

Database: Amazon RDS MYSQL

Storage: Amazon EFS

Networking: AWS Application Load Balancer

# Deployment Steps
### 1. Create ECS Cluster
A cluster is a logical grouping of resources—like EC2 instances or Fargate tasks—where your containers run. It helps manage and isolate workloads within a specific environment. 
### 2. Create Task Definition
A task definition is like a recipe that tells ECS how to run your container.
### 3. Launch ECS Service
### 4. Set up Application Load Balancer
### 5. Configure MYSQL
### 6. Set environment variables in ECS Task:

`WORDPRESS_DB_HOST`

`WORDPRESS_DB_USER`

`WORDPRESS_DB_PASSWORD`

`WORDPRESS_DB_NAME`

#  Maintenance & Updates
Redeploy updated containers by registering new task definitions

Monitor logs via CloudWatch

Backup RDS or volumes regularly

# Screenshots

### Cluster
![image](https://github.com/user-attachments/assets/ff2ffab3-ae47-4dd5-af7f-253a357b83fa)


### Task Defination
![image](https://github.com/user-attachments/assets/965440eb-1148-4752-8398-54a72d52968b)


![image](https://github.com/user-attachments/assets/7aa2954e-aac6-49c6-8bc2-f06973ae29f5)


### Database
![image](https://github.com/user-attachments/assets/6ef5d605-e160-4bba-8dc7-df20dfa49b3d)


### Webpage
![image](https://github.com/user-attachments/assets/235642e5-0d07-4405-9c31-da34634c39ea)


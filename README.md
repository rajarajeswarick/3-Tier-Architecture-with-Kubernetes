# 3-Tier-Architecture-with-Kubernetes
This repository has the sample 3-Tier Architecture with Kubernetes

3-Tier Architecture with Kubernetes
<img width="821" height="728" alt="image" src="https://github.com/user-attachments/assets/0578fe82-9dfe-4c28-b402-8ff7e1085e6c" />
In this Architecture the webserver application and Appserver applications will be running in containers within pods.
To make the pods Highly Available, Run the Appserver and webserver pods in two different Availability Zones.
Make the pods scalable using Kubernetes Scaling constructs replicaset(rs), horizontal pod autoscaler (hpa) and Cluster autoscaler.
These pods acn be run with in EC2 worker node under Elastic Kubernetes Service (EKS) or as Fargate.
Webserver fronting Load Balancer can be ALB Ingress.
Appserver fronting Loadbalancer can be ALB Ingress or Kubenetes service.
Database - Aurora

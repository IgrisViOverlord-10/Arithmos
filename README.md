# 🌐 Arithmos – Cloud Calculator Application

Developed and deployed a dynamic Django calculator web application on AWS using Application Load Balancer (ALB) and Auto Scaling Group (ASG) to demonstrate high availability, fault tolerance, and scalable cloud infrastructure.
Incoming traffic is distributed across multiple EC2 instances, while unhealthy instances are automatically replaced through Auto Scaling health checks, ensuring improved reliability and uptime.

---

## 🚀 Tech Stack

[![AWS](https://img.shields.io/badge/AWS-EC2-FF9900?logo=amazonaws&logoColor=white)](https://aws.amazon.com/ec2/)
[![ALB](https://img.shields.io/badge/AWS-Application_Load_Balancer-FF9900?logo=amazonaws&logoColor=white)](https://aws.amazon.com/elasticloadbalancing/)
[![ASG](https://img.shields.io/badge/AWS-Auto_Scaling-FF9900?logo=amazonaws&logoColor=white)](https://aws.amazon.com/autoscaling/)
[![Ubuntu](https://img.shields.io/badge/Ubuntu-22.04-E95420?logo=ubuntu&logoColor=white)](https://ubuntu.com/)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)](https://www.djangoproject.com/)
[![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?logo=gunicorn&logoColor=white)](https://gunicorn.org/)
[![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white)](https://nginx.org/)

---

## 🏗 Architecture Diagram

<p align="center">
  <img src="Architecture.png" alt="Architecture Diagram">
</p>

<p align="center">
  Architecture above illustrates a scalable AWS deployment workflow using ALB, Auto Scaling Group (ASG), Launch Templates, and multiple EC2 instances running Nginx, Gunicorn, and Django.
</p>

---

## ⚙️ Deployment Highlights

- Configured scalable AWS deployment with ALB and Auto Scaling
- Deployed Django application across multiple EC2 instances
- Configured Nginx as reverse proxy and Gunicorn as WSGI server
- Implemented Target Group health checks and traffic routing
- Created reusable AMI and Launch Template for instance scaling
- Achieved high availability and fault tolerance architecture

---

## 📸 Final Output

<p align="center">
  <img src="final-output.png" alt="Final Output">
</p>

<p align="center">
  Screenshot above shows the Django calculator application running through the AWS Application Load Balancer (ALB) endpoint.
</p>

---

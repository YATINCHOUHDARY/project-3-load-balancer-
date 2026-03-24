# project-3-load-balancer-
AWS Load Balancer &amp; Auto Scaling project demonstrating high availability, traffic distribution, and dynamic scaling using EC2.
# AWS Load Balancer + Auto Scaling Project

## 📌 Architecture
User → Load Balancer → Auto Scaling Group → EC2 Instances

## 🚀 Services Used
- Amazon EC2
- Application Load Balancer
- Target Groups
- Auto Scaling Group

## ⚙️ Features
- High availability
- Load distribution
- Auto scaling based on CPU
- Fault tolerance

## ❌ Issue Faced
503 Service Temporarily Unavailable

## ✅ Solution
- Fixed security group rules
- Added EC2 instances to target group
- Configured health check path (/)

## 📈 Improvement
- Optimized scaling by increasing CPU threshold from 50% to 70%

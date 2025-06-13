# 🌐 AWS Route 53 – Routing Policy Projects

Welcome to the complete hands-on repository on **AWS Route 53 Routing Policies**. This collection of practicals demonstrates the working and configuration of various routing techniques used to manage DNS in cloud environments.

---

## 📌 Objective

The objective of this project is to practically implement and validate all major **Route 53 DNS routing policies** in AWS. Through hands-on execution, I explored how each routing strategy works, enhancing my understanding of AWS networking and DNS management as part of my cloud learning.

---

## 📁 Project List

| Folder Name                                | Routing Type           | Description |
|--------------------------------------------|------------------------|-------------|
| `AWS-Route53-Simple-Routing`              | Simple Routing         | Basic DNS resolution with single record. |
| `AWS-Route53-Weighted-Routing`            | Weighted Routing       | Distribute traffic based on weights (like A/B testing). |
| `AWS-Route53-Latency-Routing`             | Latency Routing        | Route users to the lowest-latency endpoint. |
| `AWS-Route53-Failover-Routing`            | Failover Routing       | Automatic failover to backup resources. |
| `AWS-Route53-Geolocation-Routing`         | Geolocation Routing    | Route based on users' physical locations. |
| `AWS-Route53-Geoproximity-Routing`        | Geoproximity Routing   | Traffic flow based on geography and bias. |
| `AWS-Route53-Multivalue-Routing`          | Multivalue Answer      | Return multiple healthy records. |
| `AWS-Route53-IPbased-Routing`             | IP-Based Routing       | Custom logic using source IP. |
| `AWS-Route53-Private-Hosted-Zone`         | Private Hosted Zone    | Internal DNS for VPC-only visibility. |
| `Route-53-Static-Website-Hosting-HTTP-&-HTTPS` | Static Website Hosting | Connect Route 53 with S3 and CloudFront for securing website. |

---

## 🛠️ Tools & Services Used

- **AWS Route 53**
- **EC2 Instances**
- **S3 + CloudFront (for Static Site Hosting)**
- **Health Checks**
- **IAM Roles & Policies**
- **Hosted Zones (Public & Private)**

---

## 📚 Folder Structure

Each project folder contains:

- 🧾 Step-by-step configuration instructions  
- ✅ `README.md` with implementation steps
- 🖥️ Output snapshots for result verification 

# AWS Static Website Deployment

## Project Overview
This project demonstrates cloud infrastructure management by hosting a public-facing static website on **Amazon Web Services (AWS)** using **Amazon S3**. 

## 🛠️ Skills & Technologies Demonstrated
* **Cloud Platform:** Amazon Web Services (AWS)
* **Storage Infrastructure:** Amazon Simple Storage Service (S3)
* **Security Best Practices:** AWS S3 Bucket Policies (IAM JSON configurations) instead of legacy ACLs
* **Web Fundamentals:** HTML5 & Cloud Networking

## ⚙️ Architecture & Implementation
1. **S3 Bucket Configuration:** Created a highly available storage bucket with public access controls enabled.
2. **Modern Permissions Management:** Applied a global JSON Bucket Policy to safely permit public read access (`s3:GetObject`) across all objects.
3. **Static Web Hosting:** Configured bucket parameters to resolve default index paths securely.

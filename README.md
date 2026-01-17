# AWS Static Website Hosting Project

This project demonstrates how to host a static website using **Amazon S3** and deliver it securely using **Amazon CloudFront**.

## 🔹 Project Overview
The website was initially hosted directly on S3. After encountering browser compatibility and access issues, CloudFront was integrated to improve availability, security, and performance.

## 🔹 Architecture
- Amazon S3 – Static website hosting
- Amazon CloudFront – Content Delivery Network (CDN)
- IAM Bucket Policy – Controlled public access

## 🔹 Challenges & Solutions
- **Issue:** Website accessible on Safari but not Chrome  
- **Solution:** Implemented CloudFront and updated S3 bucket policy  
- **Result:** Website now loads consistently across all major browsers and devices

## 🔹 Live Demo
👉 **CloudFront URL:** https://d17cyvygxo7nxg.cloudfront.net/

## 🔹 Technologies Used
- AWS S3  
- AWS CloudFront  
- HTML / CSS



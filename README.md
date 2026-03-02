# Lunching a Static Website Using AWS S3 & CloudFront (My Capstone Project)

## Overview

This project demonstrates how to deploy a static website on AWS using:

  * Amazon S3:- this serves as the object storage.
  * Amazon CloudFront:- this helps to deliver the content globally with less latency.
  * CloudFront Origin Access Control (OAC):- this helps to Secure the bucket access.
    
This website is deployed and fully accessible through a CloudFront distribution.
___

## Architecture

User → CloudFront → S3 Bucket → Static Files

CloudFront handles:
  * Global caching
  * Secure access to S3
  * HTTPS delivery
 
S3 stores:
  * index.html
  * styles.css
  * script.js
___

## Deployment Steps

 1. Created an S3 bucket
 2. Uploaded static website files
 3. Configured bucket policy for CloudFront access
 4. Created CloudFront distribution
 5. Set default root object to index.html
 6. Verified global access via CloudFront URL
___

## Screenshot Images

1. S3 Wesite Endpoint
2. CloudFront Distribution
3. S3 Succesful File Upload
___

## Tech Stack

  * HTML
  * CSS
  * JavaScript
  * Amazon S3
  * Amazon CloudFront
___

## Author
 AWOYEMI EMMANUEL.
 Cloud Engineering(AWS) Capstone Project @ Schull.io

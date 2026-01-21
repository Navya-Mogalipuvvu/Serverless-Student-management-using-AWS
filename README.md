# Serverless Architecture using AWS

A simple web application to **save and view student data** using **HTML, JavaScript (jQuery)**, and **AWS services** like **Lambda** , **DynamoDB**, **S3** ,**API Gateway**,**Amazon Cloud Front**.

---


## Overview

This web app allows users to:

- Enter student details (Student ID, Name, Class, Age)
- Save student information to an **AWS DynamoDB table**
- Retrieve and display all saved student records in a table format

Designed a static frontend hosted on Amazon S3 and distributed via CloudFront.Integrated API Gateway with AWS
Lambda for REST APIs (GET, POST) to interact with DynamoDB for data storage
---

## Features

- Responsive and clean user interface
- Add student data with a single click
- View all saved students dynamically
- Real-time updates using AJAX requests

---

## Technologies Used

- **Frontend:**
  - HTML, CSS, JavaScript
  - jQuery for AJAX requests
- **Backend:**
  - AWS Lambda (Python)
  - AWS DynamoDB for database storage
  - AWS S3
- **API Communication:**
  - REST API via AWS API Gateway

---



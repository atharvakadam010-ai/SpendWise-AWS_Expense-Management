# SpendWise-AWS_Expense-Management
Cloud based Expense Management System using MERN and AWS Services
# SpendWise - AWS Integrated Expense Management System

SpendWise is a cloud-integrated expense management system built using the MERN stack and AWS services. It allows users to manage expenses, upload receipt images, view analytics, and track activity logs.

## Features

- User authentication using AWS Cognito
- Add and delete expenses
- Upload receipt images to AWS S3
- View uploaded receipts
- Expense analytics using charts
- Activity logging using AWS DynamoDB
- Backend monitoring using AWS CloudWatch
- MongoDB Atlas for expense storage

## Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- Axios
- Recharts
- AWS Cognito SDK

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- Multer
- AWS SDK

### AWS Services
- Amazon Cognito
- Amazon S3
- Amazon DynamoDB
- Amazon CloudWatch
- IAM

## Project Architecture

React Frontend  
↓  
Node.js Express Backend  
↓  
MongoDB Atlas for expense data  
↓  
Amazon S3 for receipt storage  
↓  
DynamoDB for activity logs  
↓  
CloudWatch for backend monitoring  

## Screenshots

### Dashboard
![Dashboard](screenshots/dashboard.png)

### AWS S3 Receipt Upload
![S3](screenshots/s3.png)

### DynamoDB Logs
![DynamoDB](screenshots/dynamodb.png)

### CloudWatch Logs
![CloudWatch](screenshots/cloudwatch.png)

### AWS Cognito
![Cognito](screenshots/cognito.png)

## Setup Instructions

### Backend

```bash
cd backend
npm install
npm run dev

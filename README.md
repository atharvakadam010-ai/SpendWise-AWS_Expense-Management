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
![Dashboard](<img width="1917" height="972" alt="Dashboard" src="https://github.com/user-attachments/assets/7c18c959-9860-4372-8615-641fca636ec4" />
)

### AWS S3 Receipt Upload
![S3](<img width="1917" height="900" alt="S3 bucket" src="https://github.com/user-attachments/assets/d1544572-0841-421e-8416-ddd1c4dfa25c" />
)

### DynamoDB Logs
![DynamoDB](<img width="1917" height="955" alt="DynamoDB" src="https://github.com/user-attachments/assets/ac3cf87f-40d4-4cc3-bbd7-f0c0352ab9cd" />
)

### CloudWatch Logs
![CloudWatch](<img width="1917" height="952" alt="Cloudwatch" src="https://github.com/user-attachments/assets/d8228ed4-a5ea-4db6-8917-f6cfedfccd70" />
)

### AWS Cognito
![Cognito](<img width="1917" height="962" alt="Cognito" src="https://github.com/user-attachments/assets/c56a0b49-821b-4f78-a600-e13e478d2cf4" />
)

## Setup Instructions

### Backend

```bash
cd backend
npm install
npm run dev

# Serverless Task Manager 🚀

An end-to-end serverless task management application built using modern AWS services and Infrastructure as Code (IaC).

## 🛠️ Tech Stack & Architecture
* **AWS SAM (Serverless Application Model):** For defining and deploying infrastructure.
* **AWS Lambda:** Serverless compute for handling application logic.
* **Amazon DynamoDB:** NoSQL database for fast, reliable task storage.
* **Amazon API Gateway:** RESTful API endpoints connecting the frontend/client to backend functions.
* **Python:** Core programming language used for Lambda functions.

## ✨ Features
* Create, read, update, and delete tasks seamlessly.
* Fully serverless architecture ensuring zero server management and automatic scaling.
* Rapid local testing and deployment via AWS SAM CLI.

## 📂 Project Structure
```text
serverless-task-manager/
├── src/               # Lambda function handler code
├── template.yaml      # AWS SAM infrastructure configuration
└── README.md          # Project documentation

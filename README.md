# AWS AppSync To-Do Task App

A scalable, serverless To-Do application built using AWS AppSync, GraphQL, DynamoDB, Lambda, CloudWatch, and SNS.

![AWS](https://img.shields.io/badge/AWS-AppSync-orange)
![GraphQL](https://img.shields.io/badge/GraphQL-Supported-purple)

---

## 📽️ Demo

🎥 **Watch the project demo here:** [YouTube Video](https://youtu.be/-oc4hE_fdEw)

---

## 📌 Project Overview

This project implements a real-time task management app using a serverless architecture. The GraphQL API is managed by AWS AppSync, connected to DynamoDB for data storage, with Lambda functions handling custom logic and CloudWatch monitoring task metrics.

---

## 🛠️ Technologies Used

- **AWS AppSync** - Manages GraphQL API
- **Amazon DynamoDB** - NoSQL database for task storage
- **AWS Lambda** - Custom backend logic
- **Amazon CloudWatch** - Task metric monitoring
- **Amazon SNS** - Alert notifications for pending tasks
- **GraphQL** - API query language
- **IAM** - Permission and access management

---

## 📂 Folder Structure

```bash
.
├── graphql/
│   └── schema.graphql
├── resolvers/
│   ├── addTask.js
│   ├── deleteTask.js
│   ├── markComplete.js
│   └── getTasks.js
├── lambdas/
│   ├── taskToCloudwatch.js
│   └── checkTasksAndSendSNS.py
├── todo_task_app.zip              # Complete zipped version of the project
├── README.md                      # Project documentation
├── AWS_Project_Presentation_S.Sneha.pptx
├── SDC_CLOUD_DOC2210030133.pdf
├── 22100300133_SDC_PPT.pptx
├── 2210030133_SDC_Review-3.pdf
├── 2210030133_SDC_Review2.pdf
├── A2_2210030133.pdf
```

---

## 🚀 Features

- Add, mark complete, delete, and get tasks via GraphQL mutations & queries.
- Real-time logging of task status and due dates via CloudWatch.
- Task count monitoring with automatic SNS notifications for low pending tasks.
- Secure and scalable with IAM roles and serverless resources.

---

## 🧠 Learning Outcomes

- Real-world implementation of GraphQL with AWS AppSync.
- Integration of multiple AWS services to build a serverless architecture.
- Debugging resolvers using CloudWatch logs.
- API authentication and access control using IAM.

---

## 📈 Future Enhancements

- Real-time GraphQL subscriptions
- Frontend integration using React + AWS Amplify
- Fine-grained access control with AWS Cognito
- Deploy UI on Amazon S3 + CloudFront
- Integrate ML for smart task prioritization

---


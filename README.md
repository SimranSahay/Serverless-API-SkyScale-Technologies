 # ☁️ SkyScale Serverless API (AWS Lambda + API Gateway)

A serverless REST API built using **AWS Lambda** and **Amazon API Gateway** as part of an MCA Cloud Computing project. This project demonstrates cloud-native application development by creating a scalable backend without managing servers.

---

## 📌 Project Overview

The **SkyScale Serverless API** is designed to showcase the implementation of a serverless architecture on Amazon Web Services (AWS). The API is powered by AWS Lambda functions and exposed through Amazon API Gateway, allowing users to send HTTP requests and receive dynamic JSON responses.

This project highlights how modern cloud applications can be developed using event-driven computing while reducing infrastructure management and operational costs.

---

## 🚀 Live API Endpoint

```
https://dtjxnru6a6.execute-api.us-west-1.amazonaws.com
```

---

## 🔗 Available Route

### Hello Route (Dynamic Query Parameter)

**Request**

```
GET /hello?name=Simran
```

**Example URL**

```
https://dtjxnru6a6.execute-api.us-west-1.amazonaws.com/hello?name=Simran
```

**Response**

```json
{
  "status": "success",
  "message": "Hello Simran 👋 Welcome to SkyScale API"
}
```

---

## ✨ Features

* Serverless backend architecture
* Dynamic query parameter support
* REST API using Amazon API Gateway
* Event-driven AWS Lambda execution
* JSON-based API responses
* Highly scalable and cost-effective
* No server management required

---

## ☁️ AWS Services Used

* AWS Lambda
* Amazon API Gateway
* AWS IAM
* Amazon CloudWatch

---

## 🏗️ Architecture

```
                Client / Browser
                        │
                        ▼
              Amazon API Gateway
                        │
                        ▼
                 AWS Lambda Function
                        │
                        ▼
                 JSON Response Returned
```

---

## 📁 Project Structure

```
SkyScale-Serverless-API/
│
├── lambda_function.py
├── README.md
└── screenshots/
    ├── lambda-function.png
    ├── api-gateway.png
    ├── api-response.png
    └── cloudwatch-logs.png
```

---

## ⚙️ Deployment Steps

1. Create an AWS Lambda function.
2. Write and deploy the Lambda code.
3. Create an Amazon API Gateway REST API.
4. Integrate the API Gateway with the Lambda function.
5. Deploy the API to a stage.
6. Test the endpoint using a web browser or Postman.

---

## 🧪 Testing

**Method**

```
GET
```

**Endpoint**

```
/hello?name=YourName
```

Example:

```
/hello?name=Simran
```

Expected Response:

```json
{
  "status": "success",
  "message": "Hello Simran 👋 Welcome to SkyScale API"
}
```

---


## 🎯 Learning Outcomes

Through this project, I learned to:

* Build serverless applications using AWS.
* Integrate Lambda with API Gateway.
* Understand event-driven cloud architecture.
* Deploy and test REST APIs.
* Monitor executions using Amazon CloudWatch.
* Implement scalable backend services without managing servers.

---

## 📚 Technologies Used

* AWS Lambda
* Amazon API Gateway
* Python
* JSON
* REST API
* AWS IAM
* Amazon CloudWatch

---

## 👩‍💻 Author

**Simran Sahay**

MCA – Storage & Cloud Technology

Cloud Computing Project

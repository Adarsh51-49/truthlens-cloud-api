# TruthLens Cloud API

A serverless REST API built using **AWS Lambda** and **API Gateway**.  
This project demonstrates how to deploy and expose a cloud-native API without managing servers.

---

## 🚀 Tech Stack
- AWS Lambda (Python)
- AWS API Gateway (HTTP API)
- Python 3.x
- JSON

---

## 📌 Features
- Serverless architecture
- Public HTTP endpoint
- JSON response handling
- Auto-scaling and low cost

---

## 🧠 Architecture
Client → API Gateway → AWS Lambda → JSON Response

---

## 🔗 Live API Endpoint
https://<api-id>.execute-api.eu-north-1.amazonaws.com/truthlens-cloud-api


*(Replace `<api-id>` with your actual ID)*

---

## 📥 Sample Response
```
json
{
  "project": "TruthLens Cloud API",
  "message": "API is working successfully",
  "tech": ["AWS Lambda", "API Gateway"],
  "status": "success"
}
```
##  How It Works
```
API Gateway receives HTTP request

Triggers AWS Lambda function

Lambda returns JSON response

API Gateway sends response to client
```
##  Use Cases
```
Backend for web or mobile apps

Microservices

Proof of serverless deployment skills
```
##  Author
```
Adarsh Konderu
MSc Artificial Intelligence – Sheffield Hallam University
📍 Manchester, UK

GitHub: https://github.com/Adarsh51-49

LinkedIn: http://linkedin.com/in/adarsh-konderu
```



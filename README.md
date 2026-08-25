# 🔌 API Testing

## Overview

This folder contains documentation for **manual API testing** of common REST API endpoints. It includes request examples, validation scenarios, headers, payloads, and common HTTP responses.

## 📁 Request Files

* **GET_Requests.md** – Retrieve data, query parameters, and pagination
* **POST_Requests.md** – Create resources and validate request data
* **PUT_Requests.md** – Update existing resources
* **DELETE_Requests.md** – Delete resources and validate authorization

## 🛠️ Tools Used

* Postman
* Fiddler
* cURL
* Swagger / OpenAPI
* VS Code REST Client
* Chrome DevTools – Network

## 🔄 Common HTTP Methods

| Method     | Purpose         | Example        |
| ---------- | --------------- | -------------- |
| **GET**    | Retrieve data   | Get users      |
| **POST**   | Create resource | Create review  |
| **PUT**    | Update resource | Update user    |
| **DELETE** | Remove resource | Delete product |

## 📋 Common HTTP Status Codes

| Code    | Meaning               | Usage                      |
| ------- | --------------------- | -------------------------- |
| **200** | OK                    | Successful request         |
| **201** | Created               | Resource created           |
| **204** | No Content            | Successful deletion/update |
| **400** | Bad Request           | Invalid data               |
| **401** | Unauthorized          | Missing/invalid token      |
| **403** | Forbidden             | Action not allowed         |
| **404** | Not Found             | Resource doesn't exist     |
| **409** | Conflict              | Data conflict              |
| **429** | Too Many Requests     | Rate limit exceeded        |
| **500** | Internal Server Error | Server-side error          |
| **502** | Bad Gateway           | Upstream server error      |
| **503** | Service Unavailable   | Server unavailable         |
| **504** | Gateway Timeout       | Server timeout             |

## 🎯 Testing Focus

* Request and response validation
* Authentication and authorization
* Headers and payload validation
* Status code verification
* Positive and negative test scenarios
* Error handling and edge cases

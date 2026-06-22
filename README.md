# Notefy

A cloud-native academic collaboration platform built using React.js, Node.js, Express.js, and AWS services for secure note sharing, resource management, and student productivity.

## 🎥 Demo Video

[![Watch the Demo](https://img.shields.io/badge/Watch-Demo_Video-red?style=for-the-badge\&logo=youtube)](https://youtu.be/m5xWBDnlaEM)

A complete walkthrough of the platform demonstrating authentication, note sharing, cloud storage integration, task management, and overall application workflow.

## 📄 Project Documentation

Detailed technical documentation covering system architecture, AWS infrastructure, implementation details, deployment strategy, and project outcomes.

📘 [View Full Project Report](./Cloud%20Architecture%20Design%20Submission%20P.pdf)

---

## Overview

Notefy is a full-stack web application designed to help students centralize academic resources and manage coursework efficiently through a unified cloud-based platform.

### Core Features

* Secure user authentication using AWS Cognito
* Cloud-based note upload and sharing
* Task and deadline management
* Search and filtering functionality
* Responsive user interface
* AWS-powered cloud architecture

---

## Technology Stack

### Frontend

* React.js
* Vite
* JavaScript
* CSS

### Backend

* Node.js
* Express.js

### Cloud Infrastructure

* AWS EC2
* AWS Cognito
* AWS S3
* AWS DynamoDB

---

## System Architecture

```text
React Frontend
       │
       ▼
Node.js + Express Backend
       │
 ┌─────┼─────────────┐
 ▼     ▼             ▼
AWS Cognito      AWS S3      DynamoDB
(Authentication) (Storage)  (Metadata)

       │
       ▼
AWS EC2 Deployment
```

---

## Project Status

This project was originally deployed using AWS Free Tier services, including EC2, Cognito, S3, and DynamoDB.

The original cloud deployment is no longer active, but the source code, documentation, and demonstration video have been preserved for portfolio and educational purposes.

---

## Authors

* Medha S
* Aarya Nagvekar

Cloud Architecture Design Project
Vellore Institute of Technology (VIT)

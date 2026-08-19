# CapitalEdge – AI-Powered Cloud-Native Banking Management System

**CapitalEdge – AI-Powered Cloud-Native Banking Management System with Intelligent Credit Scoring, Conversational Banking, DevOps & MLOps**

---

## Team Members

| S. No. | University ID | Name          |
| :----: | :-----------: | ------------- |
|    1   |   2420090099  | Y. Nihitha    |
|    2   |   2420090117  | A. Sri Anitha |
|    3   |   2420030443  | T. K. Amulya  |
|    4   |   2420030523  | S. Harini     |

**Supervisor:** Ms. G. Lavanya

---

## Abstract

**CapitalEdge** is a modern banking management platform designed to provide secure, intelligent, and scalable banking services by integrating traditional banking operations with **Artificial Intelligence, Cloud Computing, DevOps, and MLOps practices**.

Traditional banking management systems primarily focus on account management, transactions, and administrative operations, while modern banking requires intelligent decision-making, personalized customer assistance, scalable infrastructure, and continuous software improvement.

CapitalEdge addresses these requirements by combining core banking functionalities with **AI-powered credit assessment and conversational banking**.

The system supports multiple banking roles, including:

* **Customer**
* **Bank Teller**
* **Bank Manager**
* **System Administrator**

Role-based access ensures secure and controlled operations.

### Banking Roles

| Role                     | Responsibilities                                                                                    |
| ------------------------ | --------------------------------------------------------------------------------------------------- |
| **Customer**             | Manage accounts, perform banking activities, and interact with the conversational banking assistant |
| **Bank Teller**          | Handle customer transactions and service requests                                                   |
| **Bank Manager**         | Monitor banking operations and manage relevant activities                                           |
| **System Administrator** | Manage system-level operations and security                                                         |

The platform incorporates an **AI-based credit scoring system** that analyzes relevant customer financial information to estimate creditworthiness and assist in making informed lending decisions.

A **conversational banking assistant** enables users to interact with the system using natural language and obtain assistance with banking-related queries.

The project follows **Agile Software Engineering principles**, with requirements organized into user stories and a prioritized product backlog. Scrum practices can be used for sprint planning, incremental development, testing, and continuous feedback.

**Git and GitHub** are used for version control and collaborative development.

DevOps practices are incorporated to automate the software development and deployment lifecycle using tools such as:

* Git
* GitHub
* Docker
* GitHub Actions

Cloud infrastructure can be provided through **AWS services** to support scalable and reliable deployment.

DevSecOps practices can be incorporated to improve application security through:

* Secure authentication
* Authorization
* Vulnerability scanning
* Static code analysis
* Security testing

The **MLOps pipeline** manages the complete lifecycle of the credit-scoring machine learning model, including:

* Data preparation
* Model training
* Experiment tracking
* Model versioning
* Deployment
* Monitoring

**MLflow** can be used for experiment tracking and model lifecycle management, while monitoring tools can be used to observe application and model performance.

Overall, CapitalEdge integrates:

* Banking Management
* Artificial Intelligence
* Cloud Computing
* Agile Software Engineering
* DevOps
* DevSecOps
* MLOps

into a single intelligent and scalable banking platform.

---

## Main Purpose

The main purpose of CapitalEdge is to develop a **secure, intelligent, and cloud-native banking management system** that combines conventional banking operations with AI-based decision-making and modern software engineering practices.

### Project Aims

* Digitize and manage core banking operations.
* Provide role-based banking services for customers, tellers, managers, and administrators.
* Use AI-based credit scoring to support intelligent lending decisions.
* Provide conversational banking for natural-language customer assistance.
* Use cloud infrastructure for scalability and availability.
* Apply DevOps for automated development and deployment.
* Apply DevSecOps for secure software development.
* Apply MLOps for managing and monitoring the credit-scoring model.

---

## Technologies Used

| Category                                       | Technologies                                                                         |
| ---------------------------------------------- | ------------------------------------------------------------------------------------ |
| **Frontend**                                   | React.js, HTML5, CSS3, JavaScript / TypeScript, Tailwind CSS *(if used)*             |
| **Backend**                                    | Java 21, Spring Boot, Spring Security, REST APIs, JWT Authentication                 |
| **Database**                                   | MySQL / PostgreSQL                                                                   |
| **Artificial Intelligence / Machine Learning** | Python, Scikit-learn, Pandas, NumPy, FastAPI                                         |
| **Machine Learning**                           | ML-based Credit Scoring                                                              |
| **DevOps & Cloud**                             | Git, GitHub, Docker, GitHub Actions, AWS EC2, AWS S3                                 |
| **DevSecOps**                                  | Spring Security, JWT, BCrypt, Role-Based Access Control, SonarQube, Trivy, OWASP ZAP |
| **MLOps & Monitoring**                         | MLflow, Prometheus, Grafana                                                          |

---

## Key Features

### 1. Role-Based Banking Management

The system provides different functionalities for:

* **Customer** – Account management, transactions, banking services, and AI assistance.
* **Bank Teller** – Customer service and transaction processing.
* **Bank Manager** – Monitoring and management of banking operations.
* **System Administrator** – System, user, and security management.

---

### 2. Intelligent Credit Scoring

The ML model analyzes relevant financial attributes to estimate a customer's creditworthiness and assist banking personnel in making more informed credit decisions.

---

### 3. Conversational Banking

An AI-powered conversational interface allows customers to ask banking-related questions and receive natural-language responses.

---

### 4. Secure Authentication

The system uses authentication and authorization mechanisms such as:

* JWT
* Spring Security
* BCrypt
* Role-Based Access Control

to protect user accounts and banking operations.

---

### 5. Cloud-Native Architecture

The application is designed to be deployed on cloud infrastructure, allowing it to scale according to application requirements.

---

### 6. DevOps Pipeline

GitHub Actions and Docker can automate:

```text
Code → Build → Test → Security Checks → Docker Build → Deployment
```

---

### 7. MLOps Pipeline

The credit-scoring model follows an ML lifecycle:

```text
Data → Training → Evaluation → Experiment Tracking → Model Versioning → Deployment → Monitoring → Retraining
```

---

## Project Architecture

The overall system can be divided into the following layers:

```text
Frontend Layer
React-based user interface for customers, tellers, managers, and administrators.

        ↓

Backend Layer
Spring Boot REST APIs handling authentication, accounts, transactions,
banking operations, and business logic.

        ↓

Database Layer
Stores customer information, accounts, transactions, loan information,
and other banking data.

        ↓

AI/ML Layer
Credit-scoring model and conversational banking capabilities.

        ↓

DevOps & Cloud Layer
Docker, GitHub Actions, AWS infrastructure, deployment, and monitoring.

        ↓

MLOps Layer
MLflow-based model tracking, versioning, deployment, and monitoring.
```

---

## Project Workflow

```text
User Registration/Login
        ↓
Role-Based Authentication
        ↓
Banking Operations
        ↓
Transaction & Account Management
        ↓
AI Credit Scoring / Conversational Banking
        ↓
Database Storage
        ↓
Monitoring & Analytics
```lligent banking platform.

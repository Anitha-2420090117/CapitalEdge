CapitalEdge – AI-Powered Cloud-Native Banking Management System with Intelligent Credit Scoring, Conversational Banking, DevOps & MLOps
Team Members
S. No.	University ID	Name
1	2420090099	Yalamanchili Nihitha
2	2420090117	Alluri Sri Anitha
3	2420030523	Somarowthu Harini
4	2420030434	Tammana Kameshwari Amulya

Supervisor
Ms. G Lavanya

Abstract

CapitalEdge – AI-Powered Cloud-Native Banking Management System with Intelligent Credit Scoring, Conversational Banking, DevOps & MLOps is a modern banking management platform designed to provide secure, intelligent, and scalable banking services by integrating traditional banking operations with Artificial Intelligence, Cloud Computing, DevOps, and MLOps practices.

Traditional banking management systems primarily focus on account management, transactions, and administrative operations, while modern banking requires intelligent decision-making, personalized customer assistance, scalable infrastructure, and continuous software improvement. CapitalEdge addresses these requirements by combining core banking functionalities with AI-powered credit assessment and conversational banking.

The system supports multiple banking roles, including Customer, Bank Teller, Bank Manager, and System Administrator, with role-based access to ensure secure and controlled operations. Customers can manage their accounts, perform banking activities, and interact with the conversational banking assistant. Bank tellers can handle customer transactions and service requests, while bank managers can monitor banking operations and manage relevant activities. System administrators are responsible for system-level management and security.

The platform incorporates an AI-based credit scoring system that analyzes relevant customer financial information to estimate creditworthiness and assist in making informed lending decisions. A conversational banking assistant enables users to interact with the system using natural language and obtain assistance with banking-related queries.

The project follows Agile Software Engineering principles, with requirements organized into user stories and a prioritized product backlog. Scrum practices can be used for sprint planning, incremental development, testing, and continuous feedback. Git and GitHub are used for version control and collaborative development.

DevOps practices are incorporated to automate the software development and deployment lifecycle using tools such as Git, GitHub, Docker, and GitHub Actions. Cloud infrastructure can be provided through AWS services to support scalable and reliable deployment.

DevSecOps practices can be incorporated to improve application security through secure authentication, authorization, vulnerability scanning, static code analysis, and security testing.

The MLOps pipeline manages the complete lifecycle of the credit-scoring machine learning model, including data preparation, model training, experiment tracking, model versioning, deployment, and monitoring. MLflow can be used for experiment tracking and model lifecycle management, while monitoring tools can be used to observe application and model performance.

Overall, CapitalEdge integrates Banking Management, Artificial Intelligence, Cloud Computing, Agile Software Engineering, DevOps, DevSecOps, and MLOps into a single intelligent and scalable banking platform.

Main Purpose

The main purpose of CapitalEdge is to develop a secure, intelligent, and cloud-native banking management system that combines conventional banking operations with AI-based decision-making and modern software engineering practices.

The project aims to:

Digitize and manage core banking operations.
Provide role-based banking services for customers, tellers, managers, and administrators.
Use AI-based credit scoring to support intelligent lending decisions.
Provide conversational banking for natural-language customer assistance.
Use cloud infrastructure for scalability and availability.
Apply DevOps for automated development and deployment.
Apply DevSecOps for secure software development.
Apply MLOps for managing and monitoring the credit-scoring model.
Technologies Used
Frontend
React.js
HTML5
CSS3
JavaScript / TypeScript
Tailwind CSS (if used)
Backend
Java 21
Spring Boot
Spring Security
REST APIs
JWT Authentication
Database
MySQL / PostgreSQL
Artificial Intelligence / Machine Learning
Python
Scikit-learn
Pandas
NumPy
FastAPI
Machine Learning-based Credit Scoring
DevOps & Cloud
Git
GitHub
Docker
GitHub Actions
AWS EC2
AWS S3
DevSecOps
Spring Security
JWT
BCrypt
Role-Based Access Control
SonarQube
Trivy
OWASP ZAP
MLOps & Monitoring
MLflow
Prometheus
Grafana
Key Features
1. Role-Based Banking Management

The system provides different functionalities for:

Customer – account management, transactions, banking services, and AI assistance.
Bank Teller – customer service and transaction processing.
Bank Manager – monitoring and management of banking operations.
System Administrator – system, user, and security management.
2. Intelligent Credit Scoring

The ML model analyzes relevant financial attributes to estimate a customer's creditworthiness and assist banking personnel in making more informed credit decisions.

3. Conversational Banking

An AI-powered conversational interface allows customers to ask banking-related questions and receive natural-language responses.

4. Secure Authentication

The system uses authentication and authorization mechanisms such as JWT, Spring Security, BCrypt, and role-based access control to protect user accounts and banking operations.

5. Cloud-Native Architecture

The application is designed to be deployed on cloud infrastructure, allowing it to scale according to application requirements.

6. DevOps Pipeline

GitHub Actions and Docker can automate:

Code → Build → Test → Security Checks → Docker Build → Deployment

7. MLOps Pipeline

The credit-scoring model follows an ML lifecycle:

Data → Training → Evaluation → Experiment Tracking → Model Versioning → Deployment → Monitoring → Retraining

Project Architecture

The overall system can be divided into the following layers:

Frontend Layer
React-based user interface for customers, tellers, managers, and administrators.

↓

Backend Layer
Spring Boot REST APIs handling authentication, accounts, transactions, banking operations, and business logic.

↓

Database Layer
Stores customer information, accounts, transactions, loan information, and other banking data.

↓

AI/ML Layer
Credit-scoring model and conversational banking capabilities.

↓

DevOps & Cloud Layer
Docker, GitHub Actions, AWS infrastructure, deployment, and monitoring.

↓

MLOps Layer
MLflow-based model tracking, versioning, deployment, and monitoring.

Setup Instructions
Prerequisites

Make sure the following software is installed:

Java 21
Node.js and npm
Python 3.x
MySQL / PostgreSQL
Git
Docker
AWS Account (for cloud deployment, if applicable)
Clone the Repository
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd CapitalEdge
Backend Setup
cd backend

Configure the database connection and required environment variables.

Then run:

./mvnw spring-boot:run

For Windows:

mvnw.cmd spring-boot:run
Frontend Setup
cd frontend
npm install
npm start
AI/ML Setup
cd ml-service
pip install -r requirements.txt

Start the FastAPI service:

uvicorn main:app --reload
Project Workflow

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

The complete application is supported by DevOps, DevSecOps, Cloud, and MLOps pipelines for secure and continuous development, deployment, and improvement.

One-line project definition for your presentation

CapitalEdge is an AI-powered cloud-native banking management system that combines secure banking operations, intelligent credit scoring, conversational banking, DevOps, DevSecOps, and MLOps to deliver a scalable and intelligent banking platform.

# 🚀 Full Stack Node.js Application Deployment with Docker, ECR, ECS & CloudWatch

## 📦 **Project Overview:**
This project demonstrates how to deploy a **Node.js application** using **Docker** for containerization, **Amazon ECR** for storing Docker images, **Amazon ECS** for deployment, and **CloudWatch** for monitoring the deployed app.

### 🛠️ **Technologies Used:**
- **Node.js**: Backend application runtime
- **Docker**: Containerization of the app
- **Amazon ECR**: Docker image registry
- **Amazon ECS**: Managed container service (Fargate)
- **IAM**: Access management
- **CloudWatch**: Monitoring and logging

### 🔄 **Key Steps Involved:**
1. **Dockerizing the Application**:  
   Containerized the Node.js app with Docker, ensuring it runs consistently across multiple environments.

2. **Push to ECR**:  
   The Docker image is pushed to **Amazon ECR** using secure IAM credentials.

3. **ECS Deployment**:  
   The image is deployed using **Amazon ECS Fargate** which eliminates the need for managing EC2 instances.

4. **IAM Setup**:  
   Created IAM roles to securely grant ECS access to Amazon ECR and CloudWatch.

5. **CloudWatch Integration**:  
   Configured logging and monitoring to track app performance and health in real-time.

### 🔐 **Security Best Practices:**
- Used **IAM** roles for secure access between AWS services.
- Configured **CloudWatch Logs** to capture security-related events.

### 🔗 **Links:**
- GitHub Repository: *(Add your repo URL here)*

### 📸 **Architecture Diagram:**
- Attached below is the visual architecture of the deployment setup:
  ![Architecture Diagram](images/architecture.png)

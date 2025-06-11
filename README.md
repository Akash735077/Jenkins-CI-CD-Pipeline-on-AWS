Jenkins-CI-CD-Pipeline-on-AWS

📌 Project Summary
- Set up a Jenkins CI/CD pipeline on AWS EC2.
- Integrated with GitHub for automatic builds.
- Dockerized a Node.js app and deployed via Jenkins.

🛠 Tools Used
- AWS EC2 (Ubuntu)
- Jenkins
- Git & GitHub
- Docker
- Node.js
- Shell scripting

⚙️ Setup Steps
1. Launch EC2 and install Java, Jenkins, and Docker.
2. Configure Jenkins and install necessary plugins.
3. Connect GitHub repo using Webhook.
4. Create Dockerfile for Node.js app.
5. Create Jenkins job to:
   - Build Docker image
   - Run container
6. Access app on `http://<EC2-IP>:8000`.

📚 Key Concepts Learned
- Jenkins job configuration
- GitHub Webhook integration
- Docker container build and run
- Basic AWS EC2 operations
 📎 Author
**Akash Patil** 

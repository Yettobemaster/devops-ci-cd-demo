# 🚀 Node.js Sample App - DevOps CI/CD Demo

This project is a simple Node.js application containerized with Docker and deployed on an AWS EC2 instance. It demonstrates an end-to-end DevOps workflow including local development, containerization, GitHub integration, and cloud deployment.

---

## 💻 Tech Stack

- Node.js
- Express.js
- Docker
- AWS EC2
- Git & GitHub

---

## 📄 Project Features

✅ Simple Node.js "Hello World" app  
✅ Dockerized for portability and reproducibility  
✅ Deployed on AWS EC2 with security group configuration  
✅ Open to future CI/CD automation (e.g., Jenkins, Terraform, Ansible)

---

## ⚙️ How to Run Locally

```bash
git clone https://github.com/Yettobemaster/devops-ci-cd-demo.git
cd devops-ci-cd-demo
npm install
npm start
Visit: http://localhost:5000

🐳 How to Run with Docker Locally
bash
Copy
Edit
docker build -t node-js-sample .
docker run -p 5000:5000 node-js-sample
Visit: http://localhost:5000

☁️ How to Deploy on AWS EC2
1️⃣ Launch an EC2 instance (Amazon Linux or Ubuntu).
2️⃣ Configure security group (allow SSH and TCP 5000).
3️⃣ SSH into the instance, install Docker and Git.
4️⃣ Clone repo and build Docker image:

bash
Copy
Edit
git clone https://github.com/Yettobemaster/devops-ci-cd-demo.git
cd devops-ci-cd-demo
docker build -t node-js-sample .
docker run -d -p 5000:5000 node-js-sample
Visit: http://<your-ec2-public-ip>:5000

🌐 Architecture Diagram
plaintext
Copy
Edit
[ GitHub Repo ] 
      |
      v
[ Local Dev Machine ]
      |
      v
[ Docker Container ]
      |
      v
[ AWS EC2 Instance ]
      |
      v
[ Public Web Access on Port 5000 ]
✨ Future Enhancements
Add CI/CD pipeline using Jenkins

Use Terraform for infra provisioning

Use Ansible for automated configuration

Deploy on Kubernetes

🙏 Author
Pramod Holkar

📬 Contact
GitHub: Yettobemaster

LinkedIn: https://www.linkedin.com/in/pramod-holkar-096692216

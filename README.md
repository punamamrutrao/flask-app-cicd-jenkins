# Flask App CI/CD Pipeline using Jenkins, Docker, and Terraform

This project demonstrates a complete CI/CD pipeline for a containerized Flask application using **Jenkins**, **Docker**, **AWS ECR**, and **Terraform** for infrastructure as code.

---

## 🚀 Tech Stack

- Python (Flask)
- Docker
- Jenkins (Declarative Pipeline)
- AWS ECR (for container registry)
- Terraform (for infrastructure provisioning)
- GitHub (source code management)

---

## 📦 Project Structure

flask-app-cicd-jenkins/
├── app/
│ └── app.py # Basic Flask app
├── Dockerfile # Docker image definition
├── Jenkinsfile # Jenkins CI/CD pipeline
├── terraform/
│ └── main.tf # Placeholder for EKS/ECS infra
└── README.md


---

## 🛠 How the Pipeline Works

1. **Jenkins** pulls the latest code from GitHub.
2. Builds a **Docker image** for the Flask app.
3. Pushes the image to **Amazon ECR**.
4. (Optional) Deploys the image to **EKS** using `kubectl` or Terraform IaC.

---

## 🔐 AWS Resources Required

- IAM with ECR access
- ECR repository
- EKS/ECS cluster (optional)
- S3 + DynamoDB backend (for Terraform)

---

## 👩‍💻 Author

**Punam Amrutrao**  
DevOps Engineer | AWS Certified  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/punam-amrutrao)

---

## 📂 License

This project is open source and available under the [MIT License](LICENSE).

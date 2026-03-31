## 📌 Project Overview
This project demonstrates how to deploy a static website to AWS S3 using GitHub Actions CI/CD pipeline.

---

## 🛠️ Technologies Used
- AWS S3
- GitHub Actions
- HTML
- Git

---

## 📂 Project Structure

your-project/
├── index.html
└── .github/
  └── workflows/
    └── cicd.yml


---

## ⚙️ CI/CD Workflow
- Code is pushed to GitHub
- GitHub Actions triggers automatically
- Application is deployed to AWS S3

---

## 🔐 GitHub Secrets Required
- AWS_ACCESS_KEY_ID
- AWS_SECRET_ACCESS_KEY
- AWS_REGION
- BUCKET_NAME

---

## 🚀 Deployment Steps
1. Clone the repository  
2. Create S3 bucket in AWS  
3. Configure IAM user  
4. Add GitHub variables & secrets  
5. Push code to main branch  

---

## 🌐 Output
The static website will be hosted on AWS S3.

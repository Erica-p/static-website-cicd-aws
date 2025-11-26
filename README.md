# static-website-cicd-aws  
Professional AWS Static Website Project with CI/CD

---

## 📘 Overview  
This project shows how to deploy and automate a static website using AWS services and GitHub Actions.  
It follows real cloud engineering patterns:

- S3 website hosting  
- CloudFront CDN  
- HTTPS with ACM  
- Route 53 domain routing (optional)  
- Automated CI/CD pipeline  
- CloudFormation Infrastructure as Code (IaC)

---

## 🚀 Features  
- Automated CI/CD pipeline  
- S3 static website hosting  
- CloudFront CDN distribution  
- HTTPS with ACM  
- Route 53 domain routing (optional)  
- Version-controlled IaC (CloudFormation)  
- Clean folder structure for easy review

---

## 📁 Project Structure  

src/                     → Website files (HTML/CSS/JS)
.github/workflows        → CI/CD pipeline
cloudformation/          → IaC templates
README.md                → Project documentation

---

## 🛠️ Tools Used  
- **AWS S3** — static hosting  
- **AWS CloudFront** — global content distribution  
- **AWS Route 53** — domain routing  
- **AWS ACM** — SSL certificates  
- **GitHub Actions** — CI/CD automation  
- **CloudFormation** — Infrastructure as Code

---

## 📦 Deployment Flow  
1. Push code → GitHub Actions triggers  
2. Build & validate website files  
3. Deploy files to S3  
4. Invalidate CloudFront cache  
5. Website updates globally in seconds

---

## 📊 Architecture Diagram  
*(You will upload the PNG here later — leave this section for now.)*

---

## 🤝 About the Project  
Built as part of my cloud engineering learning journey.  
This project demonstrates real AWS production-ready static website deployment and CI/CD automation.
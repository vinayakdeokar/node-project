# node-project

# Node.js CI/CD Pipeline with Jenkins

This project demonstrates a **CI/CD pipeline** for a Node.js app using **Jenkins** with stages: **Build → Test → Deploy**.  
App gets automatically deployed on **AWS EC2** using **PM2**.

---

## 📌 Overview
- **Build** → Install dependencies  
- **Test** → Run Mocha & Supertest  
- **Deploy** → Deploy to EC2 with Jenkins + PM2  

---

## 🛠️ Tech Stack
- Node.js, Express.js  
- Mocha, Supertest  
- GitHub (SCM)  
- Jenkins (CI/CD)  
- AWS EC2, PM2  

---

## ⚙️ Quick Setup
```bash
# On EC2
sudo apt update && sudo apt install -y nodejs npm
git clone <repo-link>
cd nodeapp
npm install
pm2 start index.js

Step: 2
🔄 Flow

Push code to GitHub

Jenkins → Build → Test → Deploy

App auto-deployed on EC2

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/1eb4d575-e40d-4b9d-96db-b6cdc25a7339" />

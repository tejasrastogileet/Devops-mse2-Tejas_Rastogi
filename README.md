# DevOps MSE-2 Assignment

## 👨‍🎓 Student Details
- **Name:** Tejas Rastogi  
- **University Roll No:** 202401100200321  
- **Institute:** KIET Group of Institutions  
- **Semester:** Even Sem 2026  

---

## 📌 Completed Test Cases

I have successfully completed the following test cases from the DevOps Debug Challenge:

---

### 🔹 Test Case 2 — File Permission Configuration

**Objective:** Configure file permissions and ownership for a web server file.

**Steps Performed:**
- Created `index.html` file in home directory  
- Added HTML content to the file  
- Checked default file permissions using `ls -l`  
- Changed permissions to `777` (full access)  
- Changed ownership to `www-data`  
- Updated permissions to `755`  
- Verified final permissions and ownership  

**Outcome:**
- File permissions successfully changed from `777` to `755`  
- Owner and group updated correctly  
- Final output verified using `ls -l`  

---

### 🔹 Test Case 3 — Node.js Application Setup & Git Integration

**Objective:** Create and deploy a Node.js API.

**Steps Performed:**
- Initialized Node.js project using `npm init`  
- Installed dependencies (`express`, `@types/express`)  
- Created Express server running on port 8080  
- Implemented `/health` endpoint returning `{ "status": "OK" }`  
- Initialized Git repository  
- Created initial commit  
- Pushed project to GitHub  

**Outcome:**
- Node.js server runs successfully  
- API endpoint `/health` returns correct response  
- GitHub repository created with project files  

---

### 🔹 Test Case 4 — Docker & Containerization

**Objective:** Containerize the Node.js application using Docker.

**Steps Performed:**
- Created `Dockerfile` using `node:18-alpine`  
- Set working directory `/app`  
- Installed dependencies inside container  
- Exposed port `8080`  
- Built Docker image `nodejs-api`  
- Ran container and tested API  
- Created `docker-compose.yml`  
- Ran container using `docker compose up -d`  

**Outcome:**
- Docker image built successfully  
- Container runs without errors  
- API accessible at `http://localhost:8080/health`  
- Docker Compose runs service in background  

---

## ⚙️ Tools & Technologies Used
- Linux Commands  
- Node.js (Express)  
- Docker  
- Git & GitHub  

---

## 🎯 Conclusion
This assignment helped me gain practical experience in:
- File permission management in Linux  
- Building and running Node.js applications  
- Containerization using Docker  
- Version control using Git and GitHub  

---

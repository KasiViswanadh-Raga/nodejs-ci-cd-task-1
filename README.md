# nodejs-ci-cd-task-1
📌 DevOps Task - 1: CI/CD Pipeline with GitHub Actions & DockerHub

This project demonstrates how to automate the deployment of a Node.js application using *GitHub Actions* and *DockerHub*. A CI/CD pipeline is set up to build and push Docker images to DockerHub whenever changes are pushed to the repository.

---

## ✅ Task Objective

- Create a Node.js app
- Containerize it using Docker
- Automate the CI/CD process using GitHub Actions
- Push Docker image to DockerHub on every commit

---

## 🛠 Technologies Used

- Node.js
- Docker
- GitHub Actions
- DockerHub
## 📁 Project Structure

. ├── index.js ├── Dockerfile ├── package.json └── .github/ └── workflows/ └── main.yml

---

## ⚙ CI/CD Pipeline Workflow

The GitHub Actions workflow performs the following:

1. Trigger on every push to the main branch
2. Build the Docker image
3. Authenticate with DockerHub
4. Push the image to DockerHub repository:  
   ragakasiviswanadh/viswa-nodejs-app

---

## 🚀 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/KasiViswanadh-Raga/nodejs-ci-cd-task-1.git

# Navigate into the project folder
cd nodejs-ci-cd-task-1

# Build Docker image
docker build -t viswa-nodejs-app .

# Run the Docker container
docker run -p 3000:3000 viswa-nodejs-app

---

📦 DockerHub Repository

🔗 DockerHub – viswa-nodejs-app


---

🙋‍♂ Author

 Kasi Viswanadh Raga– DevOps Intern
🔗 GitHub: kasiviswanadh-Raga

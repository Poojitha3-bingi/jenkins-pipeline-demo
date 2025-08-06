# Jenkins CI/CD Pipeline Demo

This project showcases a basic **CI/CD pipeline using Jenkins**, integrated with GitHub. It demonstrates how to automatically build, test, and deploy code changes using a Jenkinsfile.

---

## 🛠️ Tools Used

- 🧰 Jenkins
- 🐙 GitHub
- 🐳 Docker (optional)
- 💻 VS Code

---

## 📁 Project Structure

jenkins-pipeline-demo/
├── Jenkinsfile # Contains pipeline script
├── app.py # Simple Python script
└── README.md # Project documentation


---

## 🔃 Pipeline Stages

The pipeline defined in the `Jenkinsfile` contains the following stages:

1. **Build**
   - Simulates building the application
2. **Test**
   - Placeholder for running tests
3. **Deploy**
   - Placeholder for deploying (e.g., using Docker)

### 🔧 Jenkinsfile (sample)

```groovy
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the app...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the app using Docker...'
            }
        }
    }
}

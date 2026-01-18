rahtest1

```markdown
# DevOps CI/CD Pipeline Project 🚀

This repository demonstrates a complete CI/CD pipeline setup integrating **Jenkins, Docker, Kubernetes, SonarQube, Slack, AWS, and GCP** for automation and cloud-native deployments.

---

## 📂 Repository Structure

```

.github/workflows/      # GitHub Actions workflow (main.yml)
app/                    # Python application source code
tests/                  # Unit tests
Dockerfile              # Docker image build file
Jenkinsfile             # Jenkins pipeline for CI/CD
jenkinfilekub           # Jenkins pipeline for Kubernetes deployments
kubernetes-manifest.yaml# Kubernetes manifests (Deployments, Services, etc.)
requirements.txt        # Python dependencies
cloudbuild.yaml         # GCP Cloud Build pipeline
sonarslack/             # SonarQube + Slack integration scripts
aws codebuild lab.docx  # AWS CodeBuild lab documentation
lab-jenkins-docker.\*    # Jenkins + Docker lab guides

````

---

## ⚙️ Features

- **Python Application** with tests
- **Docker** for containerization
- **Jenkins Pipelines**
  - Standard build & test pipeline (`Jenkinsfile`)
  - Kubernetes deployment pipeline (`jenkinfilekub`)
- **CI/CD Integrations**
  - GitHub Actions workflow
  - SonarQube for static code analysis
  - Slack notifications
- **Cloud Deployments**
  - AWS CodeBuild labs
  - GCP Cloud Build (`cloudbuild.yaml`)
  - Kubernetes manifests for container orchestration

---

## 🛠️ Tech Stack

- **Languages/Frameworks:** Python 3
- **CI/CD Tools:** Jenkins, GitHub Actions, AWS CodeBuild, GCP Cloud Build
- **Containerization:** Docker
- **Orchestration:** Kubernetes
- **Code Quality & Notifications:** SonarQube, Slack

---

## 🚀 Getting Started

### 1️⃣ Clone Repository
```bash
git clone https://github.com/amitopenwriteup/amitopenwriteup.git
cd amitopenwriteup
````

### 2️⃣ Build & Run Python App

```bash
pip install -r requirements.txt
python app/app.py
```

### 3️⃣ Build Docker Image

```bash
docker build -t my-python-app .
docker run -p 5000:5000 my-python-app
```

### 4️⃣ Run Tests

```bash
pytest tests/
```

---

## 📦 CI/CD Pipelines

* **GitHub Actions:** `.github/workflows/main.yml`
* **Jenkins Pipelines:** `Jenkinsfile`, `jenkinfilekub`
* **GCP Cloud Build:** `cloudbuild.yaml`
* **AWS CodeBuild:** documented in `aws codebuild lab.docx`

---

## 📜 Documentation

* **Lab Docs** included for AWS, GCP, Docker, Jenkins setup
* Example Kubernetes deployment in `kubernetes-manifest.yaml`

---

## 🤝 Contributing

Feel free to fork, raise issues, and contribute via pull requests.

---

## 📧 Contact

Maintainer: **Amit Maheshwari**
📩 [amit@openwriteup.com](mailto:amit@openwriteup.com)

---

```



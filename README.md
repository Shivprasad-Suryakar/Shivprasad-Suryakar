# Hi there 👋, I'm Shivprasad Suryakar

`Junior DevOps Engineer` · `MCA` · `Linux` · `AWS` · `Docker` · `Kubernetes` · `OpenShift` · `Terraform`

---

## 👨‍💻 About Me

- 🎓 **MCA** & Computer Science background with hands-on focus on Cloud & DevOps engineering
- 🐧 Strong daily workflow across **Linux** (Ubuntu/WSL2, RHEL, openSUSE, Kali), Bash & Python automation
- 🐳 Building & deploying containerized workloads using **Docker**, **Podman**, **Kubernetes**, and **Red Hat OpenShift**
- ☁️ Provisioning cloud infrastructure with **Terraform** on **AWS** (EC2, ECS, ECR, S3, CloudFront) and **GCP**
- 🔁 Automating build, test, and deployment pipelines via **GitHub Actions** and **Jenkins**

---

## 🛠️ Tech Stack

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=linux,docker,kubernetes,terraform,aws,gcp,jenkins,githubactions,ansible,bash,python,git" alt="Tech Stack Icons" />
  </a>
</p>

> Also working with **Podman** and **Red Hat OpenShift** for container runtimes and enterprise cluster workflows.

---

## 🔄 DevOps & Cloud Tools Architecture

```mermaid
flowchart LR
    DEV["💻 Code & Git<br/>Linux · Bash · Python"] --> CI["⚙️ CI/CD Pipeline<br/>GitHub Actions · Jenkins"]
    CI --> CNT["🐳 Containers<br/>Docker · Podman"]
    CNT --> K8S["☸️ Orchestration<br/>Kubernetes · OpenShift"]
    IAC["🧱 Terraform IaC<br/>Automated Provisioning"] --> AWS["☁️ Cloud Infrastructure<br/>AWS · GCP"]
    K8S <--> AWS

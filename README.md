<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=00C2FF&height=250&section=header&text=Chanindu%20Imanjith&fontSize=50&fontAlignY=35&animation=twinkling&fontColor=ffffff"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3500&pause=1000&color=00C2FF&center=true&vCenter=true&width=700&lines=DevOps+Engineer;Cloud+Infrastructure+Enthusiast;MLOps+Specialist;Open+Source+Contributor" alt="Typing Animation" />

<br>

<a href="mailto:chanindu.imanjith@gmail.com">
<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://www.linkedin.com/in/chanindu-imanjith-72814431b">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://github.com/ChaninduImanjith">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="https://chanindu-portfolio-v2.netlify.app/">
<img src="https://img.shields.io/badge/Portfolio-00C2FF?style=for-the-badge&logo=firefox&logoColor=white"/>
</a>

<br><br>
<img src="https://komarev.com/ghpvc/?username=ChaninduImanjith&style=flat-square&color=00C2FF&label=Profile%20Views" alt="Profile Views" />
</div>

---

## 💫 About Me

I am a Software Engineering undergraduate and DevOps enthusiast based in Kalutara, Sri Lanka. With a strong foundation in cloud-native architectures, distributed systems, and CI/CD pipelines, I am passionate about building scalable infrastructure and automating deployments. I am deeply focused on integrating machine learning models into production environments through efficient **MLOps** practices.

- 🎓 **Undergraduate:** BSc (Hons) Software Engineering at the University of Kelaniya
- 💻 **Professional Studies:** CMJD Professional at IJSE - Institute of Software Engineering
- 🐧 **Daily Driver:** Native Fedora Linux user
- 🌱 **Currently Exploring:** Advanced Kubernetes, Terraform, AWS Solutions Architecture, and MLOps infrastructure.

---

## 🛠 Tech Stack & Tools

<div align="center">
  <img src="https://skillicons.dev/icons?i=linux,fedora,bash,git,github,gitlab,docker,kubernetes,terraform,ansible,jenkins,aws,python,java,spring,react,vite,mysql,postgres,prometheus,grafana,vscode&perline=11" />
</div>

<br>

| Domain | Technologies |
|---|---|
| **Cloud & IaC** | AWS (EC2, S3, VPC), Terraform, Docker, Kubernetes |
| **Automation & CI/CD** | Jenkins, GitHub Actions, Argo CD, Ansible |
| **Development** | Java (OOP, SOLID, Design Patterns), Python, React 19, Spring Boot |
| **MLOps & Monitoring** | Model Deployment, Prometheus, Grafana |

<br>

<details>
<summary><b>🛠️ View My Advanced Toolset (Click to Expand)</b></summary>
<br>

- **OS:** Fedora Linux (Terminal Power User)
- **Container Orchestration:** Argo CD, Kubernetes
- **Design Patterns:** SOLID Principles, Factory Pattern, Dependency Inversion
- **Cloud Infrastructure:** AWS (EC2, S3, VPC Management)

</details>

---

## 🌍 Open Source Contributions

Passionate about cloud-native infrastructure, identity management, and model serving platforms, I actively engage with enterprise-grade open-source ecosystems.

- 🚀 **[WSO2](https://github.com/wso2):** Actively contributing to the enterprise ecosystem. Successfully contributed a merged Pull Request to the WSO2 Identity Server platform documentation: **[wso2/docs-is#6202](https://github.com/wso2/docs-is/pull/6202)**.
- 🤖 **[KServe](https://github.com/kserve):** Exploring and engaging with highly scalable machine learning model serving infrastructure.
- 🚢 **[OpenChoreo](https://github.com/openchoreo):** Contributing to `openchoreo/openchoreo` and related deployment tools.
- 📦 **Community Activity:** Actively collaborating across 30+ repositories with an activity footprint of **75% Commits** and **25% Pull Requests**.

<p align="left">
  <img src="https://img.shields.io/badge/Open%20Source-Contributor-00C2FF?style=for-the-badge&logo=open-source-initiative&logoColor=white" />
  <img src="https://img.shields.io/badge/Merged%20PR-WSO2-4CAF50?style=for-the-badge&logo=github&logoColor=white" />
</p>

---

## ⚙️ Core CI/CD & MLOps Architecture Workflow

```mermaid
graph TD;
    A[Developer Push] -->|Git| B(GitHub Repository);
    B -->|Webhook| C{Jenkins / GitHub Actions};
    C -->|Build| D[Docker Image];
    D -->|Push| E[Amazon ECR / DockerHub];
    E -->|Deploy| F[Kubernetes Cluster / EKS];
    C -->|Run Tests| G[SonarQube & JUnit];
    F -->|Monitor| H[Prometheus & Grafana];
    
    style C fill:#00C2FF,stroke:#333,stroke-width:2px;
    style F fill:#8A2BE2,stroke:#333,stroke-width:2px;

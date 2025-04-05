#  End-to-End DevOps Workflow for a Multi-Tier Java Bank App

This repository demonstrates a Java-based multi-tier banking application integrated with a complete DevOps workflow, including CI, code quality analysis, security scanning, and artifact management.


##  Infrastructure Provisioning

For Infrastructure setup Refer the below repo  
👉 [Infrastructure Setup](https://github.com/b-v-krishna/EKS-Terraform)

## Continuous Integration (CI)

Jenkins pipeline automates:

- Code checkout from GitHub
- Maven-based build and unit tests
- Static code analysis using SonarQube
- Vulnerability scans via Trivy
- Docker image build and push to registry
- Artifact deployment to Nexus

##  Continuous Deployment (CD)

 For Deployment and CD part refer the below repo:  
👉 [CD Repository](https://github.com/b-v-krishna/Multi-Tier-BankApp-CD)

This repository manages Kubernetes manifests, and continuous deployment based on versioned Docker images.


## Tools Explored

| Purpose                  | Tool / Technology     |
|--------------------------|------------------------|
| Source Control           | GitHub                 |
| Build Tool               | Maven                  |
| CI/CD Engine             | Jenkins                |
| Code Quality             | SonarQube              |
| Security Scanning        | Trivy                  |
| Artifact Repository      | Nexus 3                |
| Containerization         | Docker                 |


---

## Snapshots of Application

### Jenkins CI Pipeline  
![Jenkins Pipeline](https://raw.githubusercontent.com/b-v-krishna/Multi-Tier-BankApp-CI/main/src/main/resources/templates/jenkins_pipeline.png)

---

### Nexus Artifact Repository  
![Nexus Artifactory](https://raw.githubusercontent.com/b-v-krishna/Multi-Tier-BankApp-CI/main/src/main/resources/templates/Artifactory.png)

---

### Sonar Analysis  
![Sonar Analysis](https://raw.githubusercontent.com/b-v-krishna/Multi-Tier-BankApp-CI/main/src/main/resources/templates/Sonar_Analysis.png)

---

# License

This project is licensed under the MIT License.

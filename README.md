  
<h1 align="center">
  
  <a href="https://www.linkedin.com/in/ram-cloud-devops/"> Hi 👋, I'm Ram
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn" style="vertical-align: middle;">
  </a>
</h1>
<h3 align="center">👨‍💻I’m currently a software engineering Grad Student @ Northeastern University</h3>


<p align="center">
  📫 <a href="mailto:vadapalli.j@northeastern.edu"><strong>vadapalli.j@northeastern.edu</strong><a> | 
  🔭 <a href="https://ram2305.github.io/Ram/"><strong>Portfolio</strong></a> | 
  📄 <a href="https://drive.google.com/file/d/1yvYPK-1jXzIpcqOzCIhybje7wtUzWMZz/view"><strong>Resume</strong></a>
</p>


## 💻 Tech Stack:
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) ![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white) ![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)  ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) ![Packer](https://img.shields.io/badge/packer-%23E7EEF0.svg?style=for-the-badge&logo=packer&logoColor=%2302A8EF) ![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white) ![Apache Groovy](https://img.shields.io/badge/Apache%20Groovy-4298B8.svg?style=for-the-badge&logo=Apache+Groovy&logoColor=white)


<h2 style="color: yellow;">Featured Projects</h2>

> \[!TIP]\
> All the source code for the mentioned projects is available in my github repo (or) just hover at the respective project name.

<h3><a href="https://github.com/RamaRaju-personal-org/webapp" style="color: #ADD8E6;">Project : Cloud Native Web Application</a></h3>

#### Tech stack used 
[![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)](https://cloud.google.com/)
[![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white)](https://www.terraform.io/)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
[![Packer](https://img.shields.io/badge/Packer-02A8EF?style=for-the-badge&logo=packer&logoColor=white)](https://www.packer.io/)
[![Google Cloud Functions](https://img.shields.io/badge/Google_Cloud_Functions-FF6F00?style=for-the-badge&logo=google-cloud&logoColor=white)](https://cloud.google.com/functions)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](https://github.com/features/actions)
[![Mailgun](https://img.shields.io/badge/Mailgun-F06A6A?style=for-the-badge&logo=mailgun&logoColor=white)](https://www.mailgun.com/)  

> \[!NOTE]\
> Web Application Repo:  https://github.com/RamaRaju-personal-org/webapp \
> Infra Repo : https://github.com/RamaRaju-personal-org/tf-gcp-infra

#### overview 
This Project comprises a cohesive collection of repositories intended to streamline the deployment of a secure, scalable, and highly available web application on the Google Cloud Platform (GCP). By leveraging Terraform for infrastructure automation, Google Cloud Functions for serverless execution, and Node.js for backend development, this project provides a robust solution for deploying and managing contemporary, cloud-native applications. Additionally, it utilizes Packer for creating immutable machine images, GitHub Actions for CI/CD, and ensures data security with encryption managed by Google Cloud Keys.

#### Architecture  
![flow drawio](https://github.com/RamaRaju-personal-org/webapp/assets/144737522/7798b670-f957-4417-9e13-ee4f579e6e36)

### Project Highlights
##### <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" style="height:16px; vertical-align: middle;"> : RESTful APIs 

The backend is built with Node.js, offering RESTful APIs for user management, including registration, profile retrieval, updates, and health checks. Secure access is maintained using Basic HTTP authentication and Base64 encoding. User passwords are securely stored in a MySQL database with Bcrypt hashing.

##### <img src="https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white)](https://www.terraform.io/" style="height:16px; vertical-align: middle;"> : Automated GCP Infrastructure 
Terraform is used for Infrastructure-as-Code (IaC) to automate and provision a secure GCP environment, including VPC, subnets, routes, firewalls, Compute Engine, Cloud SQL (MySQL database), Cloud Storage, Cloud Functions, load balancer, Cloud DNS, Google-managed SSL certificates, and encryption keys.

##### <img src="https://img.shields.io/badge/Packer-02A8EF?style=for-the-badge&logo=packer&logoColor=white)](https://www.packer.io/" style="height:16px; vertical-align: middle;"> : Immutable Server Deployments 
Packer and GitHub Actions are utilized to create immutable machine images with pre-built application artifacts, ensuring code integrity. Terraform provisions these images into VMs, eliminating manual SSH configurations. Deployment is automated with startup scripts that configure database connections and start the application.

##### <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" style="height:16px; vertical-align: middle;"> : CI/CD with GitHub Actions 
GitHub Actions is used to set up a CI/CD pipeline, automating testing and deployment.

##### <img src="https://img.shields.io/badge/Cloud_function-blue?style=for-the-badge&logo=google-cloud&logoColor=white" style="height:16px; vertical-align: middle;"> : Event-Driven User Verification  

Google Pub/Sub and Mailgun are used for email verification, sending unique verification links upon account creation. A Cloud Function and Cloud SQL handle the verification process, ensuring secure user registration and API access.

##### <img src="https://img.shields.io/badge/logs-blue?style=for-the-badge&logo=google-cloud&logoColor=white" style="height:16px; vertical-align: middle;">  : Application Logging and Metrics 

Structured JSON logging streams log data to Google Cloud Observability, enhancing diagnostic capabilities.

##### <img src="https://img.shields.io/badge/load_balancing-blue?style=for-the-badge&logo=google-cloud&logoColor=white" style="height:16px; vertical-align: middle;"> :  Scalability and Security 
The application leverages dynamic scaling, load balancing, security groups, IAM roles, and customer-managed encryption keys for enhanced scalability and security.






[![](https://visitcount.itsvg.in/api?id=ram&icon=5&color=1)](https://visitcount.itsvg.in)

 <img align="right" src="https://visitor-badge.laobi.icu/badge?page_id=RamaRaju-vj.RamaRaju-vj" />

<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=4000&lines=Hi+There!+👋;+I'm+Ram!;" />
</h1>

<h3> 👨‍💻 I’m currently a Software Engineering Grad Student @ Northeastern University.</h3>

<br/>



<div align="left"> 
  <a href="mailto:vadapalli.j@northeastern.edu">
    <img src="https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red" />
  </a>
  <a href="https://www.linkedin.com/in/ram-cloud-devops/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />
  </a>
  <a href="https://ram2305.github.io/Ram/" target="_blank">
     <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white" target="_blank" /> 
  </a>
  <a href="https://drive.google.com/file/d/1yvYPK-1jXzIpcqOzCIhybje7wtUzWMZz/view" target="_blank">
     <img src="https://img.shields.io/badge/-Resume-green?logo=resume&logoColor=white&style=for-the-badge" target="_blank" /> 
  </a>
 

 <hr/>

<h2 align="left">⚒️ Languages-Frameworks-Tools ⚒️</h2>
<br/>
<div align="left">
    <img src="https://skillicons.dev/icons?i=git,jenkins,githubactions,docker,kubernetes,ansible,terraform,aws,gcp"/>
    <img src="https://skillicons.dev/icons?i=nodejs,javascript,mysql,mongodb" /><br>
</div>

<h2 align="left">Featured Projects</h2>


<h3><a href="https://github.com/RamaRaju-personal-org/webapp" style="color: #ADD8E6;">Project : Cloud Native Web Application</a></h3>



#### Tech stack used for project
[![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)](https://cloud.google.com/)
[![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white)](https://www.terraform.io/)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
[![Packer](https://img.shields.io/badge/Packer-02A8EF?style=for-the-badge&logo=packer&logoColor=white)](https://www.packer.io/)
[![Google Cloud Functions](https://img.shields.io/badge/Google_Cloud_Functions-FF6F00?style=for-the-badge&logo=google-cloud&logoColor=white)](https://cloud.google.com/functions)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](https://github.com/features/actions)
[![Mailgun](https://img.shields.io/badge/Mailgun-F06A6A?style=for-the-badge&logo=mailgun&logoColor=white)](https://www.mailgun.com/)  

> \[!NOTE] \
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


<div align="center">
  <h2>🐍 My Contributions 🐍</h2>
  <br>
  <img alt="snake eating my contributions" src="https://raw.githubusercontent.com/RamaRaju-vj/RamaRaju-vj/output/github-contribution-grid-snake.svg" />
  
  <br/><br/><br/>
</div>

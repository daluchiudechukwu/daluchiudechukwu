## Daluchi Udechukwu
### DevOps Engineer
Hey there! I'm Daluchi, a DevOps engineer seeking to deliver exceptional solutions that align with business objectives. I have one year of experience implementing cloud solutions with Azure and AWS services. I've been trained in thoroughly comprehending clients' challenges and implementing cloud technologies tailored to specific needs. Join me on GitHub where I share some of the projects I have worked on, insights and codes reflecting my contribution in the tech ecosystem.
[LinkedIn](https://www.linkedin.com/in/daluchi-udechukwu/)
<div id="badges">
    <a href="https://www.linkedin.com/in/daluchi-udechukwu/">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="30px"/>
    </a>
    <a href="https://udechukwudaluchi.wixsite.com/my-site/projects-8">
          <img src="https://img.shields.io/badge/My Portfolio-8A2BE2" height="30px" />
    </a>
</div>

-----
## 💼LANGUAGES AND TOOLS
Here are some of the tools and languages I have experience with:

<div style="display: flex; justify-content: space-around;">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" width="100px"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azure/azure-original.svg" width="100px"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="70px"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="70px"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" width="70px"/>
    <img src="https://www.skedler.com/blog/wp-content/uploads/2021/08/grafana-logo.png" width="170px"/>
</div>

-----
## 👩‍💻 PROJECTS
### 1) Hosting and Caching of Static Website on AWS
Deployment and caching of a static website using Amazon S3 and CloudFront. The first step was to create a static web page using HTML and CSS. I uploaded my objects in a bucket, enabled the static website hosting configuration on Amazon S3, and enforced permissions to make my website publicly accessible. I then created a CloudFront distribution from my S3 bucket for website caching.
<img src="https://i.postimg.cc/FKpwzTBS/S3-static-hosting-architectural-diagram.png" alt="Alt text" style="width:auto;height:400px;">

#### Services Used in Project
+ Amazon S3: The static HTML, CSS, and JavaScript files of the website are hosted in an Amazon S3 bucket. S3 ensures high availability and low latency for serving these files to users globally.
+ Amazon CloudFront: Created a global distribution in some regions so that my website will be cached in these regions and will be easily accessible by users when needed. CloudFront enables low latency by caching at different regions.
+ AWS Certificate Manager: This adds a security layer to the HTTP traffic allowed to access the cached content on Amazon CloudFront. Certificate Manager allows for the provisioning and managing of TLS/SSL certificates for use with AWS or internal resources.
+ Others: VS code.
#### Project Deployment: https://github.com/daluchiudechukwu/CloudFront-Distribution-of-Static-Website

### 2) AWS End-to-End Serverless Math Application
Made a website that could calculate math exponents. Hosted the front web page of this website on AWS Amplify. I then created a lambda function to implement this math functionality. I implemented API gateway to use the lambda function and communicate with the website. I created an Amazon DynamoDB table to store math results from the website.
<img src="https://i.postimg.cc/25NpFjyF/math-app-architecture.png" alt="Alt text" style="width:auto;height:400px;">

#### Services Used in Project
+ AWS Amplify: The front end of the website was deployed on Amplify. AWS Amplify is used to deploy highly scalable web applications.
+ AWS Lambda: Supplied a Python code to drive events to calculate the math functionality for the math application. AWS Lambda is a serverless, event-driven compute service that lets you run code.
+ API Gateway: Implemented this to help facilitate the request and deliveries of data and services between AWS Lambda and the math application.
+ DynamoDB: Created a table to store the results from the math calculations from the application.
+ IAM: To set permissions for the execution of AWS Lambda.
+ Others: VSCode.
#### Project Deployment

### 3) Grafana Dashboard Integration with AWS CloudWatch
Deployed a web server on Amazon EC2 and integrated Grafana with Amazon CloudWatch to display a dynamic dashboard from the CPU Utilization metric data of my EC2 instance. Also integrated IAM to allow Grafana to make the executions.

#### Services Used in Project
+ Amazon EC2: Deployed a web server to generate metrics data for visualization. Amazon EC2 is a computing service.
+ Amazon CloudWatch: Implemented Grafana to collect CPU Utilization metrics data from Amazon CloudWatch to display visualization. Amazon CloudWatch is a monitoring service and metrics repository.
+ Grafana: Data visualization tool used to visualize CPU Utilization data from my virtual instance montiored by CloudWatch.
#### Project Deployment: https://github.com/daluchiudechukwu/Grafana-Dashboard-Integration-with-AWS-CloudWatch

### 4) Apache Web Server on Docker with Azure
Deployed a linux virtual machine as a docker host to build application as a docker image and utilize apache web server to display static web page.
[![Screenshot-2024-10-08-110712.png](https://i.postimg.cc/28cvNwQW/Screenshot-2024-10-08-110712.png)](https://postimg.cc/nCmMvqwV)
-----
[![Screenshot-2024-10-08-110915.png](https://i.postimg.cc/mDyzXNZt/Screenshot-2024-10-08-110915.png)](https://postimg.cc/cg6L63nS)
-----
[![Screenshot-2024-10-08-111503.png](https://i.postimg.cc/V6gvBf4t/Screenshot-2024-10-08-111503.png)](https://postimg.cc/7GCqqyFP)
-----
[![Screenshot-2024-10-08-153019.png](https://i.postimg.cc/QMkdh82z/Screenshot-2024-10-08-153019.png)](https://postimg.cc/HJngtgs0)
-----
[![Screenshot-2024-10-08-153324.png](https://i.postimg.cc/sx8VwvWM/Screenshot-2024-10-08-153324.png)](https://postimg.cc/Fky5KFDv)
-----
[![Screenshot-2024-10-08-154800.png](https://i.postimg.cc/J7d41dFR/Screenshot-2024-10-08-154800.png)](https://postimg.cc/4nVTPwZ0)
-----
[![Screenshot-2024-10-08-160020.png](https://i.postimg.cc/Jzj157zh/Screenshot-2024-10-08-160020.png)](https://postimg.cc/LJ6KHpfd)

#### Services Used in Project
+ Terraform: Used terraform to automate the deployment the azure virtual machine.
+ Docker: Installed docker on the VM and used it to build my application as docker image and run it as container.
+ Apache web server: Installed apache on docker image and copied application web content to replace default apache web page.
  

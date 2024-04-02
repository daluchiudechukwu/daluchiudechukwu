## Daluchi Udechukwu
### Cloud Solutions Architect / DevOps Engineer
Hey there! I'm Daluchi, a solutions architect seeking to deliver exceptional solutions that align with business objectives. I have one year of experience architecting cloud solutions with AWS services. I've been trained in thoroughly comprehending clients' challenges and implementing cloud technologies tailored to specific needs. Join me on GitHub where I share some of the projects I have worked on, insights and codes reflecting my contribution in the tech ecosystem.
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
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="70px"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="70px"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" width="70px"/>
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
#### Project Deployment: 

### 2) AWS End-to-End Serverless Math Application


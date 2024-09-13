-vProfile Multi-Server Application
Overview
vProfile is a cloud-based multi-server application designed to demonstrate the deployment of a scalable and reliable system using various AWS services. The project showcases a fully functional infrastructure using AWS Beanstalk, Memcache, RabbitMQ, S3, IAM roles, CloudWatch, and RDS for seamless deployment and management.

Table of Contents
Overview
Architecture
Features
Technologies Used
Setup and Installation
AWS Services
Application Structure
Usage
Contributing
License
Architecture
The architecture of the vProfile multi-server application follows a microservices pattern that ensures scalability and fault tolerance. The application components communicate using RabbitMQ, and caching is managed via Memcache to ensure high performance. The database runs on AWS RDS, and the entire system is monitored using AWS CloudWatch.


Features
Scalable Deployment: Utilizes AWS Elastic Beanstalk to automatically manage scaling.
High Performance Caching: Integrated with Memcache for data caching.
Asynchronous Messaging: RabbitMQ is used for reliable messaging between services.
Cloud Storage: S3 bucket for static asset storage.
Secure Access: Role-based access control using AWS IAM roles.
Monitoring & Logging: CloudWatch for real-time monitoring and logging.
Relational Database: AWS RDS to store application data.
Technologies Used
AWS Services: Beanstalk, S3, IAM, CloudWatch, RDS, Elastic Load Balancer (ELB), Memcache, RabbitMQ
Frontend: HTML, CSS, JavaScript
Backend: Java, Spring Boot
Database: MySQL (AWS RDS)
Messaging: RabbitMQ
Caching: Memcache
Version Control: Git
Deployment: AWS Elastic Beanstalk
Setup and Installation
Prerequisites
AWS account
Java 8 or higher
Maven
Git

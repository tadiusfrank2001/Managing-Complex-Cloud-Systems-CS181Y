# Managing-Complex-Cloud-Systems-CS181Y

## Overview
+ A practicum course designed to build and maintain the backend cloud services and human teams that are utilized to support and upkeep websites.
+ Learned the fundamentals of Cloud Engineering by building my our AWS backend to host our assigned website (4 weeks).
+ Learned the fundamentals of Site-Reliability by setting up a paging (PagerDuty) and web monitoring system (New Relic) to track uptime.
+ Scaled up our cloud system using a relational database, additional copy of production servers, elastic file system, and load balancer to handle a simulated DDos attck with bots.
+ Provided 24/7 monitoring and maintenance of website due to constant traffic spikes via bots, made 95% uptime each week for five weeks.

## Technology Used

### Cloud Back-End and Hosting

#### AWS Services

`Amazon EC2 (Elastic Compute Cloud)`: Provides scalable virtual servers to host your website's backend logic, applications, and databases.

`AWS Lambda`: Allows you to run backend code without provisioning servers. It's often used for creating serverless architectures, where you only pay for the compute time you consume.

`Amazon S3 (Simple Storage Service)`: Used to store and serve static content like images, videos, and other media files.

`Amazon RDS (Relational Database Service)`: Provides managed relational databases like MySQL, PostgreSQL, and others.

`Amazon Elastic File System (EFS)`: scalable file storage service provided by AWS (Amazon Web Services),  scales your storage capacity up or down as you add or remove files, without the need for manual intervention.

`AWS Load Balancer`: distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, and IP addresses. Mostly utilized for scaling up.

#### Servers
`Apache Tomcat`: open-source web server and servlet container developed by the Apache Software Foundation.

`Nginx`: high-performance web server and reverse proxy server. It's also used as a load balancer and HTTP cache. Mostly used for log information on the traffic via listening on our Port 443.

`Pkeep`: a  cloud-based service or platform that allows users to manageand maintain Python packages in a development environment.

### Database
`PostgreSQL`: open-source relational database management system (RDBMS). Version 15.


### Languages

`JavaScript`: OOP language used to write our `src` file which contains front-end code for our website's UI.

#### Site Monitoring Software

`PagerDuty`: an incident management and response platform designed to help organizations handle operational issues and ensure that systems and services remain available and performant. 

`New Relic`: a comprehensive observability platform that provides monitoring and performance management for applications, infrastructure, and digital experiences. It helps organizations gain insights into their systems, detect and troubleshoot issues, and optimize performance. 













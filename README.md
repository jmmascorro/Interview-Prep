# Interview-Prep

**Cloud & DevOps**

a. Cloud is computing services such as servers, storage, databases, networking, software ...etc over the internet with pay-as-you-go pricing. DevOps brings development and operations together. It is a software engineering practice that involves collaboration within teams during development of operations to enable instantaneous deployment of products and services by utilizing a continuous integration and continuous delivery approach along with an agile and flexible development method.  

b. I have used cloud services when deploying applications and node-api connected with databases from my local environment to an EC2 instance on AWS. I have been learning and using DevOps during the last 6 weeks of the training program within our project utilizing the tools such as trello, packer, terraform, jenkins, and testing during the development cycle of operations for our project.  

c. Using cloud services allows users to be able to obtain computing services on a pay-as-you-go basis, which cuts costs of actually having to purchace and own servers or storage. Being able to only pay and use what you need depending on your current usage state. DevOps allows integration of development and operations teams for consistancy and realiability during the development cyle utilizing the tools and practices to respond to frequent changes.

**CICD**

a. Continuous Integration and Continuous Delivery. This practice allows for automation in building, testing, and deployment of applications. 

b. Created a Jenkins Pipeline to integrate node-api project with testing and connected with webhooks through github repository to be able to trigger testing on my codebase when a push to main branch is done.  

c. Errors and security issues can be identified and fixed earlier throughout the development cycle and much more easily. Improves productivity and efficiency by streamlining workflow through built-in automation, testing, and collaborattion. 

**Jenkins**

a. Open Source automation server. It helps automate parts of software development related to building, testing, and deploying. 

b. Used Jenkins Pipeline to automate testing and the build of applications using connection through github repositories and webhooks to trigger during events specified during configuration of Jenkins. 

c. Allows for constant monitoring and instantaneous notifications of errors in development cycle. 

**Provisioning**

a. Process of setting up and configuring infrastructure and integration. 

b. Used provisioning scripts when setting up VagrantFile for vagrant environment to automate commands for integration and connection of application to virtual machine.
Used Terraform (IaC) to provision Infrastructure and configuration of an AWS instance using AMI id's created by packer. 

c. Manage and automate the infrastructure components allow efficiency and reduction of human error during development and deployment of applications.

**Networking**

a. Connecting computing devices to share and exchange data and resources. 

b. Used networking when creating Vagrant environment by connecting a database ip to an api application to be able to send data from api functions. Used networking when configuring terraform AWS instances by setting up gateway ip, VPN and subnetting for inbound and outbound connections. 

c. Benefits of compute networking are convenient resource sharing, setting security where neccessary, makes file sharing easier and faster, and creates a structured environment for communincation and security. 

**Principle of Least Priviledge**

a. Information security concept that that gives minimum levels of access or permissions to users to perform their duties/tasks or job. 

b. Coaches used Principle of Least Priviledge during our training of AWS resources. Permissions and limited access were set to our accounts to protect against "rookie mistakes" when working with AWS services. 

c. Reduced malware, enhances operational performance, and reduces the impact of human error. It strikes a balance between usability and the implementation of security protections.

**IAC**

a. Infrastructure as Code. It is the managing and provisioning of infrastructure using configuration files to establish a template for development through code. 

b. We used IAC in terraform to manage our application and api database build onto an AWS instance by setting up and configuring our files for integration. 

c. IaC avoids manual configuration over periods of time and enforces consistent environment states through well-documented code. Infrastructure deployments with IaC are repeatable and prevent runtime issues caused by configuration drift, missing dependencies, and human error. 

**Packer and Terraform**

a.Packer is an Open Source VM image creation tool. Terraform is an IaC tool that lets you build, change, and configure infrastructure tasks.

b. We used packer to configure a file to create an AMI image on AWS and that image was then used to be able to configure and provision our AWS EC2 instance using terraform by utilizing different resource blocks or plug-ins available. Following the documentation we were able to configure and create VPNs, subnets, route tables, gateway ips, and database connection to our application and build it all at once.

c. Packer images allow you to launch completely provisioned and configured machines quickly and effectively. Terraform makes it possible to spin up an entire infrastructure architecture by simply running a script. It reduces error from manually having to provision your infrastructure and allows constant collaboration within easily linked configuration files. 

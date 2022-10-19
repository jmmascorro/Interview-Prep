# Interview-Prep

**Cloud** 

a. Cloud is computing services such as servers, storage, databases, networking, software ...etc over the internet with pay-as-you-go pricing.   

b. I have used cloud services when deploying applications and node-api connected with databases from my local environment to an EC2 instance on AWS. 

c. Using cloud services allows users to be able to obtain computing services on a pay-as-you-go basis, which cuts costs of actually having to purchace and own servers or storage. Being able to only pay and use what you need depending on your current usage state. 

**DevOps**

a. DevOps brings development and operations together. It is a software engineering practice that involves collaboration within teams during development of operations to enable instantaneous deployment of products and services by utilizing a continuous integration and continuous delivery approach along with an agile and flexible development method.

b. I have been learning and using DevOps during the last 6 weeks of the training program within our project utilizing the tools such as trello, packer, terraform, jenkins, and testing during the development cycle of operations for our project.  

c. DevOps allows integration of development and operations teams for consistancy and realiability during the development cyle utilizing the tools and practices to respond to frequent changes.

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

**Packer**

a.Packer is an Open Source VM image creation tool. 

b. We used packer to configure a file to create an AMI image on AWS and that image was then used to be able to configure and provision our AWS EC2 instance using terraform by utilizing different resource blocks or plug-ins available.

c. Packer images allow you to launch completely provisioned and configured machines quickly and effectively. 

**Terraform**

a. Terraform is an IaC tool that lets you build, change, and configure infrastructure tasks.

b. Following the documentation we were able to configure and create VPNs, subnets, route tables, gateway ips, and database connection to our application and build it all at once.

c. Terraform makes it possible to spin up an entire infrastructure architecture by simply running a script. It reduces error from manually having to provision your infrastructure and allows constant collaboration within easily linked configuration files. 

**AMI**

a. An AMI is an Amazon Machine Image. It is a template that contains a software configuration for an operating system, application server, or an application. Using and AMI you can launch an instance, which is a copy of the AMI running as a virtual server in the cloud. 

b. We used AMI's in our terraform orchestration after we created the AMI's using packer.json configuration file in our application. The AMI's take a snapshot or image of our application state we want for our build and then we can take that AMI and use it in configuring the terraform files for our EC2 instances for our three-tier application build using AWS.

c. Using AMI's gives you the ability to quickly and effectively determine what computing power, memory, storage, and other factors you need for your applications. It provides a template for configuration of your application that can be used to quickly and easily update and configure your application build.

**VPC**

a. VPC stands for Amazon Virtual Private Cloud. It allows developers to create a virtual network for resources in an isolated section of the Amazon Web Services cloud. Users connect to VPC's through an Internet Gateway and can define network configurations such as IP address range and route tables or manage gateways and subnets.

b. We created an Amazon VPC using terraform to be able to configure our packer.json files to be able to create our AMI's for our applications. We were then able to use our AMI's and VPC's to configure and create our subnets, gateways, and route tables for our database and application module-tiers in our terraform files for our EC2 instances.

c. Amazon VPC gives you the ability to have full control over your virtual environment, including resources, connectivity, and security. You can instantly scale your resources up or down and allow for easly integration into your applications.

**Vagrant** 

a. Vagrant is a tool used for building and managing virtual machine environments in a single workflow. 

b. We used Vagrant to set up virtual environments for our applications to run on. Using shell scripting and VagrantFile configuration, we were able to create a Nodejs and mysql database environment on two seperate VM's. We used Bash scripts to provsion the environment through Vagrant. 

c. Vagrant helps automate the creation and mangement of Virtual Machines. It allows developers to set upo their environment quickly with only one command and is exactly the same as everyone else's by launching exact copies of the same machine in a repeatable and version controlled way.

**React**

a. React is an open-source front-end Javascript library for building user interfaces based on UI components.

b. We used react to help develop our front-end builds of our beer api application. We used it to handle our View layer of our application.

c. Benefits of using React are that its DOM is declarative which the UI is adjusted when developers change the app's state when interacting with the DOM and the ability to build and reuse seperate components that make up a larger UI and creating more complex UI functions through simple HTML and Javascript components.





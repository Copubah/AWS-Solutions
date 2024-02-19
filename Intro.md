# Introduction to Cloud 101
- Define cloud computing and describe the benefits
- Compare and Contrast cloud computing service and deployment models
- Identify the AWS Global Infrastructure
- Discuss the shared responsibility model
- Describe the well-architectured framework and its role in building flexible and reliable architectures



## Cloud computing
Cloud Computing is the on-demand delivery of I.T resources over the internet with the pay as you go model,resources can be servers,networks,storage or development.

## Benefits of Cloud computing
- Cost Efficiency: eliminates the need for upfront capital investments in hardware and infrastructure. Instead, users pay only for the resources and services they consume on a pay-as-you-go basis.

- Scalability and Flexibility: Cloud offers scalability, allowing users to scale resources up or down based on demand. 

- Accessibility and Mobility: Cloud computing enables users to access data, applications, and services from anywhere with an internet connection and on any device.

- Reliability and High Availability: Cloud providers offer robust infrastructure and data redundancy across multiple data centers, ensuring high availability and reliability of services.

- Security: Cloud providers invest heavily in security measures and compliance certifications to protect data and infrastructure from cyber threats and breaches. 

- Innovation and Time-to-Market: Cloud computing enables rapid innovation by providing access to a wide range of cutting-edge technologies, development tools, and third-party services. 

## Deployment models
- Infrastructure as a service(Iaas)-contains the basic building blocks for cloud,it provides access to networking features,computers(virtual or on dedicated hardware),and data storage
- Platform as a service(Paas)-the organizations do not need to manage the infrastructure,they focus on the deployment and management of applications
- Software as a service(Saas)-a completed software product that the service provider runs and manages

## Cloud computing deployment models
- Cloud;one can migrate existing applications to the cloud or you can design and build new applications in the cloud

- Hybrid;cloud-based resources are connected to on-premises infrastructure,cloud-based resources can be intergrated with legacy I.T applications

- On-premises;also known as private cloud deployment,resources are deployed on premises by using virtaulization and resource tool management tools

## AWS Global Infrastructure
- Main components of AWS global infrastructure are regions,availability zones and edge locations
1. Regions:have multiple AZs(availability zones)
2. Availability zones:have one or more data centres and different power supply companies
3. Edge locations:used by Cloudfront

## AWS ARCHITECTURE
- It is important to plan for failure for example when a file is stored in Amazon S3,it is copied into every AZ in that region so that if one AZ goes down you still have two copies of that file available
- Compute resources can also be spread out across several AZs to guarantee high availability so that if one goes down ,the architecture is still up and running
- Database;you can configure your database for multi-AZ deployment so that if your primary database fails,the other on standby takes over 


## AWS Shared responsibility
- AWS is responsible for the security of the cloud while the customer is responsible for security in the cloud


## AWS pricing models
- Pay-as-you-go;can be used based on need and not forecast
- Save when you reserve;offers savings plan over on-demand in exchange for a commitment to use a specific amount(measured in $/hour for a 1 or 3 year period)
- Pay less by using more;you can get get volume based discounts and save as your usage increases

## Billing examples
- Amazon EC2;you pay for only the compute time you use while your instances are running
- Amazon S3;you pay only for the storage you use
- AWS Lambda;you are charged based on the number of requests for your functions and the time taken for them to run
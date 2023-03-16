# CloudApplication

The cloud application was created for User Management Application developed in Node.Js as backend.
The entire infrastructure was implemented on AWS, utilizing several services. Following load testing, the architecture was carefully designed to ensure resilience, high availability, and fault tolerance.

* **CloudFormation** as Infrastructure as code tool
* **EC2** to launch servers
* **VPC, Subnet, Route Tables, Internet Gateway, Elastic IPs, Security Groups** for networking
* **Lambda** for serverless computing
* **RDS** for managed MySQL database
* **S3** for storing blob objects which were taken as input for user profile management
* **SQS** Messaging Queue
* **SNS** Notification for lambda, also added as trigger for lambda
* **Route53** as DNS Service
* **IAM** for Identity and Access Management
* **KMS** for Key Management
* **Cloud Watch** for monitoring the APIs
* **Elastic Load Balancer** to apply load balancing on the APIs for incoming traffic.
* **AWS Autoscaling** to apply autoscaling on EC2 to cater the increased load on application.

![csye6225-infra-designer](https://user-images.githubusercontent.com/90482355/200743401-07e5ec41-d7a2-4caa-922f-37099dd111cb.png)

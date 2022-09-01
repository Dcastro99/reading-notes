# ** AWS: Cloud Servers **

> ## AWS EC2

1. What is an EC2 Instance?

-  EC2 instance is an offering from AWS where the subscriber/user can rent the virtual server per hour and use it to deploy his/her own applications.

2. Name 2 use cases for EC2.

- networking and operating systems

3. Provide 1 reason to use ECS instead of Heroku.

- EC2 only charhges what I use and provides more features.

> ## EC2 For Humans

1. Where can we find EC2 on the AWS Console?

- Under compute

2. Explain the general difference between T2 Micro and XL.

T2
```
t2.micro = vCPU (1)	CPU Credit(6) Mem(1)	EBS-Only
Low to Moderate
```
XL
```
t2.xlarge	vCPU(4)	CPU Credits(54) Mem(16)	EBS-Only	Moderate
```

3. Explain a “Compute Cycle” to a non-technical friend.

- It is a cycle that is taken once the computer receives information from another computer.

> ## Elastic Beanstalk

1. What is Elastic Beanstalk?

- Beanstalk is a service that deploys, manages, and scales web apps and services.

2. Describe the relationship between EC2 and Elastic Beanstalk.

- It leverages them into its application allowing the user to intergrate the two.

3. Name some benefits of using Elastic Beanstalk.

- elastic Beanstalk handles load balancing, auto scaling, and application health monitoring.

> ### recources

- [instances](https://www.guru99.com/creating-amazon-ec2-instance.html)
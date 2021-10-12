# Lab 2 - EC2 and Auto-Scaling Group

## Goals
This lab is intended to provide you hands-on experience in configuring EC2 instance with Auto-scaling-group (ASG). There will be CPU load generation test, to simulate the traffic load handled by your instance, where you will observe the automatic scale out behavior once the ASG configuration is in place.

> ***Note**: Before you start, please pay attention on the instruction given on each steps, particularly on a) Lab prerequisite and b)Lab cleaning*

There are 6 checkpoints of this lab:

1. Complete the lab prerequisite
2. Create launch-template, to be used as template for new instance scaled from the ASG
3. Create auto scaling group, where you will configure the scaling policies
4. Create security group, used by the auto-scaling group to ensure you can access the instance from internet (not a best practice for production environment)
5. Testing the auto scaling scenario with CPU load generator
6. Lab tear down

## Lab Details

Please visit this link for the detail lab instruction [Lab 2: Auto Scaling Group](https://catalog.us-east-1.prod.workshops.aws/v2/workshops/f3a3e2bd-e1d5-49de-b8e6-dac361842e76/en-US/basic-modules/70-auto-scaling/ec2-auto-scaling)

**REMEMBER:** In this workshop we will use **ap-southeast-1** region instead.

> If you find **us-east-1a** in the guide, remember to change it to **ap-southeast-1a**

> If you find **us-east-1b** in the guide, remember to change it to **ap-southeast-1b**

Lab will be started on 14th October 2021 4.30PM. You can do the labs until Sunday 17th October 2021 12PM noon. 

## How to get points

1. Complete all the steps on [Lab 2: Auto Scaling Group](https://catalog.us-east-1.prod.workshops.aws/v2/workshops/f3a3e2bd-e1d5-49de-b8e6-dac361842e76/en-US/basic-modules/70-auto-scaling/ec2-auto-scaling)
2. Take screenshots on the following section:

    1. Browse your instance public IP, and take a snapshot of the main page with the "CPU generator" as the picture
    2. Take a snapshot of your launch template configuration from the console, just the "Instance Details" section.
    3. Take a snapshot of your auto scaling group configuration from the console, Details and Automatic Scaling section.
    4. Take a snapshot of your Auto-scaling-group Security-group inbound's rule. The source of this inbound rule should be referencing to your load-balancer's security group
    5. After few minutes running the CPU generator, observed your EC2 instances, and capture any additional EC2 instances from your EC2 console

3. Submit your screenshots via email to `velialee@amazon.com, effends@amazon.com, tirtawid@amazon.com`, not later than Sunday 17th October 2021 1PM.
4. We will validate the result & give 5 points for correct submission.

## How to get help
1. Reach out to the facilitator over Telegram group.
2. Tell the facilitator which step you are stuck on.
3. Share the screenshot of the lab on which you encounter the issue.


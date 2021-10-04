# Lab 1 - Basic VPC Networking

## Goals
This lab designed to give you hands-on experience configuring basic network in AWS account. You will create multiple network that can be communicate each other. You will also create multiple EC2 compute instance to simulate real-life scenario.

There are 4 checkpoints of the lab:

1. Creates 3 separate Virtual Private Cloud networks.
2. Create 3 EC2 instances in each VPC.
3. Create VPC Peering to establish connectivity between VPCs. You will validate that EC2 on different VPCs can communicate over VPC peering using `ping` command.
4. Create Transit Gateway as centralised connectivity across VPCs. You will validate that EC2 on different VPCs can communicate over Transit Gateway using `ping` command.

## Lab Details

Visit this link for the lab instruction [Lab 1: Multi-VPC Account Architecture](https://networking.workshop.aws/beginner/lab1.html).

**REMEMBER:** In this workshop we will use **ap-southeast-1** region instead.

> If you find **us-east-1a** in the guide, remember to change it to **ap-southeast-1a**

> If you find **us-east-1b** in the guide, remember to change it to **ap-southeast-1b**

Lab will be started on 7th October 2021 4.30PM. You can do the labs until Sunday 10th October 2021 12PM noon. 

## How to get points

1. Complete all the steps on [Lab 1: Multi-VPC Account Architecture](https://networking.workshop.aws/beginner/lab1.html)
2. Take screenshots on the following section:

    1. Show us all 3 VPCs ("VPC A", "VPC B", and "VPC C") you have created (from VPC console page)
    2. Show us the 3 EC2 ("EC2 VPC A - AZ1", "EC2 VPC B - AZ1", and "EC2 VPC C - AZ1") you have created (from EC2 console page)
    3. Show us the remote session you made to EC2 instance named "EC2 VPC A - AZ1"
    3. Show us the VPC Peering status (from VPC Peering console page)
    4. Show us the ping results when using VPC peering
    5. Show us the Transit Gateway status, Transit Gateway Attachment status (from Transit Gateway page)
    6. Show us the ping result after using Transit Gateway

3. Share your screenshots on the Slack channel, no more than Sunday 10th October 2021 1PM.
4. We will validate the result & give 5 points for correct submission.

## How to get help
1. Reach out to the facilitator over Slack channel.
2. Tell the facilitator which step you are stuck on.
3. Share the screenshot of the lab on which you encounter the issue.


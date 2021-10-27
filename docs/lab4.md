# Lab 4 - IAM Hands On Lab

## Goals
This lab is intended to provide you hands-on experience in configuring some of the IAM principals. You will be building the IAM policy and attach it to IAM identity, and then test the policy accordingly.

> ***Note**: Before you start, please pay attention on the instruction given on each steps, and please ensure you captured the right result before submitting it through email
There are 4 checkpoints of this lab:
1. Launch EC2 instance with tags
2. Create AWS IAM identities
3. Test the access for resources
4. Assign IAM Role for EC2 instance and test the access

## Lab Details
Please visit this link for the detail lab instruction [Lab 4: Identity and Access Management](https://catalog.us-east-1.prod.workshops.aws/v2/workshops/f3a3e2bd-e1d5-49de-b8e6-dac361842e76/en-US/basic-modules/30-iam/iam)
**REMEMBER:** In this workshop we will use **ap-southeast-1** region instead.

> If you find **us-east-1a** in the guide, remember to change it to **ap-southeast-1a**

> If you find **us-east-1b** in the guide, remember to change it to **ap-southeast-1b**

Lab will be started on 28th October 2021 4.30PM. You can do the labs until Sunday 31st October 2021 12PM noon. 

## How to get points
1. Complete all the steps on [Lab 4: Identity and Access Management](https://catalog.us-east-1.prod.workshops.aws/v2/workshops/f3a3e2bd-e1d5-49de-b8e6-dac361842e76/en-US/basic-modules/30-iam/iam)
2. Take screenshots on the following section:

    1. From lab: **Launch EC2 instances with tags**, take a snapshot of your EC2 instance tags
    2. From lab: **Create AWS IAM identities**, take a snapshot which shows that you can login to the console with the newly created identity. You can capture your top right corner, where you will find your login alias and new IAM user. 

        > You may want to use different browser/incognito to be able to get new AWS console login prompt
    
    3. From lab: **Test the Access for Resources**, take a snapshot of the result, when you try to stop the "prod instance" using "dev account"

    4. From lab: **Asign IAM Role for EC2 instance and test the access**, take a snapwhot of the following command :
    
        `aws s3 ls [your-s3-bucket-name]`

3. Submit your screenshots via email to `velialee@amazon.com, effends@amazon.com, tirtawid@amazon.com`, not later than Sunday 31st October 2021 1PM.
4. We will validate the result & give 5 points for correct submission.

## How to get help
1. Reach out to the facilitator over Telegram group.
2. Tell the facilitator which step you are stuck on.
3. Share the screenshot of the lab on which you encounter the issue.
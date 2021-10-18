# Lab 3 - Amazon RDS PostgreSQL

## Goals
This lab is intended to provide you hands-on experience in creating PostgreSQL database instance in Amazon Relational Database Service (RDS). You will run some foundational activities below: 

1. Create PostgreSQL database instance, 
2. Setup database client in Amazon Cloud9 to connect to the database instance,
3. Scaling database both vertically & horizontally, 
4. Setup Highly Available database & run failover test,
5. Perform backup & restore of the database instance,
6. (Optional) Monitor the performance,
7. (Optional) Setup custom paramater,
8. (Optional) Configure IAM database authentication
9. (Optional) Basic intro to PostgreSQL & `pgadmin`.


> ***Note**: Before you start, please pay attention on the instruction given on each steps, particularly on Lab Prerequisites*

There are 9 checkpoints of this lab:

1. Complete the lab Prerequisite (make sure you can access the Cloud9 instance).
2. Create RDS PostgreSQL database instance.
3. Setup & connect database SQL from Amazon Cloud9 instance.
4. Create RDS Read Replica & promote it as new database instance.
5. Scaling up the RDS instance.
6. Setup highly availability by enabling Multi-AZ & test the failover.
7. Configure automated & manual backup.
8. Restore database from the backup.
9. Upgrade database engine version.

## Lab Details

Please visit this link for the detail lab instruction [Lab 3:  Amazon RDS PostgresSQL Workshop](https://rdspg.workshop.aws/)

**REMEMBER:** In this workshop we will use **ap-southeast-1** region instead.

> If you find **us-east-1a** in the guide, remember to change it to **ap-southeast-1a**

> If you find **us-east-1b** in the guide, remember to change it to **ap-southeast-1b**

Lab will be started on 21st October 2021 4.30PM. You can do the labs until Sunday 24th October 2021 12PM noon. 

## How to get points

1. Complete all the steps on [Lab 3:  Amazon RDS PostgresSQL Workshop](https://rdspg.workshop.aws/) only on sections **Prerequisites** & **Foundation**.
2. Take screenshots on the following section:

    1. Take screenshot of the CloudFormation Outputs section (it should have Cloud9 URL, Lab VPC ID, and Database Security Group ID).
    2. Open your Cloud9 URL & take screenshot of your Cloud9 environment.
    3. Take screenshot of your RDS PostgreSQL instance, showing the Endpoint & port section in the Connectivity and security tab of the details page.
    4. Take screenshot of AWS Secret Manager (showing the detail view of your secret).
    5. Take screenshot of your Cloud9's terminal, showing the output of this SQL command: 
        
        `select current_user, current_database();`
    
    6. Take screenshot of database instance list (you should have original database instance & its read replica). Capture also the detail page for the read replica instance.
    7. Take screenshot of new database instance created after you promoted the read replica.
    8. Take screenshot of the first database instance status after you succesfully scale it up vertically (show the new instance size).
    9. Take screenshot of your first database instance after you enable Multi-AZ (including Secondary Zone info).
    10. After you complete failover test, take screenshot of email notification you received.
    11. Take screenshot of automated backup section. 
    12. Take screenshot of manual snapshot you have taken.
    13. Take screenshot of your newly restored database (from manual snapshot).
    14. Take screenshot of your database version after upgrade process completed.

3. Submit your screenshots via email to `velialee@amazon.com, effends@amazon.com, tirtawid@amazon.com`, not later than Sunday 24th October 2021 1PM.
4. We will validate the result & give 5 points for correct submission.

## How to get help
1. Reach out to the facilitator over Telegram group.
2. Tell the facilitator which step you are stuck on.
3. Share the screenshot of the lab on which you encounter the issue.


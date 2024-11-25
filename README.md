 # CREATE S3 BUCKET AND EC2 INSTANCES FOR LINUX AND WINDOWS
  ## AIM
       To Create S3 bucket and EC2 Instances for Linux and Windows.
## PROBLEM STATEMENT
       This experiment demonstrates the process of setting up cloud infrastructure on AWS by creating an S3 bucket for storage and EC2 instances to host Linux and Windows environments. The goal is to provide an overview of how to configure and interact with these resources effectively, along with commands and screenshots to document the process.

## ALGORITHM
 ### Steps 1:
 Log in to AWS Console
 ### Steps 2:
 Navigate to the S3 service.
Click on Create bucket.
Enter a Bucket name and select a Region.
Configure Bucket settings as required (e.g., versioning, public access).
Click on Create bucket to finalize.
 ### Steps 3:
 Go to the EC2 service.
Click on Launch Instance.
Select an Amazon Machine Image (AMI) for Linux (e.g., Amazon Linux 2).
Choose an Instance Type (e.g., t2.micro for free tier).
Configure Instance Details, Storage, and Security Group.
Review and click Launch with a key pair (or create one if needed).
 ### Steps 4:
 Return to the EC2 service and click Launch Instance.
Select a Windows AMI (e.g., Windows Server 2019).
Choose the Instance Type.
Configure Instance Details, Storage, and Security Group.
Review and launch with a key pair (for future login).
 ### Steps 5:
 Verify the status of both instances in the EC2 dashboard.
Connect to the Linux instance using SSH.
Connect to the Windows instance using RDP.


## OUTPUT
s3bucket
![n](https://github.com/user-attachments/assets/f654eca1-a3d1-4235-b0af-232f9a136a41)
EC2 INSTANCE(WINDOWS)
![s](https://github.com/user-attachments/assets/8cb30197-2937-4bfd-8817-9e9344c6f827)
![ss](https://github.com/user-attachments/assets/c8d8c1f2-8acb-4669-93ba-b94679a91c2f)



## RESULT
 Successfully created an S3 bucket and EC2 instances for both Linux and Windows, demonstrating cloud resource management on AWS.

  



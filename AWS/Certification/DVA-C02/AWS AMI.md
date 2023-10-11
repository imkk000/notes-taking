# AWS AMI
- Amazon Machine Image
- AMI are a **customization** of an EC2 instance
    - Add own software, configuration, OS, monitoring, etc
    - Faster boot / configuration time because all a software is pre-packaged
- AMI are built for a specific region (and can be copied across regions)
- Can launch EC2 instances from:
    - A Public AMI: AWS provided
    - Own AMI: make and maintain them yourself
    - An AWS Marketplace AMI: an AMI someone else made (and potentially sells)

## AMI Process
- Start an EC2 instance and customize it
- Stop the instance (for data integrity)
- Build an AMI: this will also create EBS snapshots
- Launch instances from other AMIs

![ami](./Images/ami_process.png)
# AWS Certified Cloud Practitioner (CCP) Project Portfolio

During this portion of the program, I studied for and received my AWS Certified Cloud Practitioner Certification. I also completed three hands-on projects which I documented on medium. I've linked those below. 

## Project 1: Level Up Bank Website Migration to AWS S3

### Overview

Level Up Bank, a fictional fintech startup, required a more cost-effective, scalable, and manageable solution for hosting its website. The decision was made to migrate their on-premises hosted website to Amazon S3 to leverage the benefits of cloud hosting.

### Achievements

- **Cost-Effectiveness**: Migrated the bank's website to AWS S3, significantly reducing hosting costs by leveraging S3's pay-for-what-you-use pricing model.
- **Scalability**: Ensured the website could handle varying levels of traffic without manual intervention, thanks to S3's scalability.
- **High Availability**: Achieved high availability and durability for the website, ensuring 24/7 customer access without downtime.
- **Simplified Management**: Reduced operational overhead for the bank's IT team, allowing them to focus on core business objectives.

### Technical Implementation

- Configured an S3 bucket for static website hosting and uploaded the `index.html` file.
- Enabled public access and set up the bucket policy for website hosting.
- Implemented an optional advanced setup using AWS CloudFront to enhance global performance through edge caching and ensured secure access via HTTPS.

## Project 2: Secure Remote Administration of EC2 Instances

### Overview

Level Up Corporation faced challenges in securely and efficiently managing their fleet of 100+ EC2 instances. The solution was to implement SSH and RDP for secure, remote administration of Linux and Windows servers, respectively.

### Achievements

- **Enhanced Security**: Implemented SSH and RDP to provide encrypted and secure channels for remote server administration, safeguarding against unauthorized access.
- **Improved Efficiency**: Enabled the IT team to manage and troubleshoot servers remotely, reducing downtime and enhancing productivity.
- **Cost Savings**: Minimized operational costs and potential financial losses associated with server issues through prompt and efficient remote administration.

### Technical Implementation

- Deployed EC2 instances with appropriate security groups to allow SSH (Linux) and RDP (Windows) access.
- Demonstrated the ability to securely connect to and administer EC2 instances remotely.
- For an advanced layer of security, configured the Linux instance to use AWS Systems Manager (SSM) instead of SSH, eliminating the need for open SSH ports.

## Bonus Project: Secure Access Control for Level Up Solutions

### Overview

Level Up Solutions needed a comprehensive strategy for secure and controlled access to their AWS resources, critical for protecting sensitive data and maintaining operational efficiency.

### Achievements

- **Role-Based Access Control**: Implemented IAM policies to align access permissions with job roles, enhancing security and operational efficiency.
- **Scalable Security Model**: Established a scalable and secure access control model that can be adapted as the company grows and onboards more employees.

### Technical Implementation

- Created IAM groups with specific permissions for Developers, Management, and Help Desk roles, ensuring access is aligned with job responsibilities.
- Deployed and tested access control by verifying the capabilities of each group, ensuring strict adherence to the principle of least privilege.

---

This portfolio represents a snapshot of my hands-on experience with AWS services, reflecting my ability to apply cloud concepts and best practices to solve real-world problems. Thank you for exploring my projects.


# CloudAudit


![image](https://github.com/user-attachments/assets/7e423387-a4dd-40f6-b443-403bdbbc1fa4)

<img width="643" alt="image" src="https://github.com/user-attachments/assets/8e2319a0-43d4-4c90-8295-2690d7c7ab5b">


# High level architecture

![image](https://github.com/user-attachments/assets/23342e43-4c08-4e57-84fb-1cf69dc9fe09)





CloudAudit is an open-source tool designed for auditing security configurations across various cloud platforms, including AWS, Azure, and Google Cloud Platform (GCP). These scripts help identify misconfigurations and compliance issues based on industry standards such as CIS benchmarks.

## Features
- Audits IAM, storage, and compute resources for AWS, Azure, and GCP.
- Identifies over-permissive roles, insecure configurations, and compliance issues.
- Easy-to-use scripts that can be run locally or in cloud environments.

## Cloud Platforms Supported
- **AWS**: Amazon Web Services
- **Azure**: Microsoft Azure
- **GCP**: Google Cloud Platform

## Installation

To get started, clone this repository to your local machine:

git clone https://github.com/yourusername/CloudAudit.git
cd CloudAudit

## Prerequisites
Python 3.x (for AWS and GCP scripts)
PowerShell (for Azure scripts)
Appropriate permissions and access to your cloud environment

## Usage
## AWS
To audit IAM on AWS:
bash
Copy code
python aws/iam_audit.py

To audit S3 buckets:
bash
Copy code
bash aws/s3_audit.sh

To audit EC2 instances:
bash
Copy code
python aws/ec2_audit.py

## Azure
To audit Azure Active Directory:
powershell
Copy code
.\azure\azure_ad_audit.ps1

To audit Azure Storage Accounts:
powershell
Copy code
.\azure\storage_audit.ps1

To audit Azure Virtual Machines:
powershell
Copy code
.\azure\vm_audit.ps1

## GCP
To audit GCP IAM:
bash
Copy code
python gcp/gcp_iam_audit.py

To audit GCP Storage:
bash
Copy code
python gcp/gcp_storage_audit.py

To audit GCP Compute Engine:
bash
Copy code
python gcp/gcp_compute_audit.py

Documentation
Refer to the following guides for detailed usage instructions:

## AWS Audit Guide
## Azure Audit Guide
## GCP Audit Guide

Contributing
We welcome contributions to improve this toolkit! Please see CONTRIBUTING.md for guidelines on how to contribute.

License
This project is licensed under the Apache License 2.0. See the LICENSE file for details.


Contact
For any inquiries or feedback, please reach out to rajshekaryasani@gmail.com

Feel free to make any further adjustments or let me know if there's anything else you'd like to include!





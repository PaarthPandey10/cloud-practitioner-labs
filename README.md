# Cloud Practitioner Labs

> Hands-on AWS assignments from Cloud Quest: Cloud Practitioner — building real cloud skills with real services.

---

## Table of Contents

- [About](#about)  
- [Project Structure](#project-structure)  
- [Usage / How to Use](#usage--how-to-use)  
- [Features / Highlights](#features--highlights)  
- [Technologies Used](#technologies-used)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact](#contact)

---

## About

This repository contains 12 real-world AWS assignments completed as part of **Cloud Quest: Cloud Practitioner**, a gamified hands-on experience by AWS.  
Each lab explores foundational AWS services like EC2, S3, VPC, IAM, RDS, DynamoDB, and more.

---

## Project Structure
```
cloud-practitioner-labs/
├── a01-static-web-hosting/
│   ├── README.md
│   ├── a01-visual-guide.md
│   └── screenshots/
│       ├── 0-plan-overview.png
│       ├── 1-s3-console.png
│       ├── 2-rename-file.png
│       ├── 3-enable-static-web-hosting.png
│       ├── 4-test-website.png
│       └── 5-validate-assignment.png
│
├── a02-launch-ec2-instance/
│   ├── README.md
│   ├── a02-visual-guide.md
│   └── screenshots/
│       ├── 0-plan-overview.png
│       ├── 1-s3-console.png
│       ├── 2-download-data.png
│       ├── 3-ec2-console.png
│       ├── 4-ec2-config-1.png
│       ├── 5-ec2-config-2.png
│       ├── 6-ec2-config-3.png
│       ├── 7-ec2-config-4.png
│       ├── 8-ec2-config-5.png
│       ├── 9-ec2-user-data.png
│       ├── 10-launched-ec2.png
│       ├── 11-ec2-running.png
│       └── 12-validated.png
│
├── a03-scale-ec2-instance/
│   ├── README.md
│   ├── a03-visual-guide.md
│   └── screenshots/
│       ├── 00-plan-overview.png
│       ├── 01-aws-console.png
│       ├── 02-ec2-console.png
│       ├── 03-filter-instance-types.png
│       ├── 04-instance-running.png
│       ├── 05-ec2-instance-connect-ssh.png
│       ├── 06-connected-ec2-instance-cli.png
│       ├── 07-instance-settings-edit-user-data.png
│       ├── 08-stop-instance.png
│       ├── 09-start-instance.png
│       ├── 10-stop-instance-change-type.png
│       ├── 11-change-type-console.png
│       ├── 12-type-changed.png
│       ├── 13-new-type-running.png
│       └── 14-validated-diy.png
│
├── a04-secure-network/
│   ├── README.md
│   ├── a04-visual-guide.md
│   └── screenshots/
│       ├── 00-plan-overview.png
│       ├── 01-ec2-console.png
│       ├── 02-copy-web-server-instance-ip.png
│       ├── 03-site-timeout.png
│       ├── 04-instance-networking-console.png
│       ├── 05-subnet-console.png
│       ├── 06-subnet-routes-console.png
│       ├── 07-edit-routes.png
│       ├── 08-updated-routes.png
│       ├── 09-security-group-console.png
│       ├── 10-edit-rules.png
│       ├── 11-updated-sg-console.png
│       ├── 12-add-all-traffic-rule.png
│       ├── 13-copy-updated-instance-ip.png
│       ├── 14-test-ip.png
│       ├── 15-db-sg-console.png
│       ├── 16-edit-db-sg-rules.png
│       └── 17-validated-diy.png
│
├── a05-pricing-calculator-ec2/
│   ├── README.md
│   ├── a05-visual-guide.md
│   └── screenshots/
│       ├── 00-plan-overview.png
│       ├── 01-pricing-calc.png
│       ├── 02-pricing-calc-console.png
│       ├── 03-create-group.png
│       ├── 04-added-group.png
│       ├── 05-find-ec2.png
│       ├── 06-ec2-config.png
│       ├── 07-ec2-config2.png
│       ├── 08-ec2-config3.png
│       ├── 09-ec2-config4.png
│       ├── 10-ec2-config5.png
│       ├── 11-ec2-estimated-plan.png
│       ├── 12-ec2-config6.png
│       ├── 13-ec2-config7.png
│       ├── 14-ec2-config8.png
│       ├── 15-added-ec2-estimate.png
│       ├── 16-review-dev-support.png
│       ├── 17-share-estimate.png
│       ├── 18-edit-ec2.png
│       ├── 19-change-type.png
│       ├── 20-share-updated.png
│       └── 21-validated-diy.png
│
├── a06-create-rds-instance/
│   ├── README.md
│   ├── a06-visual-guide.md
│   └── screenshots/
│       ├── 00-plan-overview.png
│       ├── 01-click-ami-catalog-in-ec2-console.png
│       ├── 02-review-sql-search.png
│       ├── 03-review-database-search-click-aurora&rds.png
│       ├── 04-aurora&rds-console-create-database.png
│       ├── 05-database-config1.png
│       ├── 06-database-config2.png
│       ├── 07-database-config3.png
│       ├── 08-database-config4.png
│       ├── 09-database-config5.png
│       ├── 10-database-config6.png
│       ├── 11-database-config7.png
│       ├── 12-database-config8.png
│       ├── 13-database-config9.png
│       ├── 14-database-instance-created.png
│       ├── 15-review-database-actions.png
│       ├── 16-recommendations-database-migration-console.png
│       ├── 17-review-dms-options.png
│       ├── 18-create-actions-click-read-replica.png
│       ├── 19-read-replica-config.png
│       ├── 20-read-replica-created.png
│       └── 21-validated-diy.png
│
├── LICENSE
└── README.md
```
---

## Usage / How to Use

Each folder contains a lab with:
- Summary of the objective
- Key concepts or AWS services used
- Screenshots or walkthrough notes

Start from A1 and move through for a complete foundational experience.

---

## Features / Highlights

- Built and hosted a static website on S3  
- Launched and connected EC2 instances  
- Configured VPC and Internet Gateways  
- Peered VPCs and estimated AWS pricing  
- Secured access using IAM  
- Implemented Auto Scaling and High Availability

---

## Technologies Used

- **AWS Services**: EC2, S3, VPC, RDS, IAM, EFS, ELB, DynamoDB, ASG  
- **Platform**: AWS Skill Builder – Cloud Quest (Free sandbox)  
- **Tools**: AWS Console

---

## Contributing

Not open for contributions — personal practice lab showcase.

---

## License

This project is licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

You are free to:
- Share — copy and redistribute the material in any medium or format  
- Adapt — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.

🔗 [View License](https://creativecommons.org/licenses/by/4.0/)

---

## Contact

**Paarth Pandey**  
[LinkedIn](https://www.linkedin.com/in/paarth-pandey-13779529b/) | [GitHub](https://github.com/paarthpandey10) | paarthdxb@gmail.com

---

> Author: [Paarth Pandey](https://github.com/paarthpandey10)
> 
> **Note:** All labs in this repository are based on the official AWS Cloud Quest: Cloud Practitioner program.  
> Screenshots and flows are reused respectfully for learning and documentation purposes only.
>
> AWS Cloud Quest: Cloud Practitioner

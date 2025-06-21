# Walkthrough – A5: EC2 Pricing Calculator

> Use the AWS Pricing Calculator to estimate the monthly cost of EC2 instances.

---

## Objective

To configure an EC2 instance with specific requirements and estimate its monthly cost using the AWS Pricing Calculator.

---

## Step-by-Step Instructions

### ✅ Step 0 – Plan Overview

![Plan Overview](./screenshots/00-plan-overview.png)

---

### ✅ Step 1 – Open Pricing Calculator

- Go to the AWS Pricing Calculator. 
- Click on 'Create Estimate' button.

![Pricing Calc](./screenshots/01-pricing-calc.png)

---

### ✅ Step 2 – Console Navigation

- In the calculator console, head to 'My Estimate'.

![Pricing Console](./screenshots/02-pricing-calc-console.png)

---

### ✅ Step 3 – Create a Group

- In the new console, click on 'Create Group'.
- Name the group eg: Web Servers.
- Click on 'Create Group' button.

![Create Group](./screenshots/03-create-group.png)

### ✅ Step 4 - Add Service

- Confirm added Web Servers group.
- Click on 'Add Service'.

![Added Group](./screenshots/04-added-group.png)

---

### ✅ Step 4 – Add EC2 to Estimate

- Search for EC2 and add it to the group by click on 'Configure'.

![Find EC2](./screenshots/05-find-ec2.png)

---

### ✅ Step 5 – Configure EC2 - 1

- Provide a description for the estimate.
- Confirm that the region is US-Virginia (us-east-1-a).
- Set:
- Tenancy = Shared Instances
- Opearting System = Linux
- Workloads = Daily spike traffic
- Workload days = (Select all)

![Config 1](./screenshots/06-ec2-config.png)  

- Set: 
- Baseline = 2
- Peak = 4
- Hours = 8
- Minutes = 0

![Config 2](./screenshots/07-ec2-config2.png)

- Under EC2 Instances, set:
- vCPUs = 2
- Memory = 4 GiB
- Network performance = Any Network Performance
- Then select the 't3.medium' instance type.

![Config 3](./screenshots/08-ec2-config3.png)

- Under Payment options select 'On-demand'.

![Config 4](./screenshots/09-ec2-config4.png)

- Review 'Other purchasing options' and calculations.
- Click on estimated workload hours. 

![Config 5](./screenshots/10-ec2-config5.png)

--- 

### ✅ Step 6 - EC2 Estimated Workload Hours. 

- Review and confirm estimated workload hours cost.

![Estimated Plan](./screenshots/11-ec2-estimated-plan.png)

--- 

### ✅ Step 7 – Configure EC2 - 2

- Under Amazon Elastic Block Store (EBS), set:
- Storage = General Purpose SSD (gp3)
- IOPS = 30
- Storage amount = 10 GB

![Config 6](./screenshots/12-ec2-config8.png)

- Scroll down to find and set:
- Snapshot Frequency = Weekly
- Amount charged per snapshot = 1 GB
- Expand Data transfer and set:
- Data transfer from = Internet
- Amount = 1
- Data Amount = TB per month

![Config 7](./screenshots/13-ec2-config8.png)

- Under Outbound Data Transfer, set:
- Data transfer to = Internet (0...)
- Enter Amount = 100
- Data amount = GB per month
- Review calculations and click on 'Save and add service'.

![Config 8](./screenshots/14-ec2-config8.png)

---

### ✅ Step 7 – Add EC2 to Final Estimate

- Confirm added EC2 service estimate. 

![Added EC2](./screenshots/15-added-ec2-estimate.png)

---

### ✅ Step 8 – Add Support

- Navigate to add support and review 'Developer support plan'.
- Click on Cancel. 

![Dev Support](./screenshots/16-review-dev-support.png)

---

### ✅ Step 9 – Share Estimate

- Use "Share" option to generate a link.

![Share Estimate](./screenshots/17-share-estimate.png)

---

### ✅ Step 10 – Edit and Update

- Click on pencil icon in 'My Estimate' beside 'Amazon EC2'.

![Edit EC2](./screenshots/18-edit-ec2.png)  

- Navigate EC2 Instance types console and find and select 't2.micro'.
- Click on 'Update'.
![Change Type](./screenshots/19-change-type.png)

- Generate new share link and paste in AWS Cloud Quest validation box. 

![Updated Estimate](./screenshots/20-share-updated.png)

---

### ✅ Step 11 – Validate in Cloud Quest

- Validate the DIY activity. 

![Validated](./screenshots/21-validated-diy.png)

---

## What I Learned

- Navigating AWS Pricing Calculator  
- Configuring EC2 costs with precise control  
- Estimating monthly spend with support  
- Sharing and modifying estimates  

---

## Notes

- This lab used AWS Skill Builder sandbox  
- No billing is charged during this process  
- No CLI, IAM, or manual JSON used  

---

## Contact

For any questions or feedback, reach out:  
**Paarth Pandey**  
[LinkedIn](https://www.linkedin.com/in/paarth-pandey-13779529b/) | [GitHub](https://github.com/paarthpandey10) | paarthdxb@gmail.com

---

## Credits

Based on AWS Cloud Quest: Cloud Practitioner by AWS Skill Builder.  
Used under fair use for educational documentation.

—

> Author: [Paarth Pandey](https://github.com/paarthpandey10)  
> AWS Cloud Quest: Cloud Practitioner

# Walkthrough – A4: Secure Network

> Modify route tables and security groups to fix network issues for an EC2-hosted web server.

---

## Objective

To troubleshoot EC2 network issues by editing subnet route tables and inbound security group rules to allow proper public access and secure DB communication.

---

## Step-by-Step Instructions

### ✅ Step 0 – Plan Overview

![Plan](./screenshots/00-plan-overview.png)

---

### ✅ Step 1 – Open EC2 Console

- Start your AWS lab. 
- Search for EC2 service from the search bar and click on it. 

![EC2 Console](./screenshots/01-ec2-console.png)

---

### ✅ Step 2 – Copy Web Server Public IP

- Click on Instances and select the web server instance.
- Copy its public IPv4 address. 

![Copy IP](./screenshots/02-copy-web-server-instance-ip.png)

---

### ✅ Step 3 – Observe Site Timeout

- Paste the copied address in a new browser tab.
- Confirm that the site is not responding i.e. site timeout error message shown. 

![Timeout](./screenshots/03-site-timeout.png)

---

### ✅ Step 4 – Check Networking Panel

- Head back to instances and select the web server instance.
- Navigate over to Networking tab and click on the shown subnet ID.

![Networking](./screenshots/04-instance-networking-console.png)

---

### ✅ Step 5 – Open Subnet Console

- In the opened subnet console, select the shown network subnet.
- Head to the Route Table tab and locate the route table address.
- Click on the shown route table address. 

![Subnet](./screenshots/05-subnet-console.png)

---

### ✅ Step 6 – Open Route Table

- In the route table console, head over to the Routes tab.
- Click on Edit Routes button. 

![Route Table](./screenshots/06-subnet-routes-console.png)

---

### ✅ Step 7 – Edit Routes

- In the new console, click on Add route.
- Select Destination as 0.0.0.0/0. 
- Select Target as Internet Gateway

![Edit Routes](./screenshots/07-edit-routes.png)

---

### ✅ Step 8 – Updated Route Saved

- Click on Save Changes.
- Confirm that the settings have updated. 

![Updated Routes](./screenshots/08-updated-routes.png)

---

### ✅ Step 9 – Open Security Group Console

- Open Web Server Security Group console and click on Edit inbound rules. 

![SG Console](./screenshots/09-security-group-console.png)

---

### ✅ Step 10 – Edit Rules

- Modify rules to match the configurations as shown in the screensho. 

![Edit Rules](./screenshots/10-edit-rules.png)

---

### ✅ Step 11 – Updated SG Rules

- Confirm that the inbound rules have taken place.
- Now head over to the Outbound rules tab for the web server security group.
- Click on Edit outbound rules. 

![Updated Rules](./screenshots/11-updated-sg-console.png)

---

### ✅ Step 12 – Add All Traffic Rule

- In the console click on Add rule.
- Match the configurations of the new rule with the ones shown in screenshot. 

![All Traffic](./screenshots/12-add-all-traffic-rule.png)

---

### ✅ Step 13 – Copy Updated Public IP

- Click on Save Changes. 
- Head back to Web Server instance to copy its IPv4 address. 

![Updated IP](./screenshots/13-copy-updated-instance-ip.png)

---

### ✅ Step 14 – Test Website Access

- Paste the copied address in a new browser tab.
- Confirm that the address is working now. 

![Test IP](./screenshots/14-test-ip.png)

---

### ✅ Step 15 – Open DB SG Console

- Open the DB Server SG console.

![DB SG](./screenshots/15-db-sg-console.png)

---

### ✅ Step 16 – Edit DB SG Rules

- Click on Inbound rules tab and click Edit inbound rules.
- Click on Add rule.
- Match the new rule's configurations with the ones shown in screenshot.
- Save changes. 

![Edit DB SG](./screenshots/16-edit-db-sg-rules.png)

---

### ✅ Step 17 – Validate in Cloud Quest

- Paste the name of the DB Server Security Group in AWS Cloud Quest console.
- Validate DIY.

![Validated](./screenshots/17-validated-diy.png)

---

## What I Learned

- Route table modification for subnets  
- Security group rule logic and access controls  
- Fixing timeouts using networking tools  
- Public/private IP-based access verification  

---

## Notes

- All steps completed in AWS sandbox environment  
- Verified solution using web browser only  
- No CLI or paid resources used

---

## Contact

**Paarth Pandey**  
[LinkedIn](https://www.linkedin.com/in/paarth-pandey-13779529b/) | [GitHub](https://github.com/paarthpandey10) | paarthdxb@gmail.com

---

## Credits

This lab is based on [AWS Cloud Quest: Cloud Practitioner](https://explore.skillbuilder.aws/learn/course/external/view/elearning/13415/aws-cloud-quest-cloud-practitioner), provided by AWS Skill Builder.  
Visuals, objectives, and task flows belong to Amazon Web Services, Inc. and are used under fair use for personal learning documentation.

—

> Author: [Paarth Pandey](https://github.com/paarthpandey10)  
>  
> AWS Cloud Quest: Cloud Practitioner

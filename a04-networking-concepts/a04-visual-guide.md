# Visual Guide – A4: Secure Network

> Modify route tables and security groups to fix network issues for an EC2-hosted web server.

---

## Step-by-Step Screenshots

### ✅ Step 0

![Step 0](./screenshots/00-plan-overview.png)

---

### ✅ Step 1

![Step 1](./screenshots/01-ec2-console.png)

---

### ✅ Step 2

![Step 2](./screenshots/02-copy-web-server-instance-ip.png)

---

### ✅ Step 3

![Step 3](./screenshots/03-site-timeout.png)

---

### ✅ Step 4

![Step 4](./screenshots/04-instance-networking-console.png)

---

### ✅ Step 5

![Step 5](./screenshots/05-subnet-console.png)

---

### ✅ Step 6

![Step 6](./screenshots/06-subnet-routes-console.png)

---

### ✅ Step 7

![Step 7](./screenshots/07-edit-routes.png)

---

### ✅ Step 8

![Step 8](./screenshots/08-updated-routes.png)

---

### ✅ Step 9

![Step 9](./screenshots/09-security-group-console.png)

---

### ✅ Step 10

![Step 10](./screenshots/10-edit-rules.png)

---

### ✅ Step 11

![Step 11](./screenshots/11-updated-sg-console.png)

---

### ✅ Step 12

![Step 12](./screenshots/12-add-all-traffic-rule.png)

---

### ✅ Step 13

![Step 13](./screenshots/13-copy-updated-instance-ip.png)

---

### ✅ Step 14

![Step 14](./screenshots/14-test-ip.png)

---

### ✅ Step 15

![Step 15](./screenshots/15-db-sg-console.png)

---

### ✅ Step 16

![Step 16](./screenshots/16-edit-db-sg-rules.png)

---

### ✅ Step 17

![Step 17](./screenshots/17-validated-diy.png)

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

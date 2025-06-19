# Walkthrough – A1: Static Web Hosting

> Host a static website using Amazon S3 with public access and default settings.

---

## Objective

To host a basic static website using Amazon S3 by enabling static hosting, renaming HTML files, and accessing the site via the generated endpoint.

---

## Disclaimer

The screenshots and lab flow included in this walkthrough are sourced from the official AWS Cloud Quest: Cloud Practitioner platform.  
They are used here strictly for educational purposes, to document and demonstrate hands-on progress in AWS services.

---

## Step-by-Step Instructions

### ✅ Step 0 – Plan Overview

- Here is the plan over view. 

![Plan Overview](./screenshots/00-plan-overview.png)


### ✅ Step 1 – Open Amazon S3 from AWS Console

- Search S3 in the search bar and click on it. 

![Open Console](./screenshots/01-s3-console.png)

---

### ✅ Step 2 – Choose website-bucket and Rename

- Find the object with a name starting with "website-bucket" and click on it. 
- Find the file named "text.html" and rename it to "error.html".

![Rename File](./screenshots/02-rename-file.png)

---

### ✅ Step 3 – Enable Static Website Hosting for website-bucket

- Navigate over to "Edit static website hosting" in website-bucket's properties.
- Set static website hosting to "Enable".
- Set hosting type to "Host a static website".
- Specify index document as "index.html".
- Specify error document as "error.html".
- Save changed.

![Static Website Hosting](./screenshots/03-enable-static-web-hosting.png)


---

### ✅ Step 4 – Test Website

- Copy the bucket website endpoint.
- Go to a new browser tab.
- Paste the copied link.
- Your site is live.

![Site Live](./screenshots/04-test-website.png)

---

### ✅ Step 5 – Rename index.html

- Go back to s3 console and click on website-bucket.
- Rename index.html to waves.html.
- Copy website-bucket name and paste in Cloud Quest validation text box.

![Validated](./screenshots/05-validate-assignment.png)

---

## What I Learned

- How to access an S3 bucket  
- How to enable static website hosting  
- How to housekeep files in S3

---

## Notes

- This lab is part of AWS Cloud Quest: Cloud Practitioner  
- Done using AWS Skill Builder sandbox — no billing or CLI used  
- No IAM config or versioning involved in this lab

---

## Contact

For any questions or feedback, reach out:  
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

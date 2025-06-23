# 🔐 AWS IAM Cloud Security Project

This project focuses on **cloud security and access management using AWS IAM (Identity and Access Management)**. I explored how to set permissions, control user access, and secure AWS resources effectively by creating and testing custom IAM policies.

## 🚀 Project Overview
- **Goal:** Secure AWS resources by creating IAM users, user groups, and applying JSON-based IAM policies.
- **Services Used:** Amazon EC2, AWS IAM

## 🔧 Key Tasks Completed
- Created IAM users and user groups
- Set up account aliases for simplified login
- Defined tags to categorize EC2 instances as either `production` or `development`
- Wrote and applied a **custom JSON IAM policy**:
  - Allowed full access to EC2 instances tagged `development`
  - Denied access to `production` instances
  - Restricted actions like tag deletion or creation
- Logged in as an IAM user to test permissions
- Verified the policy by:
  - Successfully stopping the `development` instance
  - Denying access when attempting to stop the `production` instance

## 📚 What I Learned
- IAM fundamentals: users, groups, policies, account aliases
- Tagging resources for more granular security control
- Writing and understanding JSON-based IAM policies (Effect, Action, Resource)
- How permissions dynamically restrict or allow actions within the AWS environment
- How to test cloud security configurations through real-time instance management

## ⏱️ Project Duration
Approx. **1.5 hours**

## 🔑 Challenges Faced
The most challenging part was understanding IAM policies written in JSON, especially managing multiple permission statements. However, seeing the **"Access Denied"** error when expected was a rewarding confirmation that the policy worked correctly.

## 📸 Screenshots
All step-by-step screenshots and policy examples are included in this repository.

## 🔗 LinkedIn Post
[View my project update on LinkedIn] https://www.linkedin.com/posts/muzya-vida-musokotwane-3b9922293_cloud-security-with-aws-iam-activity-7343053119271927808-z_Js?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEcmTb0B88cHxzNSKZNbsTYpXUOIh5j4XGQ 

## 🔮 What's Next
I’ll continue building my AWS portfolio with more advanced security, storage, and cloud management projects. I’m also looking forward to exploring roles that combine **cloud computing and cybersecurity OR cloud engineering.**

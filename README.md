
# Ex.1: AWS Cloud Account Setup and Services Overview

## Aim
To create a cloud account in AWS and explore the various services provided on the AWS platform.

---

## Procedure

### Step 1: Go to the AWS Website
- Navigate to: [https://aws.amazon.com](https://aws.amazon.com)
- Click **“Create an AWS Account”** in the top right corner.

### Step 2: Enter Account Information
- Provide a valid **email address**.
- Set a strong **password**.
- Enter your **AWS account name** (e.g., your name or organization).

### Step 3: Choose Account Type
- Select between **Personal** or **Professional** based on your use case.
- Fill in your **contact information** including name, address, and phone number.

### Step 4: Enter Payment Information
- Provide **credit/debit card** details.
> **Note:** You will not be charged immediately. AWS Free Tier is available, but card details are required.

### Step 5: Verify Your Identity
- Enter your **phone number**.
- Choose to receive a **verification code** via call or SMS.
- Enter the code to confirm identity.

### Step 6: Choose a Support Plan
- Select one of the following:
  - Basic Support (Free)
  - Developer Support
  - Business Support
  - Enterprise Support
> For most users, **Basic Support** is recommended.

### Step 7: Complete the Sign-Up
- Review the information and click **"Sign Up"**.
- Wait for a **confirmation email** to verify account activation (usually within minutes).

### Step 8: Sign In to AWS Console
- Go to: [https://console.aws.amazon.com](https://console.aws.amazon.com)
- Log in with your registered **email and password**.

---

## Create an IAM User with Administrative Access

### 1. Secure the Root User
- Sign in to [AWS Management Console](https://console.aws.amazon.com) as the **root user**.
- Enable **Multi-Factor Authentication (MFA)** for the root account.

### 2. Enable IAM Identity Center
- Navigate to **IAM Identity Center** from the AWS Console.
- Enable the feature to manage users securely.

### 3. Create a User with Administrative Access
- In IAM Identity Center:
  - Create a **new user**.
  - Assign the user to the **AdministratorAccess** group or permission set.

### 4. Sign in with the Admin User
- Use the **sign-in URL** provided via email when the IAM Identity Center user was created.
- Login with the new user credentials to perform administrative tasks.

---

## AWS Services Overview

- Log in to the AWS Console.
- Explore available services such as:
  - **Compute** (EC2, Lambda)
  - **Storage** (S3, EBS)
  - **Databases** (RDS, DynamoDB)
  - **Networking** (VPC, Route 53)
  - **Machine Learning**, **Security**, **Monitoring**, and many more.

---

## Snapshots

> _Note: Include relevant screenshots here. For example:_

- **Snapshot 1**: AWS Sign-Up Page  
- **Snapshot 2**: AWS Services Dashboard  

(You can upload these images to your repository and link them like this:  
`![Snapshot 1](images/aws-signup.png)`)

---

## Result
✅A cloud account was successfully created on the AWS platform, and all the services were explored through the AWS Console.

---

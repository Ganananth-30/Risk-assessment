# EXPERIMENT 5
## NAME  : GANANANTH H 
## REGNO : 212225230070

## ASSET-ORIENTED RISK ASSESSMENT OF STORAGE ASSETS IN AWS 


## Aim

To identify storage assets in **AWS S3**.


## Software / Cloud Services Required

- AWS Account
- Microsoft Azure Account
- Web Browser
- Internet Connection

### Cloud Services Used

| Cloud Platform | Storage Service |
|---|---|
| AWS | Amazon S3 |


## AWS S3 STORAGE ASSESSMENT

## Step 1: Login to AWS

1. Open the AWS Management Console.
2. Sign in using your AWS account.
3. Search for **S3**.
4. Select **Amazon S3**.


## Step 2: Select the S3 Bucket

1. Click **Buckets**.
2. Select the S3 bucket created in the previous experiment.
3. Record:
   - Bucket name
   - AWS Region
   - Number/type of objects

<img width="1917" height="1017" alt="image" src="https://github.com/user-attachments/assets/5f8e01a1-94ed-4cb5-8243-b2599c0d4aaf" />




## Step 3: Check Block Public Access

1. Open the S3 bucket.
2. Select **Permissions**.
3. Locate **Block public access (bucket settings)**.
4. Check **Block all public access**.

### Record

- **ON** → Secure configuration
- **OFF** → Potential public-access risk

<img width="1917" height="1025" alt="image" src="https://github.com/user-attachments/assets/6765994e-0a14-4bd1-8fe0-52962d12ac74" />





## Step 4: Check Bucket Versioning

1. Select the **Properties** tab.
2. Locate **Bucket Versioning**.
3. Record whether it is:
   - Enabled
   - Disabled

### Security Purpose

Versioning helps recover previous versions of objects after accidental deletion or modification.



<img width="1917" height="1022" alt="image" src="https://github.com/user-attachments/assets/ce0aa6ef-21eb-4f8c-94f6-37adb0630917" />



## Step 5: Check Default Encryption

1. Stay in the **Properties** tab.
2. Locate **Default encryption**.
3. Record the encryption type.

### Possible Configurations

- SSE-S3
- SSE-KMS
- DSSE-KMS

### Security Purpose

Encryption protects stored data from unauthorized disclosure.

<img width="1917" height="1022" alt="image" src="https://github.com/user-attachments/assets/94dddeab-6ff1-47a0-9639-e52f7f6ec8ab" />


## Step 6: Check Bucket Policy

1. Select **Permissions**.
2. Locate **Bucket policy**.
3. Check whether a bucket policy exists.

### Record

- Policy exists
- No policy

> **Note:** A missing bucket policy is not automatically a vulnerability. Access may be controlled through IAM and other AWS security mechanisms.

<img width="1917" height="1025" alt="image" src="https://github.com/user-attachments/assets/9d6681ec-3db5-4041-aa49-98fd235bfdca" />


## Step 7: Check Object Ownership and ACL

1. In **Permissions**, locate **Object Ownership**.
2. Record the current configuration.

A common secure configuration is:

**Bucket owner enforced**

This means:

- ACLs are disabled.
- Objects are owned by the bucket owner.
- Access is controlled using policies.

<img width="1917" height="1016" alt="image" src="https://github.com/user-attachments/assets/bd0f5b22-d400-4114-b2ce-4316ad2412bf" />

## Step 8: Check Server Access Logging

1. Go to **Properties**.
2. Locate **Server access logging**.
3. Record whether it is:
   - Enabled
   - Disabled

### Security Purpose

Logging helps investigate suspicious or unauthorized access to the bucket.

<img width="1917" height="1025" alt="image" src="https://github.com/user-attachments/assets/539b18a4-b1fc-42c5-93c0-6175135c22f3" />




## Result

AWS S3 security configurations were analyzed and potential risks were identified.




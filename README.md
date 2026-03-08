# azure-iam-lab
azure IAM Lab – RBAC roles, groups, and permissions configuration
# Azure IAM Project – Role Based Access Control

## Project Overview

This project demonstrates how to implement Identity and Access Management in Microsoft Azure using Microsoft Entra ID.

The project includes:

* Creating security groups
* Understanding built-in roles
* Assigning RBAC permissions
* Implementing least privilege access

## Technologies Used

* Microsoft Azure
* Microsoft Entra ID
* Role Based Access Control (RBAC)

## Steps Performed

### 1. Created Security Groups

Two security groups were created:

* Accounts
* Management

These groups allow easier permission management.

### 2. Explored Azure Roles

The following built-in roles were reviewed:

* Helpdesk Administrator
* Application Administrator
* AI Administrator

### 3. Helpdesk Administrator Permissions

The Helpdesk Administrator role allows:

* Resetting user passwords
* Invalidating refresh tokens
* Monitoring service health
* Managing service requests

### 4. Best Practice

Instead of assigning permissions to users directly:

User → Group → Role

This follows the **Principle of Least Privilege**.

## Screenshots
<img width="1920" height="1080" alt="roles1" src="https://github.com/user-attachments/assets/1d012021-768c-4b40-a671-0babc003a52c" />
<img width="1920" height="1080" alt="Administrative1" src="https://github.com/user-attachments/assets/0901b2e1-0d11-4c57-8ac4-14b69c027067" />
<img width="1920" height="1080" alt="Roles2" src="https://github.com/user-attachments/assets/bfcb3b88-9f19-40db-9237-c66ebb94911b" />
<img width="1920" height="1080" alt="Groups1" src="https://github.com/user-attachments/assets/aef824a0-28cd-4d0c-8897-3864f5b9f887" />
<img width="1920" height="1080" alt="users1" src="https://github.com/user-attachments/assets/35fe0da7-a626-409b-8502-ae60988422eb" />
<img width="1920" height="1080" alt="default directory1" src="https://github.com/user-attachments/assets/50c590f4-ff89-46a1-aac9-1c68ee79fd55" />



## Skills Demonstrated

* Azure Identity Management
* RBAC Configuration
* Security Group Administration
* Cloud Security Basics

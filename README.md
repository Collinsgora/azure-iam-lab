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



## Skills Demonstrated

* Azure Identity Management
* RBAC Configuration
* Security Group Administration
* Cloud Security Basics

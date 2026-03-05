# Microsoft 365 Enterprise Identity Lab

## Tenant Information
Tenant Domain: ITLABS096.onmicrosoft.com

## Objective
This lab simulates a small enterprise Microsoft 365 environment to practice Identity and Access Management (IAM) using Microsoft Entra ID.

## Skills Practiced
- Tenant provisioning
- User lifecycle management
- Role-Based Access Control (RBAC)
- Security group implementation
- Multi-Factor Authentication enforcement
- Sign-in log monitoring

---

# Phase 1 – Identity & Access Management

## Users Created

### 1. Helpdesk Administrator
Name: Helpdesk Admin  
Username: helpdesk@ITLABS096.onmicrosoft.com  
License: Microsoft 365 Business Premium  
Role Assigned: Helpdesk Administrator

### 2. Standard Employee
Name: John Employee  
Username: john.employee@ITLABS096.onmicrosoft.com  
License: Microsoft 365 Business Premium  
Role Assigned: None (Standard User)

### 3. IT Administrator
Name: IT Operations  
Username: it.ops@ITLABS096.onmicrosoft.com  
License: Microsoft 365 Business Premium  
Role Assigned: Global Administrator

---

## Security Groups Created

Group Name: IT Support Team  
Members: Helpdesk Admin, IT Operations  

Purpose: Allows centralized permission management for IT staff.

---

## Security Configuration

### Multi-Factor Authentication (MFA)
MFA was enforced for privileged accounts to improve tenant security.

Accounts requiring MFA:
- IT Operations (Global Admin)
- Helpdesk Admin

---

## Monitoring

### Sign-In Logs Reviewed
Location:
Microsoft Entra Admin Center → Monitoring → Sign-in Logs

Activities Observed:
- User login attempts
- MFA prompts
- Authentication success/failure

---

# Key Learning Outcomes

This lab demonstrates practical experience with Microsoft 365 identity infrastructure, including:

- Creating and managing enterprise users
- Assigning RBAC administrative roles
- Implementing security groups
- Enforcing Multi-Factor Authentication
- Monitoring authentication activity

This simulates real-world identity management tasks performed by IT administrators and helpdesk technicians in enterprise environments.

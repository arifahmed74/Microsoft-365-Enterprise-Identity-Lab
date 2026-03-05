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
<img width="1424" height="681" alt="Screenshot 2026-03-04 at 12 18 31 PM" src="https://github.com/user-attachments/assets/98925bdc-2511-43b3-a02e-564e36db3cb2" />
<img width="1429" height="677" alt="Screenshot 2026-03-04 at 12 18 47 PM" src="https://github.com/user-attachments/assets/56fc1f82-2fb9-45ae-baf1-a11d43045ae2" />
<img width="998" height="625" alt="Screenshot 2026-03-04 at 12 19 26 PM" src="https://github.com/user-attachments/assets/9129bddb-5545-40c7-bb00-0edb9b87cce1" />
<img width="862" height="620" alt="Screenshot 2026-03-04 at 12 20 33 PM" src="https://github.com/user-attachments/assets/dcf09c84-b241-4373-99c3-2291abfb6f42" />
<img width="874" height="621" alt="Screenshot 2026-03-04 at 12 21 40 PM" src="https://github.com/user-attachments/assets/64d202cb-a932-4a3c-85c5-a7fddc202bc7" />
<img width="1188" height="550" alt="Screenshot 2026-03-04 at 12 22 10 PM" src="https://github.com/user-attachments/assets/0bba9f77-60bf-4209-969a-ed2df45edb82" />
<img width="1145" height="663" alt="Screenshot 2026-03-04 at 12 24 59 PM" src="https://github.com/user-attachments/assets/2e06de5f-5934-48a3-b397-5b9cb385b25e" />
<img width="1436" height="691" alt="Screenshot 2026-03-04 at 12 25 52 PM" src="https://github.com/user-attachments/assets/15068682-c4e6-458c-877f-5883bd309c63" />
<img width="1329" height="576" alt="Screenshot 2026-03-04 at 12 28 49 PM" src="https://github.com/user-attachments/assets/d40f2a73-4c26-400c-a270-4316c96107b1" />
<img width="1323" height="651" alt="Screenshot 2026-03-04 at 12 30 12 PM" src="https://github.com/user-attachments/assets/18615002-8543-4ef7-9f58-eec885203a0f" />
<img width="1075" height="674" alt="Screenshot 2026-03-04 at 12 42 15 PM" src="https://github.com/user-attachments/assets/db285f3d-434b-4db8-9be9-220061057f4e" />
<img width="591" height="637" alt="Screenshot 2026-03-04 at 12 42 44 PM" src="https://github.com/user-attachments/assets/37f980f2-2b74-40f9-a5c9-463b80b17d55" />
<img width="934" height="674" alt="Screenshot 2026-03-04 at 12 46 01 PM" src="https://github.com/user-attachments/assets/a4995e5c-3f25-46d3-bbae-a0a5bd9a675f" />

---

## Security Groups Created

Group Name: IT Support Team  
Members: Helpdesk Admin, IT Operations  

Purpose: Allows centralized permission management for IT staff.
<img width="1186" height="691" alt="Screenshot 2026-03-04 at 12 49 00 PM" src="https://github.com/user-attachments/assets/885ac8a8-9501-4ab6-824e-4346aed6d903" />
<img width="1185" height="692" alt="Screenshot 2026-03-04 at 12 50 07 PM" src="https://github.com/user-attachments/assets/e4e04678-7332-4104-9e49-8b14400039db" />
<img width="1185" height="674" alt="Screenshot 2026-03-04 at 12 50 57 PM" src="https://github.com/user-attachments/assets/890bceec-fd84-43d1-acce-67e286b079e9" />

---

## Security Configuration

### Multi-Factor Authentication (MFA)
MFA was enforced for privileged accounts to improve tenant security.

Accounts requiring MFA:
- IT Operations (Global Admin)
- Helpdesk Admin
<img width="1166" height="691" alt="Screenshot 2026-03-04 at 12 54 03 PM" src="https://github.com/user-attachments/assets/640e1128-83bf-4262-8ee6-bccb413175ba" />


---

## Monitoring

### Sign-In Logs Reviewed
Location:
Microsoft Entra Admin Center → Monitoring → Sign-in Logs

Activities Observed:
- User login attempts
- MFA prompts
- Authentication success/failure
<img width="1169" height="683" alt="Screenshot 2026-03-04 at 1 01 54 PM" src="https://github.com/user-attachments/assets/5066aab5-33c4-4502-8299-69fb5943144a" />
<img width="824" height="654" alt="Screenshot 2026-03-04 at 1 02 24 PM" src="https://github.com/user-attachments/assets/5e7974ee-1379-4b88-9cea-345b537dd27e" />
<img width="1149" height="664" alt="Screenshot 2026-03-04 at 1 02 36 PM" src="https://github.com/user-attachments/assets/09d4f06c-95c8-490c-ab5b-1e5797fb11a8" />
---

# Key Learning Outcomes

This lab demonstrates practical experience with Microsoft 365 identity infrastructure, including:

- Creating and managing enterprise users
- Assigning RBAC administrative roles
- Implementing security groups
- Enforcing Multi-Factor Authentication
- Monitoring authentication activity

This simulates real-world identity management tasks performed by IT administrators and helpdesk technicians in enterprise environments.

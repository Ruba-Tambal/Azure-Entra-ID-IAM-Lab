# Azure Identity & Access Management Lab

## 🎯 Scenario
A company needs to manage user access securely and efficiently while reducing administrative overhead.

## 🛠️ Solution
- Created multiple users in Microsoft Entra ID
- Organized users into a group (IT-Team)
- Assigned licenses using group-based licensing
- Enabled Self-Service Password Reset (SSPR)
- Implemented RBAC using group role assignment

## 🏗️ Architecture
Users → Group → Role Assignment → Azure Resources

## 🔐 Security Approach
- Centralized access control using groups
- Reduced manual errors in permission assignment
- Improved security with SSPR

## 📊 Results
- Simplified user management
- Scalable permission model
- Enhanced security posture

## 💡 Skills
- Microsoft Entra ID
- RBAC (Role-Based Access Control)
- Identity Management
- Cloud Security


## 🔐 RBAC Implementation

Instead of assigning roles individually, I implemented a group-based RBAC model:

- Created a group (IT-Team)
- Assigned Virtual Machine Contributor Role to the group
- Managed user access through group membership

### ✅ Benefits
- Simplified access management
- Reduced administrative overhead
- Scalable and secure design

## 📸 Project Evidence

| Feature | Screenshot |
|--------|------------|
| Users | /Users/ [from (Add User Step 1) to (Add User Step 5)] |
| Group | /Group/ [from (Add Group Step 1) to (Add Group Step 4)] |
| Licence | /licience/ [from (Add License to Group Step 1) to (Add License to Group Step 5)] |
| SSPR | /SSPR/ [from (SSPR1) to (SSPR9)] |
| RBAC | /RBAC/ [from (Resource Group1) to (Resource Group6)]|

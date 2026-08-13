# Microsoft-365-Administration-Lab

## Overview
This project demonstrates the deployment and administration of a Microsoft 365 Business Premium environment for a fictional small business. The lab simulates common responsibilities of an IT Technician, including identity management, Microsoft 365 administration, endpoint management, and security configuration.

The goal of the project was to gain hands-on experience with the tools and workflows used to support end users in an enterprise environment.

## Objectives

- Configure a Microsoft 365 tenant
- Create and manage users
- Implement identity and access controls
- Configure Microsoft Teams, Exchange Online, SharePoint, and OneDrive
- Enroll Windows devices into Microsoft Intune
- Deploy Microsoft 365 Apps

## Environment

| Component | Technology |
| :--- | :---: |
| Identity | Microsoft Entra ID |
| Email | Exchange Online |
| Collaboration | Microsoft Teams |
| File Storage | OneDrive |
| Document Management | SharePoint Online |
| Endpoint Management | Microsoft Intune |
| Client | Windows 10 VM |

## Scenario

This lab simulates onboarding a new employee into an IT environment.

The employee requires:

- Microsoft 365 account
- Exchange mailbox
- Department security group membership
- Multi-factor authentication
- Microsoft Teams access
- OneDrive provisioning
- Windows laptop enrollment
- Microsoft 365 Apps deployment
- Compliance and security policy assignment

## Implementation

**1. Identity Management**

Entra ID user account: Sarah Jones was created as a Finance employee and configured with appropriate organizational attributes.

![1](Screenshots/Create-User-Sarah-Jones.png)

**2. Assigning a License**

License assignment: Microsoft 365 Business Premium was assigned to the new employee, providing access to Microsoft 365 productivity services and Intune capabilities.

![2](Screenshots/Assign-Licenses.png)

**3. Finance Group**

Group-based access: Sarah was added to the Finance security group to support department-level access management.

![3](Screenshots/Security-Group.png)

**4. Conditional Access**

![4](Screenshots/Conditional-Access-Policy.png)

**5. Exchange Online**

Exchange Online: Sarah's Exchange Online mailbox was automatically provisioned following Microsoft 365 license assignment.

![5](Screenshots/Exchange-Mailbox.png)

**6. Shared Finance Mailbox**

Shared mailbox: A departmental Finance mailbox was created and access was delegated to the Finance user.

![6](Screenshots/Shared-Finance-Mailbox.png)

![6.1](Screenshots/Shared-Mailbox-Permissions.png)

**7. Microsoft Teams**

Microsoft Teams: Sarah was added to the Finance Department team and provided access to department-specific collaboration channels.

![7](Screenshots/Teams-Group.png)

![7.1](Screenshots/Teams-Channels.png)

**8. SharePoint**

SharePoint: A departmental document library was configured for centralized Finance document storage and collaboration.

![8](Screenshots/Sharepoint-Folders.png)

![8.1](Screenshots/Sharepoint-Site.png)

**9. OneDrive**

OneDrive: Verified personal cloud storage provisioning and tested controlled file sharing for the new employee.

![9](Screenshots/OneDrive-Folders.png)

![9.1](Screenshots/OneDrive-Share.png)

![9.2](Screenshots/OneDrive-Share-Confirm.png)

**10. Intune Compliance Policy**

Device compliance: A Windows 10/11 compliance policy was created to require baseline security controls including a password, firewall, and antivirus.

![10](Screenshots/Intune-Compliance-Policy.png)

**11. Intune Configuration Profile**

![11](Screenshots/Intune-Security-Configuration.png)

**12. Enrolling Sarah's Laptop**

Intune enrollment: Sarah's Windows 10 workstation was enrolled into Microsoft Intune for centralized endpoint management.

![12](Screenshots/Enroll-Intune-2.png)

**13. Deploying Microsoft 365 Apps**

![13](Screenshots/Assign-Apps.png)

![14](Screenshots/Installed-Apps.png)

## Login Test

**MFA**

![15](Screenshots/Login-MFA-Check.png)

**Outlook**

![16](Screenshots/Outlook-Check.png)

**Teams**

![17](Screenshots/Teams-Check.png)

**OneDrive**

![18](Screenshots/OneDrive-Test.png)

**Installed Apps**

![19](Screenshots/Showing-Apps-Installed.png)


## Security 

Implemented:

- Multi-Factor Authentication
- Conditional Access
- Device Compliance
- Password policies

## Skills Demonstrated

- Microsoft 365 Administration
- Microsoft Entra ID
- Microsoft Intune
- Exchange Online
- SharePoint Online
- Microsoft Teams
- OneDrive
- Identity & Access Management
- Device Compliance
- Conditional Access
- Windows Administration

## Lessons Learned & Continuous Learning

This project provided practical experience administering a Microsoft 365 tenant from the perspective of an IT Technician. It reinforced the relationship between identity management, endpoint management, collaboration services, and security policies in a cloud-managed environment.

To continue this lab, I will be continuing to explore all aspects of the administration center, particularly with endpoint security, enforcing stronger password policies, and experimenting with non-compliant devices. 










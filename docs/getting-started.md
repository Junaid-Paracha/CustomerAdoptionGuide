# Post Migration Support Adoption Guide
## Blue Mountain's Comprehensive Overview
### Welcome to Blue Mountain’s Adoption Guide Overview
This document serves as a comprehensive guide to understanding and navigating the post-migration support provided by Blue Mountain. Our aim is to familiarize you with the features and services of the PLx managed service, including protection levels, common desktop environments, and virtual enclaves.
### Introduction to PLx Managed Service
The primary offering of Blue Mountain, the PLx managed service, enables Special Access Programs (SAPs) to collaborate or work in isolation within the Microsoft Azure Secret and Top Secret clouds. Managed by Microsoft on behalf of the customer, this service helps to reduce costs and labor.
### Virtual Enclaves and Collaboration Software
#### Azure Virtual Enclaves
Virtual Enclaves (VEs) are secure locations in the cloud accessible only to permitted users. These enclaves offer:
- Remote desktops running on virtual machines
- Customized and secure workspaces for specific tasks and projects
- Accessibility through web browsers or remote desktop clients
- Applications and data hosted on virtual machines
#### Collaboration Software
The PLx managed service includes web-based applications like Jira and Confluence, which enable planning, tracking, managing work and projects, creating and sharing content, and supporting teamwork and stakeholder engagement.
### Protection Levels
PLx systems are accredited to Protection Level 2 (PL-2) and Protection Level 3 (PL-3), in compliance with the Joint SAP Implementation Guide (JSIG) (rev 4). The following table outlines the differences between these protection levels:
Protection Level	System	Use Case	Who Can Access?	What is Visible?
PL-3	PLx Desktop	Secure collaboration between different SAP users with the same read-on	Users with the same clearance (e.g., Secret) but different sets of program read-ons	Data that matches users’ program read-ons and classification
PL-2	Virtual Enclave	Mission-specific workloads	Users at the same clearance and same program read-ons	Data that matches both their program read-ons and classification
Protection levels determine the information users can access based on clearance, program read-ons, user roles, and more.
### The PLx Desktop
The PLx Desktop is a collaborative space for SAP users with different read-ons. It includes:
- Labeling/classification via Sentris
- Pull-print and scanning capabilities
- Collaboration software such as Office, Visio Pro, Project Pro, SharePoint, Outlook, Edge, Skype for Business, and Adobe Acrobat DC
#### PLx Desktop Standard Software Package
The PLx Desktop includes standard Microsoft Office tools (Word, Excel, PowerPoint, and OneNote) for creating documents and collaborating, as well as Outlook for email and calendar management, SharePoint for team projects, and Skype for Business for communication.
### Accessing the Common Desktop
#### Before You Login
Before logging on, ensure you have:
- An RSA token from your Trusted Agent (TA) or designated individual, activated and assigned to you
- A temporary password from your TA, classified at the level of your network
#### Logging into Azure Access Point
To log in:
- Click on the home icon at the bottom left
- Click Azure Virtual Desktop (v1.1)
- Type your username in the format: firstname.lastname@domain
- Enter your temporary password
- Choose whether to stay signed in
- You should now see your desktops
#### First-Time Login to Common Desktop
During your first login, you will set up your RSA token device and change your temporary password. Follow the provided steps to complete this process.
#### Changing and Resetting Passwords
To change your password:
- Click inside the Common Desktop window, press Ctrl + Alt + End, and select the option to change your password.
- Update your temporary password to your preferred password following the prompts.
If you enter your password incorrectly three times, you will need to reset it with the help of the Service Desk.
### Managed Folders
#### What are Managed Folders?
The Common Desktop has a specific folder structure for security reasons:
- The H: or home drive contains your user profile (e.g., My Documents) and new scans
- The G: or group share drive contains your files for collaboration
- The G: drive has three “root” folders you can access based on affiliation (Government, Contractors, Projects)
#### Requesting a New Managed Folder
To request a new Managed Folder, submit a ticket on JIRA, including the name of the Data Manager, or call/email the Service Desk.
#### Data Managers
Data Managers have permissions to add users to Managed Folders on the PL-3 file share. Responsibilities include verifying user access, adding/removing users from Managed Folders, and ensuring files are marked with Sentris.
### Sentris for Data Protection
#### Introduction to Sentris
Sentris is a comprehensive data protection tool that utilizes labels and markings to ensure data integrity and confidentiality.
#### Labeling Your Data
By default, users must label migrated data. Only Data Managers and the owner of a file can access and label unlabeled data.
#### Sentris Banner
The Sentris banner on the Common Desktop displays the highest classification on your system. It restricts access to data based on your facility and network.
#### Sentris Labeling for Office
Sentris integrates with Microsoft Office to enhance document security within Office apps. It provides document marking and access control, ensuring sensitive information is visible only to authorized personnel.
#### Sentris Bulk Marking Tool
This tool allows users to mark multiple files at once. It provides options for adding files and folders for marking, changing existing marking behavior, and viewing marking results.
#### Sentris Protection for SharePoint
Sentris integrates with SharePoint Server, adding protection to libraries, calendars, tasks, and lists. It ensures uploaded files are marked with appropriate classifications.
### Printing and Scanning
#### Printing
To print, users must physically accept their print jobs on the printer interface. Secure printers are available for site-specific printing needs.
#### Scanning
At the secure printer, users can scan documents to a network drive by following specific instructions to ensure data security.
### Above Baseline Software (ABS)
#### What is ABS?
ABS refers to specialized applications and tools procured beyond standard offerings. Customers must provide their own licenses for ABS.
#### Why Use ABS?
ABS allows customers to use software not included in the baseline, providing cost savings and discounts for buying licenses.
#### How to Request ABS
Customers can request ABS through forms in MARCY, providing tooling and automation for software deployment and publishing.
### Launching Remote Desktop Applications
Remote desktop applications will not appear in the start menu until you are subscribed to the workspace. Follow the provided steps to subscribe and access the applications.
### Contacting the Service Desk
For assistance, contact the Service Desk via email at Support@phc-msft.us or call 571-642-5977. Support hours are 0600-2230 EST, Monday to Friday (excluding holidays).
This guide aims to provide a thorough understanding of the post-migration support available to you. For any further inquiries or assistance, do not hesitate to reach out to our support team.


---
layout: default
---

# Ulbrich Frauendorf

## Summary
Experienced Software Engineer with a proven track record in designing, installing, testing, and maintaining robust software systems. Possesses deep expertise in managing the full software development lifecycle, from concept to deployment. Demonstrated ability to solve complex problems and deliver high-quality software solutions, whether working independently or as an integral part of a collaborative team. Committed to continuous improvement and innovation in software engineering practices.

## Skills

```js
const programmingLanguages = [
    "C#", "C++", "SQL",
    "Ts", "Js", "HTML"
];

const backendFrameworks = [
    ".Net Core", ".Net Framework"
];

const webFrameworks = [
    "Angular", "Vue.js", "Razor",
    "JQuery"
];

const databases = [
    "MSSQL", "MySQL", "SQL"
];

const tools = [
    "Azure", "Devops", "Git",
    "Miro"
];

let prodArchitecture = "Clean is Best";
```

## Education
**Bachelor Of Computer Science** | University of South-Africa | _September 2017_

Graduated Cum Laude.

## Experience

### Entelect Software (Pty) Ltd
**Senior Software Engineer** _(July 2022 - Present)_
- Working in a multi system architecture based on Azure Cloud as well as on premise hosted web applications.
- Lead the development of features across a variety of tech stacks, including .NET (Framework & Core), JavaScript, Angular, and Java Spring.
- Drive architectural decisions and contribute to the analysis and design of new software artefacts.
- Mentor junior engineers, providing training and support to help accelerate their career growth.
- Actively involved in performance reviews, providing feedback to team members and management.

_Suggestions to flesh out:_
- Include specific projects or systems you've worked on.
- Mention any key accomplishments or performance improvements.
- Highlight specific tools or frameworks (e.g., Angular, SignalR, Azure) that you leveraged in key projects.

### Sage Group Plc.
**Software Engineer** _(August 2017 - June 2022)_
- Developed and maintained CMS and CRM systems for the Outsourcing Department, integrating Microsoft Graph (SharePoint, Outlook, Power BI).
- Automated file uploads and report generation using Sage 300 and ADP APIs.
- Created custom reporting tools for non-technical users and managed Azure DevOps repositories.

### Rhapsodys
**General Manager** _(January 2004 – July 2017)_
- Managed 80+ staff and implemented inventory control systems integrated with Micros POS.


## Projects

**Accounting and payroll integrations**
- In charge of creating and maintaining a solution to integrate Deathstar with our international branches payroll software. Xero, Nmbrs.
- Lead the team to implement local accounting and invoicing from Deathstar to Sage Intacct Accounting software.
- 
**Internal ERP Solution (DeathStar)**
- Transformed legacy DeathStar system, by implementing a new Angular application to run in tandem with old MVC front-end.
- Refactor architecture to conform to proper CLEAN practices.
- Constant maintenace to keep productivity of the company up.
- Various Security enhancements added after the internal server was hacked.

**Candidate Tracker**
- Maintained and added features to old mvc site that 

**Employee Management Portal**

### Outsourcing ERP Platform

Outsourcing ERP Platform required for customer management. Logging hours spent on clients/ billing/ numerous KPI reports
- Solely responsible for the complete SDLC of the web-based project. Using SOLID principles throughout.
-	Set up the IIS server on local intranet.
-	Implemented Azure AD authentication and authorization policies to secure.
-	Fully integrated with Legacy sharepoint system, as a phased approach was used to move over to the new platform
-	Implemented SignalR hubs to display process queues used for Client and internal Tools
-	Implemented a SignalR live support chat, used by the compliance team.
-	Created framework for auto creation of razor views from Entity Framework Data models. (No scaffolding)
-	Coded PowerShell scripts for assigning App Roles, Delegated Permissions, and Setting up Oauth2 Tokens to grant Implicit permissions flow.

### Automated Test Framework

Repurposed Sage automated Test framework to facilitate Automating payroll functions and integrate with ADP APIs. Problem: Sage Premier (Legacy COBOL product) is unable to interface via API and most of functionality
-	Setting up Hyper-V VM’s to run UI functions on Premier Platform
-	Coding Coded-UI Test tools to run Reporting and Payroll functions.
-	Maintaining Test tools as new statutory requirements constantly changes the UI interface for built in parameters within the system.
-	Coordinated with Automation Test engineers Kanban used to assign tasks.
-	Project repository managed by subversion and CI Pipelines. 

### Mail Archiving and Data Access Control Service

Due to the nature of Payroll strict security protocols are in place for accessing sensitive customer information.
-	Created standalone windows service to archive and encrypt all employees’ emails (incoming and outgoing) containing information from any of our clients.
-	Created a standalone windows service to automate access control to individual client folders to be accessible only to the Account manager and payroll administrator assigned to specific clients.
-	Added a compliance user interface on the web platform fully integrated with standalone windows services, for managing all the above, with detailed error logs and automated email notifications when system processes failed.

### Payroll Integrations (SAP, Workday)

Clients needed outbound integration between SAGE300/ Premier payroll systems and Third-party HR Suites.
-	Coded a middleware on the CRM platform, to facilitate integration, between Payroll (Hosted in a private Citrix environment) and public APIs of third-party software.
-	Middleware also implemented interfaces for SFTP integrations where information was sent as encrypted XML/ JSON Files over certificate based encrypted connections.
-	Implemented encrypted JSON Mappings of allowed fields to be integrated per client.
-	Maintained a database for logging all transactions and generate quarterly security reports to management regarding the flow of information through the pipelines

### SEPA Credit Transfer ISO 20022 Payments

International banks adopt standard XML schema for initiating money transfers (Local banks have also started adopting this method) for Payroll and Third-Party payments. Sage has no export functionality for these formats.
-	Coded a generic interface for creating PAIN.001.001.03 XML files to different banks.
-	Interface is created using the options design pattern in conjunction with abstract factory pattern to produce different templates used by individual banks based on the XML schema.
-	Automated the creation and delivery of these bank files.

### Client Billable Hours Tracker

A simple WPF client installed for all employees, that uses Native windows User32 Libraries to capture time spent working on Clients, to ensure overall profitability, while still maintaining company integrity, by not collecting information on private usage of company laptop.

-	Designed and Coded application to collect usage data from system users about Time spent on Payroll systems only.
-	Implemented API to integrate information pushed to SQL database service and integrated into the local CRM Web Application.
-	Generated Reporting tools to report on customer and user profitability. (Billing vs Time spent)

### Generic Payroll Report Builder

Due to an increased need for customized reporting from our clients, a UI tool was developed so any payroll information could be built up in a visual way by normal system users.
-	Coded a UI where custom reports could be built by system users
-	Created a middleware interface with custom classes to extract all payroll information
-	Created a set of tools to allow users to set up the creation of general ledgers for their payrolls.

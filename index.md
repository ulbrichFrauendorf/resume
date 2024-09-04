---
layout: default
---

# Ulbrich Frauendorf

## Summary
Experienced Software Engineer with a proven track record in designing, installing, testing, and maintaining robust software systems. Possesses deep expertise in managing the full software development lifecycle, from concept to deployment. Demonstrated ability to solve complex problems and deliver high-quality software solutions, whether working independently or as an integral part of a collaborative team. Committed to continuous improvement and innovation in software engineering practices.

## Skills
*Programming Languages*
```
C#, C++, SQL, Typescript, Javascript, HTML
```
*Backend Frameworks*
```
.Net Framework, .Net Core
```
*Web Frameworks*
```
Angular
Vue.js
```

- Databases: MSSQL, MySQL, MongoDB
- Tools & Methods: Azure, Devops, Git, Kanban, Agile, TDD, Clean Architecture

## Experience

### Entelect Software (Pty) Ltd. 
**Senior Software Engineer** _(July 2022 - Present)_
- Under Construction

### Sage Group Plc.
**Software Engineer** _(August 2017 - June 2022)_
- Sage300 Integrations - Workday/ SAPS.
- Created and maintain web-based CMS, CRM specifically used by the Outsourcing Department, Fully Integrated with Microsoft Graph (SharePoint, Outlook, Power BI)
- Developed Automation framework for running reports on SAGE300 and organizing files in folder structures or automated file uploads To ADP SPM as well as to customer SFTP sites.
- All custom Reports PREMIER (ODBC) And SAGE300 (SQL) for outsourcing Clients.
- Created Custom Report Writer Tools used by Technically unskilled employees.
- Manage and maintain various repos on the Azure DevOps platform. (Code Reviews etc.)
- Create and maintain Automated Test Tools for Premier using Coded UI Framework.

### Rhapsodys

**General Manager** _(January 2004 – July 2017)_
- Managed a Staff Compliment of 80+ Employees.
- Created and Implemented Inventory Control Systems Web Application, Integrated with Micros point of sale System.
- All day-to-day Accounting Tasks.


## Projects
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

## Education
**Bachelor Of Computer Science** | University of South-Africa | September 2017
Graduated Cum Laude.

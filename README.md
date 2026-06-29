Employee Licensed Software Installation Request Through Service Catalog

Project Overview

This project automates the process of requesting licensed software using the ServiceNow Service Catalog. Employees can submit software installation requests, which are processed through automated workflows, approvals, and task assignments. The solution improves efficiency, transparency, and standardization in software request management.

Features

* Service Catalog Item for Software Requests
* Custom Catalog Variables
* Workflow Automation
* Approval Process
* Catalog Task Generation
* Business Rules Automation
* Service Portal Integration
* Request Tracking (REQ, RITM, SCTASK)
* Update Set Migration
* Notifications and Status Updates

Technologies Used

* ServiceNow
* Service Catalog
* Workflow Editor
* Business Rules
* Service Portal
* Update Sets
* GlideRecord API

Catalog Variables

1. Software Name
2. Version Required
3. License Justification
4. Urgency Level

Workflow Process

1. User submits software request.
2. Workflow initiates approval process.
3. Request is approved by the concerned authority.
4. Catalog Task is assigned to Software Support Team.
5. Software is installed.
6. Request is closed successfully.

Business Rule

When a software license is unavailable, the system automatically creates an Incident and assigns it to the Software Support Team for further action.

Tables Used

* sc_request (REQ)
* sc_req_item (RITM)
* sc_task (SCTASK)
* incident

Testing

* Service Catalog Testing
* Workflow Testing
* Business Rule Testing
* Service Portal Testing
* Update Set Migration Testing
* Data Integrity Validation

Project Outcomes

* Reduced manual effort
* Faster software request processing
* Improved request visibility
* Automated task assignment
* Standardized approval workflow

Future Enhancements

* Software Asset Management (SAM) Integration
* AI-based Approval Recommendations
* Automated License Availability Check
* Advanced Reporting Dashboard
* Mobile Accessibility

Author

Chiranjeevi Sanapala

Certification

ServiceNow Certified System Administrator (CSA)

# About
The files in this directory are tools to help you populate your ServiceNow instance with an IT service portfolio based on the **EDUCAUSE IT Catalog (2nd edition): The Higher Education IT Service Catalog Model**: https://www.educause.edu/working-groups/papers/2019/the-higher-education-it-service-catalog-second-edition/understanding-the-service-catalog

The spreadsheets are excel import templates containing the EDUCAUSE terms as rows (data) and are intended to be imported, in a particular order, to their respective ServiceNow tables. Once the **Service Portfolio, Taxonomy, and Business Services** are imported, the next step will be to populate *business services* with your organization's current *service offerings*.

# How to use
1. Create a Service Portfolio record: https://[instance].service-now.com/spm_service_portfolio_list.do
2. Import/create the Service Taxonomy Layer Definition (Service Category)
    - go to https://[instance].service-now.com/spm_taxonomy_layer_definition_list.do
    - right-click any column, select *Import*
    - import *spm_taxonomy_layer_definition - educause.xlsx*
3. Import the Service Category Taxonomy Nodes
    - go to https://[instance].service-now.com/spm_taxonomy_node_list.do
    - right-click any column, select *Import*
    - import *spm_taxonomy_node - educause.xlsx*
4. Import the Business Services
    - go to https://[instance].service-now.com/cmdb_ci_service_business_list.do
    - right-click any column, select *Import*
    - import *cmdb_ci_service_business - educause.xlsx*
  
# EDUCAUSE IT Service Catalog (Second Edition) Reference
This section summarizes the catalog from the EDUCAUSE page (https://www.educause.edu/working-groups/papers/2019/the-higher-education-it-service-catalog-second-edition/the-higher-education-it-service-catalog-model) in bullet points.
## Legend:
- Service Portfolio
  - Taxonomy Node (Layer Definition: Service Category)
    - Business Service

## EDUCAUSE IT Catalog:
- Information Technology
  - Administrative and Business
    - Alumni and Advancement
    - Athletics
    - Auxiliary Systems
    - Business Capability and Process Automation
    - Facilities Management
    - Faculty Information Systems
    - Financial and Procurement Systems
    - Human Resource Systems
  - Communication and Collaboration
    - Conferencing and Telephones
    - Email and Collaboration Services
    - Mass Communications and Emergency Notifications
    - Media and A/V
    - Web Services
  - Desktop and Mobile Computing
    - Desktop and Mobile Device Support
    - Hardware Lifecycle Services
    - Printing and Related Services
    - Software and Applications Distribution
  - Infrastructure
    - Business Continuity and Disaster Recovery
    - Data Center Services
    - Database Management
    - Integration Services
    - Monitoring and Alert Management
    - Network and Connectivity Management
    - Server and Storage Management
  - IT Professional Services
    - Continuous Improvement and Innovation
    - Digital Accessibility
    - IT Communications and Documentation
    - IT Service Delivery and Support
    - IT Strategy, Governance, and Enterprise Architecture
    - Portfolio and Project Management
    - Training and Outreach
  - Research
    - Lab Management Systems
    - Research Administration Systems
    - Research-Specific Computing and Applications
    - Research Data Services
    - Research Software
  - Information Security
    - Identity and Access Management
    - Secure Computing
    - Security Consulting and Education
    - Security Incident Response and Investigation
    - Security Policy and Compliance
  - Teaching and Learning
    - Assessment Systems and Learning Analytics
    - Academic Technology and Support
    - E-Portfolio Management
    - Instructional Technology and Design
    - Learning Management
    - Lecture Capture
    - Polling and Surveys

# Identity and Access Management Modernization

## Executive Summary

Scenario-based enterprise Identity and Access Management (IAM) modernization project focused on strengthening authentication, enforcing least privilege, automating identity lifecycle processes, and improving centralized security monitoring.

Designed and evaluated an IAM modernization solution for a fictional healthcare organization using Microsoft Entra ID, Conditional Access, multifactor authentication (MFA), role-based access control (RBAC), identity governance, and Microsoft Sentinel.

## Project Overview

Conducted an end-to-end IAM modernization project for a fictional healthcare organization with three locations and approximately 150 employees.

The existing identity environment presented security weaknesses involving password-only authentication, excessive user permissions, inactive accounts, manual onboarding and offboarding, and fragmented identity monitoring.

The project addressed these weaknesses through stronger authentication, standardized access management, automated identity processes, centralized logging, and documented security governance.

## Objectives

- Strengthen authentication through organization-wide MFA requirements
- Implement Conditional Access policies to protect employee sign-ins
- Enforce least privilege through RBAC and approved access assignments
- Identify and remediate inactive accounts and excessive permissions
- Automate employee onboarding, role changes, and offboarding
- Establish quarterly access reviews and documented approval processes
- Centralize identity monitoring through Microsoft Sentinel
- Improve visibility into suspicious sign-ins and administrative activity
- Validate security controls against defined acceptance criteria
- Align identity governance with Zero Trust and healthcare security principles

## My Role

- Assessed identity security weaknesses and established baseline risk measurements
- Developed IAM modernization requirements and solution architecture
- Designed MFA and Conditional Access requirements
- Defined job-based access controls and an approved role and access matrix
- Developed automated identity lifecycle management processes
- Established quarterly access-review procedures
- Designed centralized identity logging and monitoring using Microsoft Sentinel
- Evaluated implementation risks, operational dependencies, and mitigation strategies
- Developed security policies, administrative procedures, and user guidance
- Created pilot testing and final validation requirements
- Analyzed simulated post-implementation results against security objectives
- Documented project outcomes, business impact, and ongoing maintenance requirements

## Core Security Domains Addressed

### Identity & Access Management

- Microsoft Entra ID
- Multifactor Authentication (MFA)
- Conditional Access
- Role-Based Access Control (RBAC)
- Least Privilege
- Identity Governance

### Identity Lifecycle Management

- Joiner, Mover, and Leaver Processes
- Automated Account Provisioning
- Account Deprovisioning
- Role Assignment Management
- Quarterly Access Reviews
- Access Approval and Exception Management

### Security Operations & Monitoring

- Microsoft Sentinel
- Identity Sign-In Logs
- Audit Log Monitoring
- Privileged Activity Monitoring
- Suspicious Authentication Investigation
- Centralized Security Visibility

### Governance & Risk Management

- IAM Security Policies
- Zero Trust Principles
- Identity Risk Assessment
- Access Governance
- Healthcare Security Requirements
- Operational Risk Mitigation

## Key Security Findings

The simulated baseline assessment identified several identity security weaknesses:

- Only 30% of active employee accounts were enrolled in MFA
- 18 former or inactive user accounts remained enabled
- 24 cases of excessive employee permissions were identified
- Average account disablement time was approximately 48 hours
- Employee onboarding and offboarding depended on manual processes
- No formal quarterly access-review process existed
- Identity security logs were not centrally monitored
- Inconsistent access governance increased the risk of unauthorized access

## Implementation & Remediation Actions

### Authentication Security

- Established organization-wide MFA requirements
- Designed Conditional Access policies for approved sign-in scenarios
- Defined emergency administrator access and recovery procedures
- Validated authentication and access-control requirements

### Access Governance

- Developed an approved role and access matrix
- Applied least-privilege principles to job-based access
- Reviewed excessive permissions and documented approved exceptions
- Established quarterly access-review procedures

### Identity Lifecycle Management

- Developed automated onboarding, transfer, and offboarding workflows
- Defined HR-driven account lifecycle requirements
- Established procedures for disabling former employee accounts
- Validated account disablement against defined acceptance criteria

### Security Monitoring

- Integrated Microsoft Entra identity logging into the simulated Microsoft Sentinel monitoring solution
- Centralized selected sign-in and audit events
- Established procedures for investigating suspicious identity activity
- Defined monitoring responsibilities and incident escalation processes

### Security Governance

- Developed a formal IAM policy
- Documented administrator and employee procedures
- Established access approval and exception requirements
- Defined ongoing maintenance and operational responsibilities

## Security Frameworks & Principles Applied

- NIST SP 800-63B-4-Digital Identity and Authentication
- NIST SP 800-207-Zero Trust Architecture
- NIST Cybersecurity Principles
- Least Privilege
- Defense in Depth
- Role-Based Access Control
- Healthcare Cybersecurity Performance Goals
- Identity Governance and Lifecycle Management

## Tools & Technologies Used

- Microsoft Entra ID
- Microsoft Entra ID Governance
- Microsoft Entra Conditional Access
- Microsoft Entra MFA
- Microsoft Sentinel
- Microsoft 365
- Microsoft Azure
- Identity Sign-In and Audit Logs
- Role and Access Matrices

## Skills Demonstrated

- Identity and Access Management
- IAM Architecture and Modernization
- Microsoft Entra ID Security
- Conditional Access Policy Design
- Role-Based Access Control
- Identity Lifecycle Automation
- Identity Governance
- Access Reviews and Compliance
- Security Risk Assessment
- Security Monitoring and Log Analysis
- IAM Policy Development
- Security Control Validation
- Technical Documentation
- Project Planning and Risk Management
- Cross-Functional Security Governance

## Business & Security Impact

- Strengthened protection against unauthorized account access
- Reduced risks associated with password-only authentication
- Improved consistency of employee access permissions
- Reduced exposure from inactive accounts and delayed offboarding
- Improved identity governance and access-review accountability
- Increased centralized visibility into identity-related security events
- Reduced dependence on manual identity administration
- Supported healthcare information protection requirements
- Improved organizational security readiness and operational efficiency

## Key Project Outcomes

The completed scenario-based validation demonstrated:

- MFA coverage increased from 30% to 100% of active employee accounts, subject to approved exceptions
- All 18 identified inactive or former employee accounts were investigated, with unauthorized access disabled
- All 24 excessive-access cases were reviewed and corrected or supported by documented exceptions
- Tested employee offboarding scenarios met the four-hour account-disablement requirement
- Conditional Access test scenarios produced expected allow or block results
- Role-based permissions were validated against the approved access matrix
- Quarterly access-review procedures were established and tested
- Microsoft Sentinel provided centralized monitoring of selected identity security events
- IAM policies, administrative procedures, and operational guidance were documented

## Disclaimer

This repository presents a sanitized graduate cybersecurity capstone project developed for educational and professional portfolio demonstration purposes.

The healthcare organization is fictional. All organizational information, security findings, implementation activities, testing results, and performance measurements are simulated.

The project does not represent a production deployment or actual patient, employee, or organizational data. Original academic assessment materials and proprietary institutional content are not included.

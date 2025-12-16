# rrmgroup-active-directory
Secure Active Directory infrastructure with GPO, file services, backups, and network testing

**Project Overview**
This project demonstrates the design and implementation of a secure Windows Server Active Directory infrastructure for a simulated organization called RRM Group. The environment was built using virtual machines and focuses on centralized authentication, access control, backup management, and basic service testing.


**Objectives**

-Implement Active Directory Domain Services (AD DS)

-Centralize user and computer management

-Enforce security restrictions using Group Policy

-Configure a file server and backup strategy

-Test network services using command-line tools


**Technologies Used**

Windows Server

Active Directory Domain Services (AD DS)

Group Policy Management

DNS

Windows Server Backup

Telnet Client

VirtualBox



| Server Name | Role                      |
| ----------- | ------------------------- |
| ADDS01      | Domain Controller, DNS    |
| FILE_SERVER | File Services, Backups    |
| Client VM   | Domain-joined workstation |


**Key Tasks Performed**

-Installed and configured Active Directory Domain Services

-Promoted a server to Domain Controller

-Created and managed a domain environment

-Joined member servers to the domain

-Configured Group Policy to restrict Control Panel access

-Excluded ICT department from policy restrictions

-Implemented scheduled server backups

-Tested network connectivity and services using Telnet

-Diagnosed disk and performance issues in a virtualized environment


**Security Considerations**

This project applies basic security principles including centralized authentication, policy-based access control, and role separation. Group Policy was used to restrict unauthorized configuration changes while allowing administrative access for ICT staff.


**Project Status**

Completed core infrastructure setup and security policies.
Further enhancements may include monitoring, auditing, and advanced security controls.

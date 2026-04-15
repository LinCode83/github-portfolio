\# ZTA Component Definitions



\## Policy Engine (PE)

The Policy Engine is like the “brain” of Zero Trust. It collects information about who is trying to access a resource, what device they are using, and where they are connecting from. Based on this information, it decides whether to allow or block access. The Policy Engine does not enforce the decision itself; it only tells the system what to do.



\## Policy Administrator (PA)

The Policy Administrator is the part that prepares and sends the instructions from the Policy Engine to the enforcement system. Think of it as the “rule setter” that turns the decision into a clear command. For example, if the Policy Engine says “allow access,” the Policy Administrator formats that rule so the network or application can understand it.



\## Policy Enforcement Point (PEP)

The Policy Enforcement Point is the actual control point that applies the decision. It is like the “gatekeeper” that opens or closes the door for the user. If the Policy Engine and Policy Administrator say access is allowed, the PEP permits the connection. If the decision is “deny,” the PEP blocks the request.



\# Core Principle Application



\## Verify Explicitly

The Zero Trust principle of “Verify Explicitly” means you should never trust users or devices automatically, even if they are inside the facility network. Every access request must be checked before permission is granted. At the Golden State Water Treatment Facility, this principle helps protect the HR Employee PII Database, which contains sensitive employee information.



For example, if an HR employee tries to open the HR database, the Policy Engine might first verify that the user is a real HR staff member who has logged in with multi‑factor authentication. Then it checks that the device is a company‑owned laptop that is up to date and that the connection is coming from the secure facility network or approved VPN. Only when all these checks pass does the Policy Engine allow the request to proceed. If any check fails, access is denied until the issue is fixed.



\# Simplified Policy Table



| Policy Requirement (Signal) | Condition to be Met by User | Action if Condition is Met |

|---|---|---|

| User Identity | User must be a verified HR employee with valid multi‑factor authentication and matching HR role. | Grant Access |

| Device Posture | Device must be a managed company device that passes basic security checks (up‑to‑date OS and antivirus). | Grant Access |

| Network Context | User must connect from the approved facility network segment or secure company VPN. | Grant Access |





\# Git Repository Metadata

Project: Lab 3 - Zero Trust Policy

Filename: ZT-Policy-Profile.md

Commit Message: Completed Lab 3 Zero Trust Policy profile - https://github.com/LinCode83/GitHub-portfolio/lab3




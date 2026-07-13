Attack Flow



Overview



This document describes the intended workflow that learners should follow while completing the SecureTech Linux Privilege Escalation Training Lab.



The objective is to encourage systematic enumeration before attempting privilege escalation.



Attack Flow



SSH Login

&#x20;     │

&#x20;     v

User Enumeration

&#x20;     │

&#x20;     v

System Enumeration

&#x20;     │

&#x20;     v

Directory Enumeration

&#x20;     │

&#x20;     v

Permission Analysis

&#x20;     │

&#x20;     v

Sudo Enumeration

&#x20;     │

&#x20;     v

Identify Administrative Utilities

&#x20;     │

&#x20;     v

Privilege Escalation Analysis

&#x20;     │

&#x20;     v

Capture Root Flag



Detailed Steps



Step 1 – Login



\- Access the Ubuntu Server using the provided user account.

\- Verify the logged-in user.



Step 2 – User Enumeration



Commands commonly used:



\- whoami

\- id

\- groups



Objective:



Understand the privilege level of the current user.



Step 3 – System Enumeration



Commands commonly used:



\- uname -a

\- hostname

\- cat /etc/os-release



Objective:



Identify the operating system and machine information.



Step 4 – File System Enumeration



Inspect directories such as:



\- /home

\- /opt

\- /var

\- /tmp



Objective:



Locate files that may assist during privilege escalation.



Step 5 – Permission Analysis



Inspect:



\- File ownership

\- File permissions

\- Executable files



Objective:



Understand which files are accessible by the current user.



Step 6 – Sudo Enumeration



Command:



sudo -l



Objective:



Identify administrative commands delegated to the current user.



Step 7 – Security Analysis



Analyze all collected information before attempting privilege escalation.



Learners should understand why the identified configuration represents a security risk.



Educational Goal



Rather than encouraging learners to rely on automated tools, this lab promotes careful observation, manual enumeration, and structured analysis before privilege escalation.


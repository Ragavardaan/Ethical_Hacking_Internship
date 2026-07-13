Solution Guide

Objective

The objective of this lab is to demonstrate a structured methodology for Linux privilege escalation through proper enumeration and analysis of system configurations.



Step 1 – User Enumeration

Identify the current user and group memberships.

Example commands:

* whoami
* id
* groups



Step 2 – System Enumeration

Collect operating system and host information.

Example commands:

* uname -a
* hostname
* cat /etc/os-release
* 

Step 3 – File System Enumeration

Inspect important directories and identify files of interest.

Example commands:

* ls
* ls -l
* tree



Step 4 – Permission Analysis

Review ownership and permissions of files and directories to understand access controls.



Step 5 – Sudo Enumeration

Review delegated administrative privileges.

Example command:

sudo -l



Step 6 – Security Analysis

Analyze the collected information and explain the identified security weakness. Discuss how improper privilege delegation or insecure configurations can increase the risk of privilege escalation.



Mitigation

To reduce privilege escalation risks:

* Follow the principle of least privilege.
* Grant sudo permissions only when necessary.
* Review file ownership regularly.
* Audit sensitive directories and scripts.
* Periodically verify user privileges.
* Monitor administrative changes.



Learning Outcome

By completing this lab, learners gain practical experience in Linux enumeration, permission analysis, sudo configuration review, and privilege escalation methodology while understanding the importance of secure system administration.


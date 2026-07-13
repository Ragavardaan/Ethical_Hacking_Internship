Setup Guide

Overview

This document explains the steps required to recreate the SecureTech Linux Privilege Escalation Training Lab.

Software Requirements

* Oracle VirtualBox
* Ubuntu Server 26.04 LTS
* Windows 11 Host Machine
* Minimum 2 GB RAM
* 40 GB Virtual Disk



Virtual Machine Configuration

&#x20;\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

| Component        |      Configuration      |
| Platform         |    Oracle VirtualBox    |
| Operating System | Ubuntu Server 26.04 LTS |
| Memory           |         2048 MB         |
| Processor        |       2 CPU Cores       |
| Disk Size        |         40 GB           |
| Network          |          NAT            |

|\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_|\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_|



Initial Configuration

The following tasks were completed after installing Ubuntu:

* Updated the operating system.
* Installed essential packages.
* Created administrative and learner accounts.
* Configured the SecureTech directory structure.
* Created department folders.
* Added sample confidential files.
* Configured file permissions.
* Configured controlled sudo access.
* Verified the lab environment.



Directory Structure

/opt/securetech
├── backups
├── finance
├── hr
└── it



Users:

&#x20;\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

|    Username      |      Role     |

|      root        | Administrator |

|      ragav       | Primary User  |

|     analyst      |    Learner    |

|\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_|\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_|



Verification

The setup was verified by:

* Logging in as the learner account.
* Verifying file permissions.
* Checking sudo permissions.
* Testing access to the SecureTech environment.



Result

The lab environment was successfully configured and is ready for privilege escalation training.


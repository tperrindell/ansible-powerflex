**Ansible Modules for Dell Technologies PowerFlex** 
=========================================
### Release notes 1.5.0

>   © 2022 Dell Inc. or its subsidiaries. All rights reserved. Dell
>   and other trademarks are trademarks of Dell Inc. or its
>   subsidiaries. Other trademarks may be trademarks of their respective
>   owners.

Contents
-------
These release notes contain supplemental information about Ansible
Modules for Dell Technologies (Dell) PowerFlex.

-   [Revision History](#revision-history)
-   [Product Description](#product-description)
-   [New Features](#new-features-and-enhancements)
-   [Known issues](#known-issues)
-   [Limitations](#limitations)
-   [Distribution](#distribution)
-   [Documentation](#documentation)

Revision history
----------------
The table in this section lists the revision history of this document.

Table 1. Revision history

| Revision | Date           | Description                                                 |
|----------|----------------|-------------------------------------------------------------|
| 01       | December 2022  | Current release of Ansible Modules for Dell PowerFlex 1.5.0 |

Product description
-------------------

The Ansible modules for Dell PowerFlex are used to automate and orchestrate
the deployment, configuration, and management of Dell PowerFlex storage
systems. The capabilities of Ansible modules are managing volumes,
storage pools, SDCs, snapshots, SDSs, replication consistency groups, devices, protection domain and MDM 
cluster, and obtaining high-level information about a PowerFlex system information.
The modules use playbooks to list, show, create, delete, and modify
each of the entities.

New features and enhancements
-----------------------------
Along with the previous release deliverables, this release supports following features - 
- Info module is enhanced to support the listing replication consistency groups.
- Added New module for replication consistency groups.
- Updated modules to adhere with ansible community guidelines.
- Renamed gateway_host to hostname
- Renamed verifycert to validate_certs.

Known issues
------------
- Setting the RF cache and performance profile of the SDS during its creation fails intermittently on PowerFlex version 3.5 

Limitations
-----------
- The API is accepting a negative integer value for overall_limit in the network_limits for a specific protection domain. 

Distribution
------------
The software package is available for download from the [Ansible Modules
for PowerFlex GitHub](https://github.com/dell/ansible-powerflex/tree/1.5.0) page.

Documentation
-------------
The documentation is available on [Ansible Modules for PowerFlex GitHub](https://github.com/dell/ansible-powerflex/tree/1.5.0/docs)
page. It includes the following:

   - README
   - Release Notes (this document)
   - Product Guide

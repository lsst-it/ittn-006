..
  See https://developer.lsst.io/restructuredtext/style.html
  for a guide to reStructuredText writing.

:tocdepth: 2

.. sectnum::

.. note::

   **This technote is not yet published.**

   2019 saw significant changes have taken place in IT. Here we address the team structure and responsibilities. We put forward some planning and start on an estimate to complete for IT.

.. Add content here.
.. Do not include the document title (it's automatically added from metadata.yaml).

Introduction
============

In this document we layout the IT approach to the Rubin Observatory  construction. It will refer to other specific tech notes for details. 

We wish to build a modern approach to IT just close enough to the cutting edge to allow us remain current at the start of operations but preferably not quite the bleeding edge. 
To best support deployment we must have an element of research and development in the IT team.

Organization
============
IT north and south and interactions. 
Weekly tag up Monday. 


Physical Locations
==================
Networking
----------
- Logical design
- Redundant links
- High throughput 
- Wired and Wireless (802.1x)

Base Data Center
----------------
- Logical design architecture
- Large capacity data center
- Access control
- Shared with AURA

Summit Data Center
------------------
- Logical design architecture
- Access control

Tucson Lab(s)
-------------
These should resemble Chile as much as possible in terms of network and deployment.
 

Areas of work
=============
Some of this may lead to updates to :cite:`LSE-309`.

Desktop Support
---------------
- Hardware and software support to users.
- Installation of Rubin Observatory licensed software and provisioning of end user systems. 
- Follow policies and procedures, but also contribute to the creation of new ones

Monitoring
----------
- Network monitoring
- Server monitoring
- Service monitoring
- Environmental variables (Comp. Room) monitoring
- Cybersecurity threats detection
- Centralized log servers
- Notifications of outages.
- Preemptive alarms

Deployment
----------
- Infrastructure automation
- Configuration management
- Open source and licensed based software. 
- Automated user provisioning
- Rapidly scalable platform
- Highly available system

Authentication and Authorization
--------------------------------
- Cybersecurity plan compliant 
- 2FA 
- Single account across multiple systems.
- Admin privileges via escalation (sudo)

Storage
-------
- Highly available system
- High performance system
- Flexible and reliable storage.
- Central location for users and systems storage

Cybersecurity
-------------
IT will ensure to secure and protect technological resources of the Rubin Observatory, using industry standards, best practices, and cybersecurity policies.
We will focus our efforts in to keep confidentiality and integrity of the information, but also to increase the cybersecurity awareness of the users. 

We will enforce policies and keep systems up to date to strengthen the security of data and systems.

Backup
------
- Data protection
- Disaster Recovery 
- Automated multi-platform protection
- File and system recovery.

Video Conference
----------------
- Conference rooms and support for mobility. 
- Reachable from outside
- Support for meetings and collaboration. 

Interactions/Interface
=====================
- T&S
- DM
- OIR LAB

.. include:: openissues.rst
.. rubric:: References

.. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
   :style: lsst_aa

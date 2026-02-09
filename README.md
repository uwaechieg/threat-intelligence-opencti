# OpenCTI Setup – Threat Intelligence Lab

This repository documents my docker-based OpenCTI deployment on Ubuntu for threat intelligence analysis, IOC management, and MITRE ATT&CK mapping.

## Environment
- Ubuntu Linux (VM)
- Docker & Docker Compose

## Overview
OpenCTI is an open-source Threat Intelligence Platform used to centralize, correlate, and contextualize threat intelligence data. I used OpenCTI to explore the fundamentals of cyber threat intelligence, including threat actors, indicators of compromise (IOCs), and intelligence platforms. The focus was on understanding how raw threat data is collected, structured, and transformed into actionable intelligence for security operations.

## Setup Summary
- Deployed OpenCTI on an Ubuntu virtual machine using Docker.
- Installed Docker & Docker compose.
-  Configured threat intelligence connectors.
-  Ingested threat data from AlienVault OTX.
-  Explored threat entities such as indicators, reports, and threat actors.
-  Studied MITRE ATT&CK mappings.

## Tools & Technology
- OpenCTI
- Docker & Docker Compose
- Ubuntu Linux
- AlienVault OTX
- MITRE ATT&CK Framework

## Repository Structure
- **opencti-setup/** – Deployment notes and architecture overview
- **threat-feeds/** – Documentation of intelligence sources
- **intel-analysis/** – Sample analysis and reports
- **resources/** – References and tools used during the sprint

## Key Takeaways
- Threat intelligence becomes valuable when indicators are properly contextualized.
- Automation through connectors reduces manual intelligence handling.
- Platforms like OpenCTI help SOC teams correlate data and improve detection workflows.

 ## Status
This repository reflects the Threat Intelligence sprint and will remain as a reference for future SOC and blue team work.

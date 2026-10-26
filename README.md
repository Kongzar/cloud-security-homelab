# Cloud Security Home Lab

## Overview
A personal lab environment built to develop hands-on cloud security
skills across AWS and Azure, aligned with the SA cybersecurity job market.

## Lab Architecture
[link to your network diagram image]

## Environment
| Component       | Details                        |
|-----------------|-------------------------------|
| Hypervisor      | VirtualBox 7.0.6            |
| Security OS     | Kali Linux 2024.x             |
| Cloud (AWS)     | af-south-1 (Cape Town)        |
| Cloud (Azure)   | South Africa North (JHB)      |
| Host OS         | MAC OS / Ventura 13.7.8   |

## Tools Installed
- Nmap 7.99 — network scanning
- Wireshark 4.6.6 — packet analysis
- AWS CLI x.x — cloud management
- Azure CLI x.x — cloud management
- Python 3.14.6 + boto3 — automation

## Security Controls Implemented
- Root MFA enabled on AWS
- IAM admin user created (least privilege principle)
- AWS CloudTrail enabled (audit logging)
- Azure Defender for Cloud enabled (secure score: xx/100)
- Billing alerts configured on both platforms

## Documentation
- [VM Setup](docs/vm-setup.md)
- [AWS Setup](docs/aws-setup.md)
- [Azure Setup](docs/azure-setup.md)

## What I'm learning
[2-3 sentences on your current focus]

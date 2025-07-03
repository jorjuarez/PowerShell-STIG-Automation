# Windows STIG Hardening Scripts
## Overview
This repository contains a collection of PowerShell scripts designed to automate the remediation of security findings based on the Defense Information Systems Agency (DISA) Security Technical Implementation Guides (STIGs) for Windows systems.

The goal of these scripts is to provide a reliable and efficient way to apply security configurations, ensuring compliance and hardening systems against vulnerabilities.

## Scripts
This collection includes scripts for the following STIGs:

| STIG ID              | Description                                                  | Script File                        |
| -------------------- | ------------------------------------------------------------ | ---------------------------------- |
| **WN10-AU-000500** | Ensures the Application event log maximum size is configured to at least 32768 KB. | `STIG-ID-WN10-AU-000500.ps1` |


## Usage
Each script is designed to be run individually with administrative privileges in a PowerShell console.

**Example:**

To apply the remediation for STIG `WN10-AU-000500`:

```powershell
# Navigate to the script directory
cd C:\Path\To\Scripts

# Unblock the script if downloaded from the internet
Unblock-File -Path .\STIG-ID-WN10-AU-000500.ps1

# Execute the script
.\STIG-ID-WN10-AU-000500.ps1
```
## Disclaimer
These scripts are provided as-is. Always test them in a non-production environment before deploying to live systems. The user assumes all risk associated with running these scripts.

## Connect With Me
* **LinkedIn:** linkedin.com/in/jorgejuarez1
* **GitHub:** github.com/jorjuarez

# Windows Defender Integration with Wazuh

## Overview

This task was completed as part of my ongoing cybersecurity traineeship. I connected a Windows 10 endpoint to Wazuh and configured the agent to collect Microsoft Defender operational events.

The integration was tested using the standard EICAR antivirus test file. EICAR is a harmless test file designed to check whether antivirus and security monitoring tools are working correctly.

## What I Did

- Deployed the Wazuh agent on a Windows 10 endpoint.
- Confirmed that the Windows agent was active and connected.
- Configured the Wazuh agent to collect events from:

```text
Microsoft-Windows-Windows Defender/Operational

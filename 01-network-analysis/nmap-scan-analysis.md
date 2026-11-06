# Network Discovery and Security Analysis

## Project Overview
Performed a localhost network scan using Nmap to identify open ports and running services.

## Tools Used 
Nmap
Windows Command Prompt

## Target
127.0.0.1 (localhost)

## Findings
### Port 135
Service: Microsoft RPC
Status: Open 

### Port 445
Services: Microsoft-DS / SMB
Status: Open

## Security Observations
RPC is listening on port 135
SMB is listening on port 445
Both services requires appropriate security controls

## Recommendations
Restrict unnecessary network exposure
Ensure SMBv1 is disabled if not required
Keep Windows security updates current
Review firewall rules

## Conclusion 
The scan successfully identified two open TCP ports on the local Windows computer.

# EternalBlue (MS17-010) and WannaCry Simulation

## Objective

The purpose of this lab was to:

- Identify a vulnerable Windows host
- Validate the MS17-010 vulnerability
- Gain remote access
- Simulate ransomware execution
- Understand attacker and defender perspectives

## Environment

### Attacker
- Kali Linux

### Victim
- Windows 7

### Tools
- Nmap
- Metasploit
- Meterpreter
- VirtualBox

## Findings

The target machine was found vulnerable to MS17-010.

Successful exploitation resulted in a Meterpreter session.

The ransomware simulation successfully executed on the victim machine.

## Lessons Learned

- SMBv1 presents significant security risks.
- Legacy systems are highly vulnerable.
- Network services should be regularly patched.
- Detection opportunities exist during scanning, exploitation, and payload execution.

 ## Skills Demonstrated

- Vulnerability Assessment
- Network Enumeration
- Metasploit Framework
- Post Exploitation
- Ransomware Analysis
- Windows Security
- Incident Response Concepts

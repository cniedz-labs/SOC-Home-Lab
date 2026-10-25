# SOC-Home-Lab
Home cybersecurity lab focused on SIEM monitoring, threat detection, and investigation. Gaining experience and challenging myself

Overview

This project documents my development and use of a virtual SOC environment using Wazuh, Ubuntu Server, and Windows 11.

I am building this lab to develop and practice skills in cybersecurity including monitoring, threat detection, incident investigation, and engineering.

My background started as an electro-mechanical industrial technician working hands on with systems building a foundation in problem solving, root cause analysis, and technical diagnosis. 
With a passion for cyber starting in highschool, 4 years of c++ coding, I gained knowledge of networks, software, and hardware: exploring cybersecurity before deciding to try hands on mechanical work instead. 
I am hoping to transition my career now, to expand my knowledge, and challenge my skills and mindset to apply everything I have learned into a cyber setting.

My Lab consists of two VMs running in Oracle VirtualBox

Component                      Configuration                    Purpose

Ubuntu Server         |         Wazuh SIEM, 8GB RAM, 4vCPUs   |   Security monitoring and log analysis

Windows 11            |         6GB RAM, 2vCPUs        |         Monitored endpoint and security testing

VirtualBox NAT        |         Internet connectivity     |       Updates and software instillation

VirtualBox Internal Network  |  soc-lab               |           Private communication between VMs

Planned Security Investigations

01-Failed Authentication Attempts
Generate failed Windows logins, identify relevant security events and document investigation

02-Suspicious PowerShell Activity
Analyze PowerShell execution logs and identify potentially suspicious behavior

03-Network Traffic Analysis
Capture and inspect network traffic using Wireshark to identify unusual activity and understand common protocols

04-Detection Engineering
Develop and test custom detection rules to learn and improve security monitoring

Disclaimer

All security testing is performed in an authorized, and isolated home lab for educational purposes.

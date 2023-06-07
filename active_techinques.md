Groups, services, malware, etc. that have targeted or impacted ICS.

## Hive RaaS
- Gain access to victim networks by using single factor logins via RDP, VPN, and other remote network connection protocols [T1133].
- Gain access to victim network by exploiting the following Microsoft Exchange vulnerabilities [T1190].
- Gain access to victim networks by distributing phishing emails with malicious attachments. [T1566.001]
- Identifies processes related to backups, antivirus/anti-spyware, and file copying and then terminating those processes to facilitate file encryption [T1562].
- Stops the volume shadow copy services and remove all existing shadow copies via vssadmin on command line or via PowerShell [T1059] [T1490].
- Deletes Windows event logs, specifically the System, Security and Application logs [T1070]. 
- Removes virus definitions and disables all portions of Windows Defender and other common antivirus programs in the system registry [T1112].
- Deploy a ransom note HOW_TO_DECRYPT.txt into each affected directory which states the \*.key file cannot be modified, renamed, or deleted, otherwise the encrypted files cannot be recovered. [T1486]
- Exfiltrates data likely using a combination of Rclone and the cloud storage service Mega.nz [T1537].
- Files created in root (C:\ or /root/)
- Sources: https://www.cisa.gov/news-events/cybersecurity-advisories/aa22-321a

- Isolate ICS/SCADA systems and networks from corporate and internet networks using strong perimeter controls, and limit any communications entering or leaving ICS/SCADA perimeters.
- Enforce multifactor authentication for all remote access to ICS networks and devices whenever possible.
- Have a cyber incident response plan, and exercise it regularly with stakeholders in IT, cybersecurity, and operations.
- Change all passwords to ICS/SCADA devices and systems on a consistent schedule, especially all default passwords, to device-unique strong passwords to mitigate password brute force attacks and to give defender monitoring systems opportunities to detect common attacks.
- Ensure security is correctly configured with application authentication enabled and explicit trust lists.
- Ensure certificate private keys and user passwords are stored securely.
- Maintain known-good offline backups for faster recovery upon a disruptive attack, and conduct hashing and integrity checks on firmware and controller configuration files to ensure validity of those backups.
- Limit ICS/SCADA systems’ network connections to only specifically allowed management and engineering workstations.
- Robustly protect management systems by configuring Device Guard, Credential Guard, and Hypervisor Code Integrity (HVCI).
- Install Endpoint Detection and Response (EDR) solutions and ensure strong anti-virus file reputation settings are configured.
- Implement robust log collection and retention from ICS/SCADA systems and management subnets.
- Leverage a continuous OT monitoring solution to alert on malicious indicators and behaviors, watching internal systems and communications for known hostile actions and lateral movement.
- Ensure all applications are only installed when necessary for operation.
- Enforce principle of least privilege. Only use admin accounts when required for tasks, such as installing software updates.
- Investigate symptoms of a denial of service or connection severing, which exhibit as delays in communications processing, loss of function requiring a reboot, and delayed actions to operator comments as signs of potential malicious activity.
- Monitor systems for loading of unusual drivers.

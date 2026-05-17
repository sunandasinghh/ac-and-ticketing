This project demonstrates the setup and management of a basic Active Directory home lab environment using Windows Server 2019 and a Windows 10 client machine in Oracle VirtualBox manager. 
The lab was configured to simulate a real-world enterprise environment by creating Organizational Units (OUs), managing domain users, and joining a Windows 10 client system to the domain.
Technologies used while making thsi:
Windows Server
Active Directory Users and Computers
Windows 10
Virtual Machines
Domain Services





Lab Configuration
Organizational Units Created
The following Organizational Units (OUs) were created to simulate departmental separation in an organization:
HR
Finance
IT
Sales
Interns
These OUs were used to organize users and computers in a structured Active Directory environment.


![alt](https://github.com/sunandasinghh/ac-and-ticketing/blob/1c46a362b05d379ced0bfea9cea41d32b8b84861/addingousandusers/showing%20servers.jpeg)



User Management
Multiple domain users were created and assigned to their respective Organizational Units.
Tasks performed:
Created domain user accounts
Configured passwords
Organized users into departmental OUs
Verified account creation in Active Directory


![alt](https://github.com/sunandasinghh/ac-and-ticketing/blob/1c46a362b05d379ced0bfea9cea41d32b8b84861/addingousandusers/hrcreated.jpeg)


Windows 10 Domain Join
A Windows 10 virtual machine was configured and joined to the Active Directory domain.
Tasks performed:
Configured network connectivity between VMs
Joined Windows 10 client to the domain
Verified successful domain authentication
Logged into the client machine using domain credentials

![alt](https://github.com/sunandasinghh/ac-and-ticketing/blob/1c46a362b05d379ced0bfea9cea41d32b8b84861/addingousandusers/creatingvm.jpeg)



Key Learning Outcomes
Through this project, I gained hands-on experience with:
Managing Active Directory environments
Structuring enterprise-like domain environments
Managing users and computers in OUs
Joining endpoints to a Windows domain
Simulating real-world IT administration tasks

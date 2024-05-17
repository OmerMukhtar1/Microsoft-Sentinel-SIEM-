Microsoft Sentinel Live Attack Demonstration Home Lab
Description
This is a walkthrough of how I used Microsoft Azure and created a virtual machine in the cloud running Windows 10. I exposed a VM to the internet and used Azure Log Analytics Workspace, Microsoft Defender for Cloud, and Azure Sentinel to collect and aggregate the attack data and display it on a map in Microsoft Sentinel. This project will display the use of a few different tools and resources. I will be using PowerShell to scan Event Viewer in the exposed VM, specifically EventID 4625 which is failed logon attempts, and send that data to a logfile. The PowerShell Script also sends the IP address of any failed logons to IPgeolocation.io via an API, so later that information can be used Microsoft Sentinel to map where the logon attempts originated from. This project was done to gain experience with SIEMs, cloud concepts and resources, APIs, and Microsoft Azure. I learned how to provision and configure resources in the cloud, how to read SIEM logs and much more. This was a fun project and I hope anyone reading this appreciates the work that went into this project.
Utilities Used
Microsoft Sentinel (SIEM)
Log Analytic Workbooks
Microsoft Defender for Cloud
Virtual Machines
Remote Desktop
PowerShell
API's
Event Viewer
Firewalls
Environments Used
Microsoft Azure
Windows 10 (21H2)
Links
Microsoft Azure Free Trial: https://azure.microsoft.com/en-us/free/
IPGeolocation: https://ipgeolocation.io/

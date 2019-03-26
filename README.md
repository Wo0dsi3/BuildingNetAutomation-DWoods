# BuildingNetAutomation-DWoods

This is my project repository for the Building Network Automation Solutions course

The aim of my project is to bring as much network automation to my main managed services customer as possible.  I am a network support engineer for a customer with a global network. I manage CE WAN + LAN devices. I would love to automate many of the repeatable tasks and write a strong process document for each task so as to intergate automation into our managed services solution.

I have spent a good chunk of time in the last 3 weeks getting a lab into play. I followed your quick reciepe and created the ansible server via vagrant. For some reason , I cannot ssh to vagrant server... I am guessing a security policy on my work devices. 

I have commissioned an Ansible server which now has connectivty to my main managed services customer  (production , ekk!!!)
I have used GNS3 + EVE-NG to spin up vuirtual server and got them talking to routers. 

My next plan is to get Ansible production server talking to EVE-NG so as to test pushing playbooks to devices with customer configutations on them.

My project tasks (so far - is it ok to add more as I go?)

* Generate reports
* Compliance checks
* Commissioning new sites , routers , switches
* Commissoining new DMVPN tunnels
* Clean up of legacy DMVPN tunnels + configuration
* Bulk rollout of security policy configurations to routers and switches


I have created a new branch. IOS Compliance.
This branch is for creating a playbook that logs onto devices, gathers facts and based on the model and IOS running generates a report that tells me what devices don't meet our standard IOS software.


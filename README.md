# BuildingNetAutomation-DWoods

This is my project repository for the Building Network Automation Solutions course

Homework #3

09/04/19
I have created a new branch. Data Models - Commissioning
This branch is for creating a good data model. I wish to create inventory files and a commissioning playbook to push configurations to the new devices. I would love to add the compliance report I created (but need to fix) to the end of the playbook to sanity check the new build.

Group vars file uploaded

  location on Ansible server - btadmin@STLPBTDC0693:/etc/ansible/group_vars/MID.yml

Conf file uploaded

location on Ansible server - btadmin@STLPBTDC0693:/etc/ansible/templates/MID.conf

Site hosts file uploaded

location on Ansible server - btadmin@STLPBTDC0693:/etc/ansible/MID-hosts

Commissiong Playbook uploaded

location on Ansible server - btadmin@STLPBTDC0693:/etc/ansible/MID-New-Site.yml

This solution seems to work ok for me... I need to add more varibles to the group vars and more configuration into the .conf file..

I need a generic playbook though as I now have multiple files in my directories doing the same thing..

NOTE: I needed to manually create the folders in the Output directory - unsure why.

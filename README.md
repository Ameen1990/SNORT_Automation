# SNORT_Automation
SNORT IDS Installation and configuration on CentOS-7 using Ansible 

SNORT is an open source IDS (Intrusion Detection Sysyem).

I creted a script which installs the essential packages for IDS to function, then install SNORT itself.
The code also contains creating essential folders and files.
The main part is editing the "/etc/snort/snort.conf"  file.


## Howto

Install git

Pull the repository

`
apt-get install git -y
`

`
apt-get install ansible -y
`


`
git clone 
`

`
cd SNORT_Automation
`

`
ansible-playbook snort.yml
`




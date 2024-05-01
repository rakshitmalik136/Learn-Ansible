# Learn-Ansible
Learn what I know about Ansible and in return you can tell me what you all know about it.
**Hey folks!**

> So this repo is created so that everyone can share what they know and have learnt about Ansible.. 

**Lets Start....**

### What is Ansible?
Ansible is a basically simple IT automation platform that makes your applications and systems easier to deploy and maintain. Automate everything from code deployment to network configuration to cloud management, in a language that approaches plain English, using SSH, with no agents to install on remote systems.

### Why Ansible?
Simple:- You just have basic knowledge about English and Linux as it is quickly productive.
Powerful:- App Deployment, Configuration Management, Workflow Orchestration.
Agentless:- Use OpenSSH or WinRM, no agents to update or exploit. 
Credibility:- Efficient and Secure.                                                                              

![Screenshot 2024-04-27 012408](https://github.com/rakshitmalik136/Learn-Ansible/assets/111422125/d384c18f-26d8-4b74-9cec-8ef414e094c6)

There are three types of files:-
1) Playbooks (script of ansible)
-> use YAML and it is denoted as `script.yaml` or `script.yml`
2) Inventory:-
-> `/etc/ansible/hosts`
3) Cfg File:-
-> `/etc/ansible/ansible.cfg`

**After installation of Ansible:**
Inventory File ---- hosts
`cd/etc/ansible` --> used to change the directory to where ansible is located..
`vim hosts` --> used to open hosts file in vim text editor..
`#add the host name and there branches...`
#for example:

1) `:wq!` --> used to exit from text editor..
2) `ansible all --list-hosts` --> used to list all the hosts present in hosts file..
3) `ansible ungrouped --list-hosts` --> used to show ungrouped host present in hosts file..
4) `ansible -inventory --graph` --> used show all the hosts with their branches present in the host file..

In Ansible we have:-
1) Modulus - python language
2) ansible-doc `ansible-doc -l`
3) ping module --> checks the ability of ansible to log in and that a usable py is configured.
4) `ansible-user module -create delete/modify`


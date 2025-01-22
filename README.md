
##############################################################
#   Ansible Templates for Ansible Servers                    #
#   https://github.com/wevansprojects/MyAnsibleTemplates.git #
#   Author: William John Evans                               #
##############################################################

README:
This repo is for Ansible Templates. Here you will find my
structure for setting up a new ansible server.

Ansible can run on Debian or Redhat based distributions
 with little to no modification required.

Choose your Linux Distribution. Wisely. 
Once chosen you will find a whole multiple ansible playbooks
each of which can be used for different administrative tasks.

All playbook folders have a specific structure for their
purpose so that you can easily locate a playbook from its
function. For example for user management playbooks you 
would check inside the folder user-management.

Please use the run folder to create bash scripts to run
the ansible playbooks. This folder is present to ensure
you can combine multiple playbooks if you wish.

In this way we can write new playbooks following a set
structure for a specific purpose.
Should we chose to we can combine multiple
playbooks together we can do so within a script instead 
of creating extremely complex playbooks to fit every purpose. 

The above methodology is tried and tested and helped me avoid
complexity and overall confusion with custom folder structure.
I hope you find the playbooks useful and helpful. They will 
save you much time and effort if used as intended.

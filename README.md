# ansible_windows_guardicore_install

This is ansible code to deploy Guardicore agent on Windows

Tested on: Centra v40, Windows 2012R2, Ansible 2.9.6

Prerequisites:
Enable winrm from the Powershell on the Windows client and open firewall port 5986

# Instructions
Update the inventory file with your inventory
Update the win_install.yaml file with correct URL, target folder and install parameters 

# Execute the playbook:
ansible-playbook -i inventory win_install.yaml

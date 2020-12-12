# How to create an Ansible Configuration
1. Check first if your device has Ansible by using `ansible --version`
2. Create a configuration file named `ansible.cfg` using `vi ansible.cfg`, Ansible will automatically search for your `ansible.cfg` file in your current directory
3. Occupy the `ansible.cfg` file with basic information such as inventory, host verification, and your default remote user
4. Then save the `ansible.cfg` file

# How to create an Ansible Inventory
1. Create first the inventory file
> NOTE: Your inventory file name must be the same on your inventory variable in `ansible.cfg`
2. Write down the IP addresses of your hosts
3. Then save the inventory file

# How to create an Ad-hoc Ansible command with _setup_ and _shell_ module
1. For ansible setup use the command `ansible <host name or group name> -m setup`. Ansible setup command used to gather useful variables about remote hosts that can be used in playbooks
2. For ansible shell use the command `ansible <host name or group name> -m shell -a <bash arguments>`. Ansible shell module takes the command name followed by a list of space-delimited arguments

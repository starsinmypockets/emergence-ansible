# emergence-ansible
Ansible playbook and roles to install Emergence PHP and Sencha Cmd ona fresh Ubuntu 14 box

# Usage
1. Setup a fresh Ubuntu box for the emergence / sencha install to go onto
2. From your control machine [install ansible](https://docs.ansible.com/ansible/intro_installation.html)
3. Install this repository on your control machine
4. Add the following to your /etc/hosts/ansible file:
    [arbitrary tag]
    domain-or-ip-address.com
5. from emergence-project root run: `ansible-playbook playbooks/main.yml` 
6. Sit back and watch the money roll in

Feel free to contribute or report issues!

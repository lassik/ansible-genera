# Setup Symbolics Genera emulation using Ansible

Based on the instructions at https://static.loomcom.com/genera/genera-install.html

1. Create a Debian/amd64 virtual machine using VirtualBox
2. Setup SSH port forwarding in VirtualBox (Host Port 9000 : Guest Port 22)
3. Start up the virtual machine
4. Run `ansible-playbook genera.yml`

# vagrant-install

Ansible playbook for the installation of vagrant on a Fedora >=33 host with libvirt already installed.
This also opens the required firewall ports for NFS that vagrant up requires.
The playbook assumes 2 active zones (FedoraWorkstation and libvirt) these are defined as variables so can be changed as required.





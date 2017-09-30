# NetAutoTraining
IpSpace Project exercises

This note intends to describe my Ansible lab setup.
 
Hardware Platform: Dell laptop, 8G RAM, x86_64 CPU
Virtual Platform: Vagrant and Virtualbox
Environment VMs:
- two vqfx10k (vqfx1, vqfx2)
- two Ubuntu servers (srv1, srv2)
- one Fedora ansible management host, (srv). Our most likely real platforms will be SuSE or Redhat.
 
Using vagrant, I started with an example vagrant file from Juniper, then added a fedora ansible host to that vagrant setup.
 
Using vagrant, I defined a "mgmt" vlan, which will be used for the ansible traffic.
 
I defined an "ansible" user on all components. I propogated the public key from ansible@srv to setup publich key access.



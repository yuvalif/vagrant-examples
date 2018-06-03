# Vagrant Examples
## nested
This is an example of running vagrant box inside a vagrant box (using libvirt). Note that 2 issues are handled there:
* nested virtualization in libvirt
* the reuse of eth0 as the interface name for both boxes

To run the environment, first execute: ```vagrant up``` on the host, and the ```vagrant up``` on the guest.


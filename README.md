# Vagrant Examples
## nested
This is an example of running vagrant box inside a vagrant box (using libvirt). Note that 2 issues are handled there:
* nested virtualization in libvirt
* the reuse of eth0 as the interface name for both boxes

To run the environment, first execute: ```vagrant up``` on the host, ```vagrant ssh``` to get on the guest, and then ```vagrant up``` on the guest to bring up the nested environment.
## linkerd-tcp
This is an exmaple of linkerd-tcp environment, building linkerd-tcp and then setting up a test using it as a simple TCP proxy.

To run the environment, first execute: ```vagrant up``` on the host, ```vagrant ssh``` to get on the guest. On the guest ```cd linkerd-tcp-example``` and follow the instruction in the readme there.

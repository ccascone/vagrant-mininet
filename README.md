# vagrant-mininet

This Vagrantfile tries to be an all-inclusive script to provide an
OpenFlow playground in a VM.

Included tools are:

- Mininet
- OpenFlow 1.3 Switch
- NOX OpenFlow 1.3 Controller

## Usage

You have to have VirtualBox and Vagrant installed. Next, download the
Vagrantfile and run `vagrant up` from the folder it is located in.

After the script finishes its job, `vagrant ssh` should let you in the
VM. Windows users may want to install `msysgit` distribution for a
seamless ssh experience.

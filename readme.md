### Requirements

- Vagrant
- Virtualbox
- Ansible

### Installation

- clone ansible-fuse
- download the `jboss-fuse-full-6.2.1.redhat-084.zip` binary from access.redhat.com or jboss.org
- run `vagrant up` and the Ansible role will run against the Vagrant inventory

### Configuration

Set up the intended host topology by modifying the Vagrantfile

### Issues and Roadmap

- Ansible role implementation is too rigid, move hard-coded values to variables 
- Problems getting RMI services to bind, causing failures to ensemble



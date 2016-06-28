# mode-packer

### About

This repository contains the [Packer](http://packer.io) and [Puppet](http://puppetlabs.com) manifests used to build some internal Vagrant boxes for mode.com development.  It's forked from [Puppet Labs' packer manifest repo](https://github.com/puppetlabs/puppetlabs-packer).

### VM settings

* `root` password is set to `puppet`
* `vagrant` account uses the [Vagrant project's insecure public key](https://github.com/mitchellh/vagrant/tree/master/keys)

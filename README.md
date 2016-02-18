# About

Debian Jessie 64 based Vagrant dev box.

Configuration:
* Guest folder - config.vm.synced_folder "/data", "/data"
* Shell provisioning - config.vm.provision :shell, path: "bootstrap.sh"

## Tips

### Guest additions

Install virtualbox guest additions automatically

    vagrant plugin install vagrant-vbguest

### Become root

The vagrant user has sudo access. To become root run the following command as the vagrant user-
    
    $ sudo su -

## Cheatsheet

    $ vagrant up
    $ vagrant destroy
    $ vagrant reload --provision



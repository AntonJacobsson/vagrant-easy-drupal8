# vagrant-easy-drupal8
A simple way to fire up a Drupal 8 in Vagrant

### Getting started

Install Virtualbox, NFS-server, Vagrant and the following plugins:
```
# https://github.com/fgrehm/vagrant-cachier
vagrant plugin install vagrant-cachier
# https://github.com/devopsgroup-io/vagrant-hostmanager
vagrant plugin install vagrant-hostmanager
# https://github.com/dotless-de/vagrant-vbguest
vagrant plugin install vagrant-vbguest 
```

If you run Windows, install the nfs-plugin:
```
# https://github.com/winnfsd/vagrant-winnfsd
vagrant plugin install vagrant-winnfsd
```

Then run:
```
vagrant up
```

Drupal is installed in the directory `drupal` this is created in the git-root.

You can browse to `http://drupal8.dev/` now.

Login with `admin` and password `abc123` and begin to create!

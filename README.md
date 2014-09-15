# Vagrant-Zipkin

A quickly cobbled together Vagrant config to install & boot Zipkin for a hack around.

Utilises the Chef cookbook from https://github.com/dpkp/chef-zipkin


## Uses
This template also uses..

* Ubuntu 12.04 basebox with Ruby 1.9.3 and Chef 10.x?? pre-installed

  https://dl.dropbox.com/u/14292474/vagrantboxes/precise64-ruby-1.9.3-p194.box

* Vagrant Omnibus plugin - https://github.com/schisamo/vagrant-omnibus

  To update the version of Chef in the base box to a later version
 
```
vagrant plugin install vagrant-omnibus
```

* Various dependant cookbooks from the Chef Supermarket...
 



## Tested With
* Vagrant 1.6.3
* Oracle VM Virtual Box 4.3.6

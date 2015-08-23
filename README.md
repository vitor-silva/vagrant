# vagrant

vagrant package --output mynew.box
vagrant box add mynewbox mynew.box
vagrant init mynewbox
(https://scotch.io/tutorials/how-to-create-a-vagrant-base-box-from-an-existing-one)

## plugins
https://github.com/dotless-de/vagrant-vbguest

### snapshot
vagrant plugin install vagrant-vbox-snapshot
vagrant snapshot take good-snap
vagrant snapshot back (reload the last snapshot)
vagrant snapshot go good-snap (use the named snapshot)

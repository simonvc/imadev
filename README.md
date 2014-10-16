Pre-reqs:

Install vagrant.
Install Ansible (pip install ansible)

vagrant box add --name ubuntu1404 https://cloud-images.ubuntu.com/vagrant/trusty/current/trusty-server-cloudimg-amd64-vagrant-disk1.box

vagrant up

Now you can vagrant ssh into the machine and start tornado or whatever and keep your source/build directory in /vagrant so you can edit it in sublime atom etc.

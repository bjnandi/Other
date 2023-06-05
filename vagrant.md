STEP 1 >  install virtualBox
```
sudo apt install virtualbox
```
```
wget https://releases.hashicorp.com/vagrant/2.2.19/vagrant_2.2.19_x86_64.deb
sudo apt install ./vagrant_2.2.19_x86_64.deb
vagrant --version
mkdir ~/vagrant_project
cd ~/vagrant_project
vagrant init debian/trusty64
vagrant up
vagrant ssh
```




All this started after I added these settings (in Vagrantfile):

config.ssh.username = "vagrant"
config.ssh.password = "vagrant"
config.ssh.keys_only = true
config.ssh.insert_key = true

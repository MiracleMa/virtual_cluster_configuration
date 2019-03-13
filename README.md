# README

It is the script to build a virtual cluster by vagrant

The configuration file is `Vagrantfile`


## How to use

```
sh setpasswd.sh
su - #input passwd
cd /vagrant
sh install.sh
sh sethosts.sh
#and then set the ssh without password
ssh-keygen -t rsa
ssh-copy-id vm1
```

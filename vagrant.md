# Vagrant

https://blog.stephane-robert.info/docs/infra-as-code/provisionnement/vagrant/introduction/

% libvirt, virtualbox, vagrant, hyper-v

#plateform/multiple #target/local #cat/DevOps

## vagrant - start a box

```
vagrant up
```

## vagrant - relaunch provision

```
vagrant up --provision
```

## vagrant - destroy a box

```
vagrant destroy -f
```

## vagrant - login in box

```
vagrant ssh
```

## vagrant - add a box from packer

```
vagrant box add <path-to-package.box> --name <name> --force
```
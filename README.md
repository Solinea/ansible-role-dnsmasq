# ansible-role-dnsmasq

https://travis-ci.org/Solinea/ansible-role-dnsmasq.svg?branch=master

## Purpose:
This is a simple role meant to install dnsmasq

## Testing 
This role is instrumented with the [`Molecule`](https://molecule.readthedocs.io/en/stable-1.25/) test harness. To run it, install `Molecule` with pip
 ```commandline
$ pip install ansible
$ pip install docker
$ pip install molecule
```
then execute the tests like this
```commandline
$ molecule test 
```

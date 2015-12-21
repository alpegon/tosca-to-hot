[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)

Tosca to Hot - Tests
===============
Tests to check the heat-translator compatibility with the non normative tosca types.

1. INSTALLATION
===============

1.1 REQUISITES
--------------
This project makes use of [linux containers] (https://linuxcontainers.org/), so you need the lxc packages installed in your machine.

1.2 INSTALLING
--------------
To create the container needed to launch the tests you need to execute:
```
sudo ./create-lxc toscahot --create
```
this will create the container **toscahot** with all the needed libraries and dependencies to launch the tests.

2. TESTING
===============
Currently there is only one basic test to check the tosca to hot functionality, to launch it you need to type:
```
sudo ./launch-tests toscahot 
```
If everything is correct you should see the message:
```
Test test-base-tosca passed.
```

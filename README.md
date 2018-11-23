# molecule-ansible-docker
[![Build Status](https://travis-ci.org/jonashackt/molecule-ansible-docker.svg?branch=master)](https://travis-ci.org/jonashackt/molecule-ansible-docker)

Example project showing how to test Ansible roles with Molecule and Docker

This is a similar project to https://github.com/jonashackt/molecule-ansible-vagrant, but leveraging Molecule´s `docker` driver.

Don´t forget to install the Molecule docker driver:

```
pip install docker-py
```
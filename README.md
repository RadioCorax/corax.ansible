Requirements
============

* git
* python-virtualenv

Install
=======

* clone repository: `git clone git@github.com:RadioCorax/corax.ansible.git`
* change working directory: `cd corax.ansible`
* setup virtualenv: `virtualenv --python=python3 .`
* bootstrap Ansible environment: `./bin/pip install -r requirements.txt`
* install Ansible Galaxy role: `./bin/ansible-galaxy install -r ansible-galaxy.yml`

Run
===

* run deployment: `./bin/ansible-playbook site.yml`

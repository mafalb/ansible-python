# An ansible role for installing python2 [![Build Status](https://travis-ci.com/mafalb/ansible-python2.svg?branch=master)](https://travis-ci.com/mafalb/ansible-python2)

## Basic Usage

```
- hosts: localhost
  roles:
    - role: mafalb.python2/python
    - role: mafalb.python2/pip
```

## Variables

```
python2_pip_upgrade: false
```
if set it will do a pip install --upgrade pip .

## License

GPLv3


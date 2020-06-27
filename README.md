# Ansible Playbook: Secure Raspberry Pi

An Ansible playbook that automates securing your Raspberry Pi device. The configuration settings used are taken from the [official docs](https://www.raspberrypi.org/documentation/configuration/security.md) provided by the Raspberry Pi organization.

Requirements
------------

* Passwordless SSH access to the Raspberry Pi
* Update IP addresses in hosts for your local Raspberry Pis

Example
-------

Run the following command to execute the playbook.

```bash
$ ansible-playbook -i hosts site.yml
```

License
-------

MIT

Author Information
------------------

This playbook was created in 2020 by [Michael-Bryant Choa](https://www.github.com/mbchoa).

Spacewalk
=========

This project has the intention to automate installation of the Spacewalk server version 2.6 on CentOS 7 machines.


Prerequisites
-------------

  * CentOS 7 installed on target hosts;
  * Ansible 2.2.1.0 or higher.

Usage
-----

Access the spacewalk playbook and fill the configuration files according to your needs:

   * Adjust the server information on hosts file
      * NOTE: It's possible to install more than one servers at the same time.

   * Adjust the configuration information to server on defaults/main.yaml
      * NOTE_1: If you don't set any one of those variables the instalation won't work.

Resources
---------

Following links might be of value in case you are interested:

  * [spacewalk project page](http://spacewalkproject.org/),
  * [spacewalk wiki](https://github.com/spacewalkproject/spacewalk/wiki),
  * [ansible project page](https://www.ansible.com/),
  * [ansible documentation page](http://docs.ansible.com/ansible/).


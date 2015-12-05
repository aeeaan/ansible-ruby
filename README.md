correcthorse.ruby
=========

A role for installing ruby, bundler and phusion mod_passenger. Only system ruby is supported for now.


Role Variables
--------------
| Variable				| Default			| Notes						|
| :---					| :---				| :---						|
| ruby_install_passenger		| true				| 						|
| ruby_rubygem_rpms			| []				| rubygem rpms to install from base/EPEL/repos	|


Dependencies
------------

- correcthorse.common

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: correcthorse.ruby }

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)

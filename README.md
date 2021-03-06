Drupal
====================

Role for maintaining an installation of Drupal.

Role Variables
--------------
    
See defaults for any available variables.

Dependencies
-------------

  - City-of-Bloomington.linux
  - City-of-Bloomington.apache
  - City-of-Bloomington.mysql
  - City-of-Bloomington.php

Example Playbook
----------------
```yml
- hosts: drupal
  become: yes
  roles:
    - City-of-Bloomington.drupal
```

Additional Information
-------------------------
This role and others like it are maintained on the City of Bloomington's Github page:

https://github.com/city-of-bloomington

For a general guide on how to use Ansible, see:

https://github.com/city-of-bloomington/system-playbooks

License
-------

This ansible role is avialable under the MIT license.

Copyright (c) 2016 City of Bloomington, Indiana

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.



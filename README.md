hipchat
=========

HipChat is a Web service for internal/private chat and instant messaging. As well as one-on-one and group/topic chat, 
it also features cloud-based file storage, video calling, searchable message history and inline image viewing.   
(https://www.hipchat.com/downloads)

Requirements
------------

Currently only this role will only work on debian based systems. Install process taken from https://www.hipchat.com/downloads

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: jgrowlands.hipchat }

License
-------

MIT

Author Information
------------------

Jonathan Rowlands

Dedicated to toteswildly - May your love for ansible be an eternal flame that shines forever and ever.

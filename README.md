
---
  - hosts: tomcat-servers
    become: true
    become_method: sudo
    roles:
     - tomcat

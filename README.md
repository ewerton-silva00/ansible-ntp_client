ntp_client
=========

Esta role instala e configura o cliente NTP no CentOS 7.x

Role Variables
--------------

Esta role utiliza as variáveis abaixo:

```
# Variável que recebe os IPs/DNSs dos servidores NTP.
# Informar um abaixo do outro.
ntp_servers:
  - pool.ntp.br
```



Example Playbook
----------------

Como utilizar esta role na sua playbook:

    - hosts: all
      roles:
         - ntp_client

License
-------

BSD

Author Information
------------------

LinkedIn: https://br.linkedin.com/in/ewertonsilva00

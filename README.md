# ansible
Proyecto de Ansible para realizar despliegue de servidores web - APACHE2
En este ejemplo usamos por paises (Brasil y Chile), configurando unas variables para que se configure el Apache según el país que queramos.
Ejemplos para despliegue:

ansible-playbook frontend-apache.yml -i enviro/lab/hosts --tags configuration,chile --limit chile

ansible-playbook frontend-apache.yml -i enviro/lab/hosts --tags configuration,brazil --limit brazil

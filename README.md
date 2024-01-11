# Ansible


1.- Introducción 

La plataforma fue creada por Michael DeHaan, también autor de la aplicación de aprovisionamiento Cobbler y coautor del framework para administración remota ***Func.*** Está incluido como parte de la distribución de Linux Fedora, heredada de Red Hat Inc., y también está disponible para Red Hat Enterprise Linux, CentOS y Scientific Linux a través de los Paquetes Extras para Enterprise Linux (EPEL) como también para otros sistemas operativos. Ansible tiene soporte comercial de Ansible, Inc.


2.- ¿Qué es Ansible? 

**Ansible** es una herramienta que nos permite configurar, administrar y realizar instalaciones en
sistemas ***cloud*** con múltiples nodos sin tener que instalar agentes software en ellos. Sólo es
necesario instalar Ansible en la máquina principal desde la que vamos a realizar operaciones sobre
el resto de nodos y ésta se conectará a los nodos a través de SSH.
Ansible utiliza archivos ***YAML*** para describir las configuraciones que queremos aplicar en cada uno
de los nodos. Estos archivos de configuración se conocen como Playbooks.

3.- Características de Ansible 

**- Automatización sin agentes:** A diferencia de otras herramientas de automatización, Ansible no requiere la instalación de ningún software en los nodos que gestiona.

**- Uso del protocolo SSH:** Ansible utiliza el protocolo SSH para conectarse a los servidores y ejecutar las tareas.

**- Módulos:** Ansible se conecta a los nodos e inserta pequeños programas llamados módulos, que se utilizan para realizar tareas de automatización.

**- Idempotencia:** Las operaciones idempotentes producen los mismos resultados si se ejecutan una o varias veces sin ninguna intervención.

4.- Los competidores. 

* Jenkins
* Chef Enterprise Automation Stack
* Azure DevOps Services
* Puppet Enterprise
* Jira
* Odoo


5.- Arquitectura y componentes. 



.- Referencias
https://www.redhat.com/es/blog/system-administrators-guide-getting-started-ansible-fast
https://www.redhat.com/es/topics/automation/learning-ansible-tutorial
https://learn.microsoft.com/es-es/azure/developer/ansible/overview
https://es.wikipedia.org/wiki/Ansible_(software)
https://www.capterra.es/alternatives/149875/ansible-tower

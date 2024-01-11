# Arquitectura y componentes de Ansible

![image](https://github.com/camposchaconjosemaria/Ansible/assets/114906855/7d1ba41b-a121-4721-aa0c-c6516e37ccb4)

**Arquitectura de Ansible:**

1. **Máquinas de Control (Control Nodes):** Nodos desde los cuales se ejecutan las tareas de Ansible, con la instalación de Ansible y los archivos de inventario.

2. **Inventario (Inventory):** Archivo o colección de archivos que define los nodos gestionados por Ansible, puede ser estático o dinámico.

3. **Módulos (Modules):** Pequeños programas que realizan tareas específicas en los nodos de destino, como instalar software o copiar archivos.

4. **Conexiones SSH:** Ansible utiliza SSH para comunicarse con los nodos de destino, sin necesidad de instalar agentes en estos nodos.

5. **Facts:** Información recopilada sobre los nodos de destino antes de ejecutar tareas, almacenada en variables llamadas "facts".

6. **Playbooks:** Archivos YAML que definen una serie de tareas a ejecutar en los nodos de destino, proporcionando una forma declarativa de configurar sistemas.

**Componentes de Ansible:**

1. **Ansible Core:** Motor de ejecución central de Ansible que contiene los módulos, playbooks y la lógica para ejecutar tareas.

2. **Módulos (Modules):** Unidades de código reutilizables que realizan tareas específicas.

3. **Inventario (Inventory):** Especifica los nodos de destino y su configuración, puede ser estático o dinámico.

4. **Playbooks:** Archivos YAML que definen la configuración, tareas y roles a ejecutar en un conjunto de nodos.

5. **Roles:** Unidades de organización para playbooks, que permiten estructurar y reutilizar código.

6. **Ansible Galaxy:** Repositorio en línea de roles de Ansible compartidos y reutilizables por la comunidad.

Estos componentes trabajan juntos para permitir la automatización y gestión de la configuración en entornos de infraestructura.

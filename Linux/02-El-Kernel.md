# ¿Qué es el Kernel?

Es el núcleo del sistema operativo. Es la parte encargada de comunicarse directamente con el hardware y administrar los recursos necesarios para que los programas puedan funcionar. En Linux, el Kernel actúa como intermediario entre el usuario, las aplicaciones y los componentes físicos del equipo. Sin el Kernel, el sistema operativo no podría gestionar el procesador, la memoria, los dispositivos de almacenamiento ni los periféricos.

## Funciones principales del Kernel
### 1. Gestión de procesos:
   - El Kernel administra los programas que están ejecutándose en el sistema.

Sus funciones incluyen:
- Crear procesos.
- Asignar recursos.
- Controlar la ejecución.
- Finalizar procesos.

### 2. Administración de memoria
   - El Kernel controla cómo se utiliza la memoria RAM.

Se encarga de:
- Asignar memoria a los programas.
- Liberar memoria cuando ya no es necesaria.
- Gestionar la memoria virtual.

### 3. Comunicación con el hardware
   - El Kernel permite que el sistema operativo pueda utilizar los componentes físicos mediante controladores (drivers).

Ejemplos:
- Disco duro.
- Tarjeta de red.
- Procesador.
- Memoria RAM.
- Dispositivos USB.
  
### 4. Gestión del sistema de archivos
  - El Kernel controla la forma en que Linux almacena y organiza la información.

Se encarga de:
- Crear y eliminar archivos.
- Controlar permisos.
- Administrar dispositivos de almacenamiento.

### 5. Seguridad y permisos
  - Una de las funciones más importantes del Kernel en ciberseguridad es controlar el acceso a los recursos del sistema.

Gestiona:
- Usuarios.
- Grupos.
- Permisos.
- Privilegios de administrador.

## Comandos Basicos de Kernel
| Comando | Para qué sirve |
|---|---|
| `uname -r` | Ver versión del Kernel |
| `uname -a` | Información completa |
| `lsmod` | Ver módulos cargados |
| `dmesg` | Analizar mensajes del Kernel |
| `ps aux` | Ver procesos |
| `free -h` | Revisar memoria |
| `lscpu` | Información del CPU |
| `lsblk` | Ver almacenamiento |
| `journalctl -k` | Revisar logs del Kernel |


## Características del Kernel Linux

- Código abierto: Su código fuente puede ser revisado, modificado y mejorado por la comunidad.
- Multitarea: Permite ejecutar varios procesos al mismo tiempo.
- Multiusuario: Permite que varios usuarios utilicen el sistema con diferentes permisos.
- Modular: Puede agregar o eliminar módulos según las necesidades del sistema.
- Portable: Puede funcionar en diferentes dispositivos y arquitecturas.
- Gestión de recursos: Administra el procesador, memoria, dispositivos y almacenamiento.
- Seguridad: Controla permisos, privilegios y acceso a los recursos del sistema.
- Estabilidad: Está diseñado para funcionar durante largos periodos con pocos errores.

 ## El Kernel en ciberseguridad

Comprender el funcionamiento del Kernel es importante en ciberseguridad porque permite analizar:

- Vulnerabilidades del sistema operativo.
- Escalada de privilegios.
- Gestión de permisos.
- Seguridad de servidores Linux.
- Funcionamiento interno de herramientas de seguridad.

  

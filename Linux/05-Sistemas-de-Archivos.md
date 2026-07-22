# Sistemas de archivos 

El sistema de archivos de Linux es la estructura utilizada por el sistema operativo para organizar, almacenar y acceder a toda la información de la computadora.

A diferencia de otros sistemas operativos que utilizan letras para identificar las unidades de almacenamiento (como C: o D: en Windows), Linux organiza todos los archivos mediante una estructura jerárquica en forma de árbol que comienza en un único punto llamado directorio raíz (Root Directory).

### Su función principal es:

- Organizar archivos y carpetas.
- Permitir localizar la información rápidamente.
- Administrar el almacenamiento.
- Controlar los permisos de acceso.
- Facilitar la seguridad de los datos.

Sin un sistema de archivos, el sistema operativo no podría encontrar ni administrar la información almacenada en el disco.

___ 

- ### Directorio Raíz (/)
Es el directorio principal del sistema de archivos de Linux. Representa el punto de inicio desde el cual se organizan todos los archivos y carpetas del sistema operativo.

Todo lo que existe en Linux depende del directorio raíz.

- ### Directorio /home
Contiene los archivos personales de cada usuario del sistema. Cada usuario posee su propio directorio.

```` Bash
/home/ana
/home/pedro
/home/issy
````
##### *Su función es almacenar:*
- Documentos.
- Imágenes.
- Descargas.
- Videos.
- Configuraciones personales.

Es el directorio donde el usuario trabaja habitualmente.


- ### Directorio /etc
Contiene los archivos de configuración del sistema operativo y de muchos programas instalados.

#### *Su función es almacenar configuraciones relacionadas con:*

- Usuarios.
- Redes.
- Servicios.
- Seguridad.
- Aplicaciones.

Modificar archivos dentro de /etc puede cambiar el comportamiento del sistema.

- ### Directorio /bin
Almacena los programas esenciales del sistema operativo. Contiene comandos fundamentales necesarios para el funcionamiento de Linux. Entre ellos se encuentran herramientas utilizadas diariamente desde la Terminal.

- ### Directorio /usr
Contiene aplicaciones, bibliotecas y programas instalados para los usuarios. Es uno de los directorios más grandes del sistema y almacena la mayoría del software disponible. Muchas aplicaciones instaladas mediante los repositorios oficiales terminan almacenándose aquí.

- ### Directorio /var
Almacena archivos cuyo contenido cambia constantemente.

*Ejemplos* 
- Registros del sistema (logs).
- Bases de datos.
- Caché.
- Correos electrónicos.
- Archivos temporales de servicios.

Es un directorio muy importante para administradores de sistemas y analistas de ciberseguridad, ya que muchos registros de actividad se almacenan aquí.

- ### Directorio /tmp
Contiene archivos temporales utilizados por programas y por el propio sistema operativo.

*Características:*
- Su contenido puede eliminarse automáticamente.
- Se utiliza para almacenar información temporal durante la ejecución de programas.
- No está pensado para guardar información importante de forma permanente.

- ### Directorio /boot
Contiene los archivos necesarios para iniciar el sistema operativo.

#### *Su función es almacena componentes esenciales como:*

- El Kernel.
- Gestores de arranque.
- Archivos de inicio.

Sin este directorio el sistema no podría arrancar correctamente.
___

## Importancia en Ciberseguridad

El conocimiento del sistema de archivos permite a un profesional de ciberseguridad:

- Localizar archivos importantes.
- Analizar registros del sistema.
- Investigar incidentes de seguridad.
- Buscar malware.
- Administrar permisos.
- Comprender dónde almacenan información las aplicaciones.
- Realizar análisis forenses.

### *Durante una investigación es común revisar directorios como:*

- /var para consultar registros del sistema.
- /home para analizar archivos del usuario.
- /etc para revisar configuraciones.
- /tmp para buscar archivos temporales sospechosos.

 ## En resumen
El sistema de archivos de Linux constituye la base sobre la cual el sistema operativo organiza toda la información. Su estructura jerárquica, iniciada en el directorio raíz (/), permite administrar de manera ordenada los archivos, programas y configuraciones del sistema. Cada directorio posee una función específica, lo que facilita la administración, mejora la seguridad y simplifica el mantenimiento del sistema.

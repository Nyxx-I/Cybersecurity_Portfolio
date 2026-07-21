# Comandos básicos de Linux

Los comandos de Linux son instrucciones que el usuario escribe en la Terminal para interactuar con el sistema operativo. A través de ellos es posible navegar por el sistema de archivos, administrar documentos, gestionar permisos, instalar programas y realizar tareas de administración.

### 1. pwd (Print Working Directory):
Muestra la ubicación actual del usuario dentro del sistema de archivos y permite conocer el directorio en el que se está trabajando. Ejemplo:

```bash
pwd
```
### 2. ls (List)
Lista el contenido del directorio actual y permite visualizar archivos y carpetas. Ejemplo:

```bash
ls
```
### 3. ls -l
Muestra una lista detallada del contenido.

### **Información mostrada**
- Permisos.

- Propietario.

- Grupo.

- Tamaño.

- Fecha de modificación.

- Nombre del archivo.

Es uno de los comandos más utilizados para revisar permisos.

### 4. ls -a
Muestra todos los archivos, incluyendo los ocultos. En Linux, los archivos ocultos comienzan con un punto (.).
Ejemplo:

```bash
ls -a
```

Salida:

```text
.bashrc
.profile
Documentos
Descargas
```

### 5. cd (Change Directory)
Permite cambiar de directorio y navegar entre carpetas. Ejemplo:

```bash
cd documentos
```

o

```bash
cd /home/usuario/Documentos
```
### 6. cd ..
Regresa al directorio anterior y sube un nivel dentro del árbol de directorios.

### 7. cd ~
Lleva al directorio personal del usuario.

### 8. mkdir (Make Directory)
Crea un nuevo directorio y organiza archivos en carpetas. Ejemplo:

```Bash
mkdir proyectos
```
### 9. touch
Crea un archivo vacío y genera nuevos archivos para posteriormente editarlos. Ejemplo:

```Bash
touch notas.txt
```
### 10. cp (Copy)
Copia archivos o directorios. Duplica información sin modificar el archivo original. Ejemplo:

```Bash
cp archivo.txt respaldo.txt
```
### 11. mv (Move)
Mueve o cambia el nombre de un archivo. Cambia ubicación y renombra archivos. Ejemplo: 

```Bash
mv informe.txt documentos/
```
o

```Bash
mv viejo.txt nuevo.txt
```
### 12. rm (Remove)
Elimina archivos. El archivo se elimina directamente del sistema.

**Advertencia**: Los archivos eliminados con rm no pasan por la papelera; se eliminan directamente del sistema.

Ejemplo:

```Bash
rm archivo.txt
```
### 13. rmdir
Elimina directorios vacíos. Ejemplo:

```Bash
rmdir proyectos
```
### 14. rm -r
Elimina directorios junto con todo su contenido.

**Advertencia**: Debe utilizarse con precaución, ya que elimina archivos y subdirectorios de forma permanente.

Ejemplo:

```Bash
rm -r proyectos
```
## En resumen

Los comandos básicos de Linux son fundamentales para cualquier profesional de tecnologías de la información y, especialmente, para quienes desean especializarse en ciberseguridad. Aunque son sencillos, constituyen la base para realizar tareas más avanzadas, como la administración de sistemas, el análisis de redes, la automatización mediante scripts y el uso de herramientas de pruebas de seguridad.

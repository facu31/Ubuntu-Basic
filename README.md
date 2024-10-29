# Ubuntu-Basic

![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

Un pequeño repositorio de comandos utiles para linux.



# Tutorial Básico de Comandos en Ubuntu

Este tutorial cubre comandos básicos en Ubuntu organizados por temas: manejo de directorios, manejo de archivos, permisos, información del sistema, instalación de paquetes, y comandos de ayuda. Con ellos podrás gestionar tu sistema de manera eficiente.

---

## 1. Manejo de Directorios

- **`pwd`** - Muestra el directorio de trabajo actual.
  
  `pwd`

- **`ls`** - Lista los archivos y carpetas en el directorio actual. Algunas opciones comunes:
  
  - `ls -l` : Lista en formato largo, mostrando detalles de permisos y propietarios.
  - `ls -a` : Muestra archivos ocultos.
  - `ls -lh` : Muestra el tamaño de archivos en formato legible.
  
  `ls -l`

- **`cd`** - Cambia de directorio. Usa `cd ..` para retroceder un nivel.
  
  `cd nombre_del_directorio`

- **`mkdir`** - Crea un nuevo directorio.
  
  `mkdir nombre_del_directorio`

- **`rmdir`** - Elimina un directorio vacío.
  
  `rmdir nombre_del_directorio`

---

## 2. Manejo de Archivos

- **`touch`** - Crea un archivo vacío.
  
  `touch nombre_del_archivo`

- **`cp`** - Copia archivos o carpetas. Usa `-r` para carpetas.
  
  `cp archivo_origen archivo_destino`
  
  `cp -r carpeta_origen carpeta_destino`

- **`mv`** - Mueve o renombra archivos y carpetas.
  
  `mv archivo_origen archivo_destino`

- **`rm`** - Elimina archivos o carpetas (con `-r` para eliminar carpetas y su contenido).
  
  `rm nombre_del_archivo`
  
  `rm -r nombre_de_la_carpeta`

- **`cat`** - Muestra el contenido de un archivo.
  
  `cat nombre_del_archivo`

- **`nano`** - Editor de texto en la terminal, útil para crear o editar archivos.
  
  `nano nombre_del_archivo`

---

## 3. Gestión de Permisos

- **`chmod`** - Cambia los permisos de un archivo o directorio.
  
  `chmod 755 nombre_del_archivo`

- **`chown`** - Cambia el propietario de un archivo o directorio.
  
  `chown usuario:grupo nombre_del_archivo`

- **`chgrp`** - Cambia el grupo de un archivo o directorio.
  
  `chgrp grupo nombre_del_archivo`

---

## 4. Información del Sistema

- **`uname -a`** - Muestra información sobre el sistema operativo.
  
  `uname -a`

- **`df -h`** - Muestra el uso del espacio en disco.
  
  `df -h`

- **`du -sh`** - Muestra el tamaño de un directorio específico.
  
  `du -sh nombre_del_directorio`

- **`free -m`** - Muestra el uso de memoria en megabytes.
  
  `free -m`

- **`top`** - Muestra los procesos en ejecución y el uso de recursos.
  
  `top`

- **`ps aux`** - Muestra todos los procesos activos.
  
  `ps aux`

---

## 5. Instalación y Gestión de Paquetes

- **`sudo apt update`** - Actualiza la lista de paquetes.
  
  `sudo apt update`

- **`sudo apt upgrade`** - Instala las actualizaciones de software.
  
  `sudo apt upgrade`

- **`sudo apt install nombre_del_paquete`** - Instala un paquete.
  
  `sudo apt install nombre_del_paquete`

- **`sudo apt remove nombre_del_paquete`** - Elimina un paquete instalado.
  
  `sudo apt remove nombre_del_paquete`

- **`sudo apt autoremove`** - Elimina paquetes y dependencias que ya no son necesarios.
  
  `sudo apt autoremove`

- **`dpkg -l`** - Lista los paquetes instalados.
  
  `dpkg -l`

---

## 6. Compresión y Descompresión de Archivos

- **`tar -czvf`** - Crea un archivo comprimido en formato `.tar.gz`.
  
  `tar -czvf nombre_del_archivo.tar.gz nombre_del_directorio`

- **`tar -xzvf`** - Descomprime un archivo `.tar.gz`.
  
  `tar -xzvf nombre_del_archivo.tar.gz`

- **`zip`** - Comprime archivos en formato `.zip`.
  
  `zip nombre_del_archivo.zip archivo1 archivo2`

- **`unzip`** - Descomprime archivos `.zip`.
  
  `unzip nombre_del_archivo.zip`

---

## 7. Comandos de Ayuda y Manuales

- **`man`** - Muestra el manual de un comando. Usa `q` para salir.
  
  `man ls`

- **`comando --help`** - Muestra las opciones de uso de un comando.
  
  `ls --help`

- **`whatis`** - Muestra una breve descripción de un comando.
  
  `whatis ls`

- **`apropos`** - Busca en las páginas de manual comandos relacionados con una palabra clave.
  
  `apropos palabra_clave`

---

Con estos comandos básicos puedes comenzar a trabajar en la terminal de Ubuntu y gestionar tu sistema de forma efectiva. ¡Practica para familiarizarte con ellos!



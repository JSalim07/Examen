| Comando | Descripción |
|---------|-------------|
| ``` ls ```|Muestra los archivos|
| ```-l ``` | Muestra los archivos pero detalles como permisos y tamaño. |

## Comandos Básicos

| Comando | Descripción |
|---------|-------------|
| ``` cp archivo1.txt copia_archivo1.txt ``` | Copia un archivo o directorio. |
| ``` mv archivo1.txt nueva_carpeta/ ``` | Mueve o renombra archivos y directorios. |
| ``` rm archivo1.txt ``` | Elimina archivos. |
| ``` cat archivo1.txt ``` | Muestra el contenido de un archivo en el terminal. |
| ``` touch nuevo_archivo.txt ``` | Crea un archivo vacío. |
| ``` file imagen.jpg ``` | Muestra el tipo de un archivo. |

## 2. Comandos para la Manipulación de Directorios

| Comando | Descripción |
|---------|-------------|
| ``` mkdir nueva_carpeta ``` | Crea un nuevo directorio. |
| ``` rmdir carpeta_vacía ``` | Elimina un directorio vacío. |
| ``` cd documentos ``` | Cambia el directorio actual a "documentos". |
| ``` pwd ``` | Muestra el directorio actual. |
| ``` tree ``` | Muestra la estructura de directorios en forma de árbol. |

## 3. Comandos para Inspeccionar el Sistema

| Comando | Descripción |
|---------|-------------|
| ``` df -h ``` | Muestra el espacio disponible en los sistemas de archivos en un formato legible para humanos. |
| ``` du -sh carpeta/ ``` | Muestra el uso de espacio en disco por archivos o directorios. |
| ``` uname -a ``` | Muestra información completa sobre el sistema operativo. |
| ``` who ``` | Lista los usuarios que están conectados al sistema. |
| ``` top ``` | Muestra los procesos que consumen más recursos en tiempo real. |

## 4. Comandos de Gestión de Procesos

| Comando | Descripción |
|---------|-------------|
| ``` ps aux ``` | Muestra una lista de todos los procesos en ejecución. |
| ``` kill 1234 ``` | Termina un proceso por su ID (donde 1234 es el ID del proceso). |
| ``` fg ``` | Mueve un proceso al primer plano. |
| ``` jobs ``` | Lista los procesos en segundo plano. |

## 5. Comandos de Búsqueda

| Comando | Descripción |
|---------|-------------|
| ``` find /home -name "archivo*.txt" ``` | Busca archivos cuyo nombre empiece con "archivo" y terminen con ".txt". |
| ``` grep "palabra" archivo.txt ``` | Busca "palabra" dentro del archivo. |
| ``` locate archivo.txt ``` | Busca archivos rápidamente usando una base de datos preindexada. |

## 6. Comandos de Compresión y Archivos

| Comando | Descripción |
|---------|-------------|
| ``` tar -cvf archivo.tar carpeta/ ``` | Crea un archivo .tar. |
| ``` gzip archivo.txt ``` | Comprime un archivo. |
| ``` zip archivo.zip archivo1.txt archivo2.txt ``` | Comprime archivos en formato .zip. |

## 7. Comandos para Conexiones de Red

| Comando | Descripción |
|---------|-------------|
| ``` ping google.com ``` | Envía paquetes a un servidor para probar la conexión. |
| ``` wget https://example.com/archivo.zip ``` | Descarga archivos desde una URL. |
| ``` scp archivo.txt usuario@servidor:/ruta/ ``` | Copia archivos entre computadoras usando SSH. |
| ``` curl https://example.com ``` | Transfiere datos desde o hacia un servidor. |

## 8. Comandos de Permisos

| Comando | Descripción |
|---------|-------------|
| ``` chmod 755 archivo.sh ``` | Cambia los permisos de un archivo o directorio, dando permisos de ejecución. |
| ``` chown usuario:grupo archivo.txt ``` | Cambia el propietario de un archivo o directorio. |

## 9. Comandos Útiles de Administración

| Comando | Descripción |
|---------|-------------|
| ``` history ``` | Muestra el historial de comandos usados. |
| ``` alias ll='ls -l' ``` | Crea un alias para un comando. |
| ``` echo "Hola Mundo" ``` | Muestra un mensaje en la terminal. |

| Comando | Descripción |
|---------|-------------|
| ```bash ls -l ``` | Muestra los archivos con detalles como permisos y tamaño. |

## Comandos Básicos

| Comando | Descripción |
|---------|-------------|
| ```bash cp archivo1.txt copia_archivo1.txt ``` | Copia un archivo o directorio. |
| ```bash mv archivo1.txt nueva_carpeta/ ``` | Mueve o renombra archivos y directorios. |
| ```bash rm archivo1.txt ``` | Elimina archivos. |
| ```bash cat archivo1.txt ``` | Muestra el contenido de un archivo en el terminal. |
| ```bash touch nuevo_archivo.txt ``` | Crea un archivo vacío. |
| ```bash file imagen.jpg ``` | Muestra el tipo de un archivo. |

## 2. Comandos para la Manipulación de Directorios

| Comando | Descripción |
|---------|-------------|
| ```bash mkdir nueva_carpeta ``` | Crea un nuevo directorio. |
| ```bash rmdir carpeta_vacía ``` | Elimina un directorio vacío. |
| ```bash cd documentos ``` | Cambia el directorio actual a "documentos". |
| ```bash pwd ``` | Muestra el directorio actual. |
| ```bash tree ``` | Muestra la estructura de directorios en forma de árbol. |

## 3. Comandos para Inspeccionar el Sistema

| Comando | Descripción |
|---------|-------------|
| ```bash df -h ``` | Muestra el espacio disponible en los sistemas de archivos en un formato legible para humanos. |
| ```bash du -sh carpeta/ ``` | Muestra el uso de espacio en disco por archivos o directorios. |
| ```bash uname -a ``` | Muestra información completa sobre el sistema operativo. |
| ```bash who ``` | Lista los usuarios que están conectados al sistema. |
| ```bash top ``` | Muestra los procesos que consumen más recursos en tiempo real. |

## 4. Comandos de Gestión de Procesos

| Comando | Descripción |
|---------|-------------|
| ```bash ps aux ``` | Muestra una lista de todos los procesos en ejecución. |
| ```bash kill 1234 ``` | Termina un proceso por su ID (donde 1234 es el ID del proceso). |
| ```bash fg ``` | Mueve un proceso al primer plano. |
| ```bash jobs ``` | Lista los procesos en segundo plano. |

## 5. Comandos de Búsqueda

| Comando | Descripción |
|---------|-------------|
| ```bash find /home -name "archivo*.txt" ``` | Busca archivos cuyo nombre empiece con "archivo" y terminen con ".txt". |
| ```bash grep "palabra" archivo.txt ``` | Busca "palabra" dentro del archivo. |
| ```bash locate archivo.txt ``` | Busca archivos rápidamente usando una base de datos preindexada. |

## 6. Comandos de Compresión y Archivos

| Comando | Descripción |
|---------|-------------|
| ```bash tar -cvf archivo.tar carpeta/ ``` | Crea un archivo .tar. |
| ```bash gzip archivo.txt ``` | Comprime un archivo. |
| ```bash zip archivo.zip archivo1.txt archivo2.txt ``` | Comprime archivos en formato .zip. |

## 7. Comandos para Conexiones de Red

| Comando | Descripción |
|---------|-------------|
| ```bash ping google.com ``` | Envía paquetes a un servidor para probar la conexión. |
| ```bash wget https://example.com/archivo.zip ``` | Descarga archivos desde una URL. |
| ```bash scp archivo.txt usuario@servidor:/ruta/ ``` | Copia archivos entre computadoras usando SSH. |
| ```bash curl https://example.com ``` | Transfiere datos desde o hacia un servidor. |

## 8. Comandos de Permisos

| Comando | Descripción |
|---------|-------------|
| ```bash chmod 755 archivo.sh ``` | Cambia los permisos de un archivo o directorio, dando permisos de ejecución. |
| ```bash chown usuario:grupo archivo.txt ``` | Cambia el propietario de un archivo o directorio. |

## 9. Comandos Útiles de Administración

| Comando | Descripción |
|---------|-------------|
| ```bash history ``` | Muestra el historial de comandos usados. |
| ```bash alias ll='ls -l' ``` | Crea un alias para un comando. |
| ```bash echo "Hola Mundo" ``` | Muestra un mensaje en la terminal. |

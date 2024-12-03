<span style="font-size: 17px;"><strong>Ejemplo: </strong></span>

- ```bash
      ls -l
    ```

-<span style="font-size: 17px;">muestra los archivos con detalles como permisos y tamaño.</span>

- <span style="font-size: 17px;"><strong>cp: Copia un archivo o directorio.</strong></span>

    - ```bash 
        cp archivo1.txt copia_archivo1.txt
        ```


<span style="font-size: 17px;"><strong>mv: Mueve o renombra archivos y directorios.</strong></span>
- ```bash
      mv archivo1.txt nueva_carpeta/
    ```

- <span style="font-size: 17px;">(mueve el archivo).</span>

<span style="font-size: 17px;"><strong>rm: Elimina archivos.</strong></span>
- ```bash
      rm archivo1.txt
    ```

- <span style="font-size: 17px;">elimina un archivo.</span>

<span style="font-size: 17px;"><strong>cat: Muestra el contenido de un archivo en el terminal.</strong></span>
- ```bash
      cat archivo1.txt
    ```

<span style="font-size: 17px;"><strong>touch: Crea un archivo vacío.</strong></span>
- ```bash
      touch nuevo_archivo.txt
    ```

<span style="font-size: 17px;"><strong>file: Muestra el tipo de un archivo.</strong></span>
- ```bash
      file imagen.jpg
    ```

<span style="font-size: 17px;"><strong>2. Comandos para la Manipulación de Directorios</strong></span>
<span style="font-size: 17px;"><strong>mkdir: Crea un nuevo directorio.</strong></span>
- ```bash
      mkdir nueva_carpeta
    ```

<span style="font-size: 17px;"><strong>rmdir: Elimina un directorio vacío.</strong></span>
- ```bash
      rmdir carpeta_vacía
    ```

<span style="font-size: 17px;"><strong>cd: Cambia el directorio actual.</strong></span>
- ```bash
      cd documentos
    ```
    - <span style="font-size: 17px;">te lleva al directorio "documentos".</span>

<span style="font-size: 17px;"><strong>pwd: Muestra el directorio actual.</strong></span>
    - <span style="font-size: 17px;">Si estás en </span>
- ```bash
      /home/usuario
    ```
    - <span style="font-size: 17px;">, el comando </span>
    - ```bash
      pwd
      ```
    - <span style="font-size: 17px;">devolverá esa ruta.</span>

<span style="font-size: 17px;"><strong>tree: Muestra la estructura de directorios en forma de árbol.</strong></span>
- ```bash
      tree
    ```
    - <span style="font-size: 17px;">(requiere instalación en algunos sistemas).</span>

<span style="font-size: 17px;"><strong>3. Comandos para Inspeccionar el Sistema</strong></span>
<span style="font-size: 17px;"><strong>df: Muestra el espacio disponible en los sistemas de archivos.</strong></span>
- ```bash
      df -h
    ```
    - <span style="font-size: 17px;">muestra los resultados en un formato legible para humanos.</span>

<span style="font-size: 17px;"><strong>du: Muestra el uso de espacio en disco por archivos o directorios.</strong></span>
- ```bash
      du -sh carpeta/
    ```

<span style="font-size: 17px;"><strong>uname: Muestra información sobre el sistema operativo.</strong></span>
- ```bash
      uname -a
    ```
    - <span style="font-size: 17px;">muestra detalles completos.</span>

<span style="font-size: 17px;"><strong>who: Lista los usuarios que están conectados al sistema.</strong></span>
- ```bash
      who
    ```

<span style="font-size: 17px;"><strong>top: Muestra los procesos que consumen más recursos en tiempo real.</strong></span>
- ```bash
      top
    ```

<span style="font-size: 17px;"><strong>4. Comandos de Gestión de Procesos</strong></span>
<span style="font-size: 17px;"><strong>ps: Muestra una lista de procesos en ejecución.</strong></span>
- ```bash
      ps aux
    ```
    - <span style="font-size: 17px;">muestra todos los procesos del sistema.</span>

<span style="font-size: 17px;"><strong>kill: Termina un proceso por su ID.</strong></span>
- ```bash
      kill 1234
    ```
    - <span style="font-size: 17px;">(donde 1234 es el ID del proceso).</span>

<span style="font-size: 17px;"><strong>bg y fg: Mueve procesos al fondo (background) o primer plano (foreground).</strong></span>
- ```bash
      fg
    ```
    - <span style="font-size: 17px;">trae un proceso al primer plano.</span>

<span style="font-size: 17px;"><strong>jobs: Lista los procesos en segundo plano.</strong></span>
- ```bash
      jobs
    ```

<span style="font-size: 17px;"><strong>5. Comandos de Búsqueda</strong></span>
<span style="font-size: 17px;"><strong>find: Busca archivos en un directorio y subdirectorios.</strong></span>
- ```bash
      find /home -name "archivo*.txt"
    ```
    - <span style="font-size: 17px;">busca archivos cuyo nombre empiece con "archivo" y terminen con ".txt".</span>

<span style="font-size: 17px;"><strong>grep: Busca texto dentro de un archivo o flujo de datos.</strong></span>
- ```bash
      grep "palabra" archivo.txt
    ```
    - <span style="font-size: 17px;">busca "palabra" dentro del archivo.</span>

<span style="font-size: 17px;"><strong>locate: Busca archivos rápidamente usando una base de datos preindexada.</strong></span>
- ```bash
      locate archivo.txt
    ```

<span style="font-size: 17px;"><strong>6. Comandos de Compresión y Archivos</strong></span>
<span style="font-size: 17px;"><strong>tar: Crea o extrae archivos comprimidos.</strong></span>
- ```bash
      tar -cvf archivo.tar carpeta/
    ```
    - <span style="font-size: 17px;">crea un archivo .tar.</span>

<span style="font-size: 17px;"><strong>gzip y gunzip: Comprime y descomprime archivos.</strong></span>
- ```bash
      gzip archivo.txt
    ```

<span style="font-size: 17px;"><strong>zip y unzip: Comprime y descomprime archivos en formato .zip.</strong></span>
- ```bash
      zip archivo.zip archivo1.txt archivo2.txt
    ```

<span style="font-size: 17px;"><strong>7. Comandos para Conexiones de Red</strong></span>
<span style="font-size: 17px;"><strong>ping: Envía paquetes a un servidor para probar la conexión.</strong></span>
- ```bash
      ping google.com
    ```

<span style="font-size: 17px;"><strong>wget: Descarga archivos desde una URL.</strong></span>
- ```bash
      wget https://example.com/archivo.zip
    ```

<span style="font-size: 17px;"><strong>scp: Copia archivos entre computadoras usando SSH.</strong></span>
- ```bash
      scp archivo.txt usuario@servidor:/ruta/
    ```

<span style="font-size: 17px;"><strong>curl: Transfiere datos desde o hacia un servidor.</strong></span>
- ```bash
      curl https://example.com
    ```

<span style="font-size: 17px;"><strong>8. Comandos de Permisos</strong></span>
<span style="font-size: 17px;"><strong>chmod: Cambia los permisos de un archivo o directorio.</strong></span>
- ```bash
      chmod 755 archivo.sh
    ```
    - <span style="font-size: 17px;">da permisos de ejecución.</span>

<span style="font-size: 17px;"><strong>chown: Cambia el propietario de un archivo o directorio.</strong></span>
- ```bash
      chown usuario:grupo archivo.txt
    ```

<span style="font-size: 17px;"><strong>9. Comandos Útiles de Administración</strong></span>
<span style="font-size: 17px;"><strong>history: Muestra el historial de comandos usados.</strong></span>
- ```bash
      history
    ```

<span style="font-size: 17px;"><strong>alias: Crea un alias para un comando.</strong></span>
- ```bash
      alias ll='ls -l'
    ```

<span style="font-size: 17px;"><strong>echo: Muestra un mensaje en la terminal.</strong></span>
- ```bash
      echo "Hola Mundo"
    ```

# Manipulación de archivos y directorios
### El manipular archivos y directorios es una de las tareas fundamentales en un sistema operativo. Consiste en gestionar las estructuras de almacenamiento de información (archivos) y organizarlas dentro de carpetas (directorios):

### Obviamente todos aquí han de conocer que es un archivo pero por si acaso lo cuento:

- <span style="font-size: 16px;">Un archivo es una unidad lógica de almacenamiento utilizada para guardar datos o programas.</span>


### En cuanto a la manipulación de archivos, las operaciones más comunes gracias al sistema operativo son las siguientes:
- <span style="font-size: 16px;">Creación de archivos: Los usuarios o programas pueden crear archivos vacíos o con contenido inicial.</span>
    - ```bash
      touch nombre_del_archivo
      ```

- <span style="font-size: 15px;">Lectura de archivos: Permite extraer información almacenada en el archivo.</span>
    - ```bash
      cat nombre_del_archivo
      ```

- <span style="font-size: 16px;">Escritura en archivos: Agregar o modificar el contenido de un archivo.</span>
    -Aunque existen dos variaciones, son muy similares en funciones:
    
    -sobrescribe:
    - ```bash
      echo "contenido" > nombre_del_archivo 
      ```    
    -Agrega al final
    - ```bash 
        echo "contenido" >> nombre_del_archivo 
        ```

- <span style="font-size: 16px;">Copiar archivos: Crear una copia exacta de un archivo en otro lugar.</span>
    -  ``` bash
        cp nombre_del_archivo destino
        ```


- <span style="font-size: 16px;">Mover archivos: Cambiar la ubicación del archivo dentro del sistema.</span>
    - ``` bash
        mv nombre_del_archivo destino
        ```
- <span style="font-size: 16px;">Eliminación de archivos: Borrar el archivo del sistema de almacenamiento.</span>
   - ``` bash
        rm nombre_del_archivo
        ```

- <span style="font-size: 16px;">Renombrar archivos: Cambiar el nombre de un archivo sin modificar su contenido o ubicación.</span>
    - ``` bash
        mv nombre_actual nombre_nuevo
        ```


### En cuanto a la manipulación de directorios:
- <span style="font-size: 16px;">Creación de directorios: Generar una nueva carpeta para organizar archivos.</span>
    - ``` bash
        mkdir nombre_del_directorio
        ``` 
- <span style="font-size: 16px;">Navegación entre directorios: Moverse por la jerarquía de carpetas.</span>
    -   ``` bash
            cd ruta_del_directorio
        ```
        -Dicho comando posee una variación: ``` cd .. ``` , que es el que sirve para regresarse al directorio anterior.

- <span style="font-size: 16px;">Eliminación de directorios: Borrar carpetas vacías o con contenido (con precaución).</span>
    - ``` bash
        rmdir nombre_del_directorio
        ```
        
        - <span style="font-size: 16px;">Y cuando si tiene contenido la carpeta:</span>
            - ``` bash
                rm -r nombre_del_directorio
                ```

- <span style="font-size: 16px;">Listar el contenido de un directorio: Ver qué archivos y subdirectorios contiene.</span>
    
    -<span style="font-size: 15px;">Listar el contenido dentro del directorio:</span>

   - ``` bash 
        ls 
        ```
    
        -<span style="font-size: 15px;">Hacer lo mismo pero con más detalles:</span>
        - ``` bash
            ls -l
            ```

- <span style="font-size: 16px;">Mover y copiar directorios: Similar a los archivos, pero incluye su contenido.</span>
    
    - <span style="font-size: 15px;">El comando para copiar</span>
        - ``` bash
            cp -r nombre_del_directorio destino
            ```

        -<span style="font-size: 15px;">Comando para mover</span>
        - ``` bash
            mv nombre_del_directorio destino
            ```

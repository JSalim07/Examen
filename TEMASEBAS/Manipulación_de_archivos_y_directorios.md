# Manipulación de Archivos y Directorios

### La manipulación de archivos y directorios es una tarea esencial en cualquier sistema operativo. Esta actividad implica gestionar las estructuras de almacenamiento de información (archivos) y organizarlas dentro de carpetas (directorios).

### Definición de Archivo

- Un archivo es una unidad lógica de almacenamiento utilizada para guardar datos o programas.

### Operaciones Comunes de Manipulación de Archivos

Las operaciones más comunes para la manipulación de archivos, facilitadas por el sistema operativo, son las siguientes:

- **Creación de Archivos:** Los usuarios o programas pueden crear archivos vacíos o con contenido inicial.
    - ```bash
      touch nombre_del_archivo
      ```

- **Lectura de Archivos:** Permite extraer información almacenada en el archivo.
    - ```bash
      cat nombre_del_archivo
      ```

- **Escritura en Archivos:** Agregar o modificar el contenido de un archivo. Existen dos variaciones:
    - Sobrescribir:
    - ```bash
      echo "contenido" > nombre_del_archivo
      ```
    - Agregar al final:
    - ```bash
      echo "contenido" >> nombre_del_archivo
      ```

- **Copiar Archivos:** Crear una copia exacta de un archivo en otro lugar.
    - ```bash
      cp nombre_del_archivo destino
      ```

- **Mover Archivos:** Cambiar la ubicación del archivo dentro del sistema.
    - ```bash
      mv nombre_del_archivo destino
      ```

- **Eliminación de Archivos:** Borrar el archivo del sistema de almacenamiento.
    - ```bash
      rm nombre_del_archivo
      ```

- **Renombrar Archivos:** Cambiar el nombre de un archivo sin modificar su contenido o ubicación.
    - ```bash
      mv nombre_actual nombre_nuevo
      ```

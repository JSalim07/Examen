# Comandos Adicionales (wildcard, rm, mv, ls, obtener peso ordenado)

### A pesar de que ya abordamos los comandos usados en UNIX, existen otros cuantos que vale la pena mencionar. Los **wildcards** son caracteres especiales utilizados principalmente para representar varios caracteres en archivos y directorios, permitiendo seleccionar múltiples archivos a la vez.

## Wildcards

| Wildcard | Descripción | Ejemplo | Resultado |
|----------|-------------|---------|-----------|
| `*`      | Selecciona todos los archivos con una terminación específica que va después del asterisco. | `ls *.txt` | archivo1.txt, archivo2.txt, archivo3.txt |
| `?`      | Muestra todos los archivos con un nombre en común, reemplazando el signo de interrogación por cualquier carácter. | `ls archivo?.txt` | archivo1.txt, archivo2.txt, archivo3.txt, archivo4.txt |
| `[]`     | Selecciona archivos dentro de un rango específico. | `ls archivo[1-3].txt` | archivo1.txt, archivo2.txt, archivo3.txt |
| `{}`     | Genera patrones al nombrar archivos. | `ls archivo{1,final}.txt` | archivo1.txt, archivofinal.txt |

### Descripción de Wildcards

- **Asterisco (*)**: Se utiliza para seleccionar todos los archivos que coincidan con una terminación específica. 
  - Ejemplo: `ls *.txt` listará todos los archivos con la extensión `.txt`.

- **Signo de Interrogación (?)**: Se usa para mostrar todos los archivos que tengan un nombre en común, reemplazando el signo de interrogación por cualquier carácter.
  - Ejemplo: `ls archivo?.txt` podría resultar en `archivo1.txt`, `archivo2.txt`, `archivo3.txt`, `archivo4.txt`.

- **Corchetes ([])**: Permiten seleccionar archivos dentro de un rango específico.
  - Ejemplo: `ls archivo[1-3].txt` listará `archivo1.txt`, `archivo2.txt`, `archivo3.txt`.

- **Llaves ({})**: Se utilizan para generar patrones al nombrar archivos.
  - Ejemplo: `ls archivo{1,final}.txt` listará `archivo1.txt` y `archivofinal.txt`.

### Otros Comandos Útiles

- **Eliminar archivos (rm)**: Elimina archivos del sistema.
  - Ejemplo: `rm nombre_del_archivo`

- **Mover archivos (mv)**: Mueve archivos a una nueva ubicación.
  - Ejemplo: `mv nombre_del_archivo destino`

- **Listar archivos (ls)**: Lista los archivos en un directorio.
  - Ejemplo: `ls`

- **Obtener peso ordenado**: Ordena archivos por tamaño.
  - Ejemplo: `ls -lS`

Estos comandos y wildcards son herramientas poderosas para la gestión de archivos y directorios en sistemas UNIX, facilitando la manipulación y organización de datos de manera eficiente.

## $Permisos$ $de$ $archivos$ $en$ $unix$ $(chmod)$ 


## Permisos chmod simbolicos
| **Permiso** | **Símbolo** | **Ejemplo**               |
|-------------|-------------|---------------------------|
| **Lectura** | `r`         | `chmod u+r archivo.txt`    |
| **Escritura**| `w`        | `chmod g+w archivo.txt`    |
| **Ejecución**| `x`        | `chmod o+x archivo.sh`     |
| **Agregar** | `+`         | `chmod u+x archivo.sh`     |
| **Quitar**  | `-`         | `chmod o-r archivo.txt`    |
| **Establecer exactamente** | `=`         | `chmod u=r archivo.txt`    |
| **Usuario** | `u`         | `chmod u+x archivo.sh`     |
| **Grupo**   | `g`         | `chmod g-w archivo.txt`    |
| **Otros**   | `o`         | `chmod o+r archivo.txt`    |
| **Todos**   | `a`         | `chmod a+x archivo.sh`     |
```bash
chmod u+rwx archivo.sh
```
## Permisos chmod en modo octal
| **Permiso**              | **Valor Octal** | **Combinación de Permisos** | **Ejemplo**                          |
|--------------------------|-----------------|-----------------------------|--------------------------------------|
| **Sin permisos**          | `0`             | ---                         | `chmod 000 archivo.txt`              |
| **Ejecución**             | `1`             | --x                         | `chmod 001 archivo.sh`               |
| **Escritura**             | `2`             | -w-                         | `chmod 002 archivo.txt`              |
| **Lectura**               | `4`             | r--                         | `chmod 004 archivo.txt`              |
| **Lectura + Escritura**   | `6`             | rw-                         | `chmod 006 archivo.txt`              |
| **Lectura + Ejecución**   | `5`             | r-x                         | `chmod 005 archivo.sh`               |
| **Escritura + Ejecución** | `3`             | wx-                         | `chmod 003 archivo.sh`               |
| **Lectura + Escritura + Ejecución** | `7`   | rwx                         | `chmod 007 archivo.sh`               |


```bash
chmod 764 archivo.txt
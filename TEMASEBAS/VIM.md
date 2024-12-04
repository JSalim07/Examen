# **VIM**

## **¿Qué es Vim?**

### Vim es un editor de texto avanzado utilizado en sistemas Linux y otros sistemas Unix. Por ejemplo, también se usa en Git Bash, que es el entorno en el que estoy escribiendo este texto. Sin embargo, Vim no es la versión original del editor de texto; el original se llamaba VI, y su sucesor "VIM" significa "Vi IMproved", que es la versión que se utiliza actualmente.

### Vim es muy útil para los programadores, ya que su rapidez y flexibilidad facilitan la curva de aprendizaje en entornos como "GIT BASH".

## **Características**

### Git Bash, al no tener una interfaz gráfica, encuentra en Vim una herramienta perfecta para este entorno debido a su ligereza y rapidez. No requiere una licencia como "Word" ni necesita ser instalado, ya que viene preinstalado, a diferencia de algunos comandos que deben instalarse en entornos como Linux.

### Vim tiene distintos modos de funcionamiento. Antes de mencionarlos, es importante entender qué es un modo de funcionamiento. Esto se refiere a las diferentes formas en las que se puede interactuar con Vim. A continuación, se enumeran los modos disponibles:

- **Modo Normal:** Es el modo más básico pero limitado en funciones, ya que no permite escribir directamente en el archivo. Solo permite moverse, borrar, copiar y ejecutar comandos básicos.
  - Ejemplo: "dd" se usa para borrar líneas. "yy" se usa para copiar líneas.

- **Modo de Inserción:** Este modo se activa cuando se ejecuta el comando "vim [nombre_del_archivo.md]" y se entra al archivo en modo normal. Al presionar las teclas "a", "i" o "o", se pasa del modo normal al modo de inserción, donde se puede insertar texto.

- **Modo de Comandos:** Para salir del "modo de inserción", se presiona la tecla "esc", lo que lleva al modo de comandos. En este modo, se pueden guardar, cerrar o buscar algo dentro del archivo. Para guardar lo escrito, se utiliza el comando ":wq", que significa write and quit.

- **Modo Visual:** Este modo permite visualizar el archivo para copiar, borrar o editar texto. Se accede a él presionando la tecla "v" desde el modo normal.

- **Modo de Línea de Comandos (Ex mode):** Este modo es similar al modo de comandos normal, pero se accede desde la línea de comandos sin necesidad de abrir el archivo. Además, permite ejecutar scripts.

## **Comandos Básicos**

### Navegación:
- **h:** Moverse a la izquierda
- **j:** Moverse hacia abajo
- **k:** Moverse hacia arriba
- **l:** Moverse a la derecha

### Para moverse rápidamente:
- **gg:** Moverse al inicio del archivo
- **G:** Moverse al final del archivo
- **W:** Avanzar una palabra
- **b:** Retroceder una palabra

### Inserción y Edición:
- **i:** Entrar en el modo de inserción para comenzar a escribir antes del cursor.
- **a:** Entrar en el modo de inserción para escribir después del cursor.
- **o:** Entrar en el modo de inserción para escribir e insertar una línea debajo de la última línea de texto.

### Por último, un pequeño consejo: con el comando "vimtutor", se puede acceder a un mini-tutorial sobre cómo usar Vim.

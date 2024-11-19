# Trabajo, Sebastián
## **$¿$ $Qué$ $es$ $un$ $sistema$ $operativo$ $?$**
### Un sistema operativo, al igual que todo lo que hay en un dispositivo que no sea un hardware, es el software principal con el cual podemos manipular nuestro dispositivo, ya sea una PC o un celular, o tablet.

### Es lo que permite una interacción entre dispositivo y usuario.
### Ejemplo: Windows, Mac OS, Android, iOS, LINUX.
# 

## **$¿$ $Qué$ $hace$ $un$ $administrador$ $de$ $sistemas$ $?$**
### Es el responsable de, por así decirlo, de configurar todo y darle mantenimiento, supervisar los procesos, ser una parte fundamental de la seguridad de la organización.

# 

# **$Dispositivos$ $de$ $entrada$ $,$ $salida$ $y$ $mixto$**
### Los dispositivos de entrada son los que permiten al usuario dar todo tipo de valores.
### Ejemplos: Teclado, micrófono, cámara.

### Los dispositivos de salida, a diferencia de los de entrada, no reciben, sino que muestra información, por ejemplo, porque antes el usuario escribió o mandó algo.

### Ejemplos: Monitor, proyector o bocinas.

### Los dispositivos mixtos son la combinación de los dos anteriores, es decir, que pueden recibir y dar información, y un ejemplo perfecto para este tipo, son las pantallas táctiles, pues si no contamos el teclado, el puro monitor muestra imagen y puede funcionar como teclado.

# 

# **$Comandos$ $Unix$** 
### Los comandos de unix son instrucciones que se usan para realizar todas las tareas desde la terminal, pues nos dan la posibilidad de interactuar directamente con el sistema operativo
### estos son la lista de los comandos de Unix, mas usados.
### ls: Lista el contenido de un directorio.
### cd: Cambia el directorio actual.
### pwd: Muestra la ruta del directorio actual.
### cp: Copia archivos o directorios.
### mv: Mueve o renombra archivos.
### rm: Elimina archivos o directorios.
### chmod: Cambia los permisos de un archivo o directorio.
### ps: Muestra los procesos en ejecución.
### kill: Finaliza procesos.
### man: Muestra el manual de un comando.

# 

# **$GIT$**
### Este es un sistema de control de versiones, es decir, es un programa que ayuda a gestionar cambios realizados en un proyecto.
### Como por ejemplo el programa **GIT BASH** donde lo puedes vincular con la plataforma de GitHub, pudiendo subir, modificar y borrar archivos desde ahí, pudiendo rastrear cambios que tu o tus compañeros hagan, poder trabajar con tus compañeros desde multiples dispositivos y de igual manera, poder crear un respaldo de tus proyectos.

### Pero incluso, hay variaciones para sistemas de controlador de versiones
### Sistemas locales: Todo es manipulado en un solo equipo.
### Sistemas centralizados: Ahora todos los trabajos, o mejor dicho, las versiones son almacenadas en un servidor central.
### Ejemplo: Subversion (SVN)
### Sistemas distribuidos: En este tipo, todos los usuarios tienen una copia completa del historial del proyecto, pudiendo incluso trabajar sin conexión
### Ejemplo: GIT
# 
# **$Comandos$ $UNIX$ $para$ $la$ $administración$ $de$ $procesos$**
### A pesar de ya haber mencionado a los procesos de UNIX, en este caso los tomaremos desde la area de procesos, por ejemplo, el comando de "ps" sirve para mostrar información sobre los procesos que estan en ejecución; tiene varias variaciones como por ejemplo: "ps -e" el cual muestra todos los procesos, "ps -f" da información detallada( como el usuario, PID), "ps aux" muestra todos los procesos con muchos mas detalles.

### El comando de "top" monitorea los procesos en tiempo real y su variación "htop" que es solamente una version mas colorida del comando top. 
### En el apartado de ***gestión de procesos***, el comando "kill" se usa para terminar un proceso usando su PID. Y si por ejemplo, llegan a haber varios procesos con un nombre en común, por ejemplo "GOOGLE" se podria usar el comando "killall" y el nombre de los procesos, ejemplo: "killall google."
### Para los procesos en segundo plazo se usa el comando "jobs" y si es que se quiere traer un proceso en segundo plazo a primer plazo, usamos el comando "fg" y el numero dado por el comando "jobs". Ejemplo: fg %1.
### Y por el otro lado, si es que se busca mandar un proceso a segundo plano usamos el comando de "bg" y el numero dado por el comando "jobs". Ejemplo: "bg %1"
### En el apartado de ***priorización de procesos*** se usa el comando "nice" para iniciar un proceso con cierta prioridad (siendo 1 la mayor prioridad), y su variación "renice" cambia la prioridad, no es igual, puesto que "nice" crea y "renice" cambia.
### "pidof" obtiene el PID de algun proceso.
# 
# **$¿$ $Qué$ $es$ $un$ $proceso$ $?$**
### Esta es una instancia en estado de ejecución, en si, un proceso es una tarea activa, cada proceso tiene un identificador propio de nombre "PID", dicho nombre proviene de su nombre en ingles "Process ID". Cada proceso consume recursos del dispostivo, es decir, asi como tiene un ID propio, tambien se le asignan la cantidad de RAM, CPU, Archivos y dispositivos. Pero no solo se le asignan/consume recursos, sino que tambien cada proceso puede estar en diferentes estados, que son los siguientes:
- **Nuevo**:Acaba de ser creado dicho proceso, sin embargo, aún no se ha ejecutado.
- **Ejecutando**:El proceso ya ha empezado a ejecutarse, usando parte de los recursos del dispositivo.
- **Bloqueado**:Puede bloquearse para que así, no consuma recursos en dado caso de estar activo sin mucha prioridad.
- **Listo**:Ya esta listo para poder ejecutarse.
- **Terminado**: El proceso ya ha terminado.
# 
## Tipos de procesos
### Y así como un proceso puede tener diferentes estados, de igual manera existen tipos de procesos, de "Primer plano","Segundo Plano" y "Procesos del sistema".
### Los procesos en ***primer plano***, son aquellos creados por el usuario, es decir, aquellos como block de notas o un navegador que requierern interacción directa. 
### Los procesos de ***segundo plano***, son los creados por asi decirlo " por el propio dispositivo", no requieren interacción del usuario, y normalmente suelen ser actualizaciones automaticas o de servidores web.
### Y los ***procesos del sistema***, como su nombre lo indica, son **esenciales** para el funcionamiento del sistema operativo, pues aquí es donde aparecen los contoladores o servicios de red, o mejor conocidos como drivers.
# 
# **$Comandos$ $adicionales$ $(wildcard,$ $rm,$ $mv$, $ls,$ $obtener$ $peso$ $ordenado)$**
### A pesar de que ya abordamos los comandos usados en UNIX, existen otros cuantos que vale la pena mencionar, los **"wild cards"** son caracteres especiales usados más que nada para representar varios caracteres en archivos y directorios, se usan para seleccionar varios archivos a la vez.
### El "* " se usa para nombrar todos los archivos con una terminación especifica que va despues del asterisco, un ejemplo: "ls ( *.txt )* , el signo de interrogación "?" es usado para mostrar todos los archivos con un nombre en comun, por ejemplo si corremos este comando "ls archivo?.txt" un ejemplo de resultado seria asi: archivo1.txt, archivo2.txt, archivo3.txt, archivo4.txt
### Al usar los corchetes "[]" ocurre algo similar que con el comando anterior(ls * ) solamente que con los corchetes podemos verlo con un rango especifico, es decir, un ejemplo del comando seria "ls archivo[1-3]" y el resultado serian: archivo1.txt, archivo2.txt, archivo3.txt
### Hay otro comando que es muy similar a los corchetes, y son las llaves "{}", sus usos son muy similares, sin embargo su diferencia radica en que las llaves {}, se puede usar para generar patrones al nombrar archivos, por ejemplo "ls archivo{1,final}", su resultado siendo: "archivo1.txt, archivofinal.txt"




# **$Comandos$ $UNIX$ $para$ $la$ $administración$ $de$ $procesos$**
### A pesar de ya haber mencionado a los procesos de UNIX, en este caso los tomaremos desde la area de procesos, por ejemplo, el comando de "ps" sirve para mostrar información sobre los procesos que estan en ejecución; tiene varias variaciones como por ejemplo: "ps -e" el cual muestra todos los procesos, "ps -f" da información detallada( como el usuario, PID), "ps aux" muestra todos los procesos con muchos mas detalles.

### El comando de "top" monitorea los procesos en tiempo real y su variación "htop" que es solamente una version mas colorida del comando top.
### En el apartado de ***gestión de procesos***, el comando "kill" se usa para terminar un proceso usando su PID. Y si por ejemplo, llegan a haber varios procesos con un nombre en común, por ejemplo "GOOGLE" se podria usar el comando "killall" y el nombre de los procesos, ejemplo: "killall google."
### Para los procesos en segundo plazo se usa el comando "jobs" y si es que se quiere traer un proceso en segundo plazo a primer plazo, usamos el comando "fg" y el numero dado por el comando "jobs". Ejemplo: fg %1.
### Y por el otro lado, si es que se busca mandar un proceso a segundo plano usamos el comando de "bg" y el numero dado por el comando "jobs". Ejemplo: "bg %1"
### En el apartado de ***priorización de procesos*** se usa el comando "nice" para iniciar un proceso con cierta prioridad (siendo 1 la mayor prioridad), y su variación "renice" cambia la prioridad, no es igual, puesto que "nice" crea y "renice" cambia.
### "pidof" obtiene el PID de algun proceso.


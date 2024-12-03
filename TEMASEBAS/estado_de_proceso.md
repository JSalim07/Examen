# **$Estados$ $de$ $un$ $proceso$**
<span style="font-size: 17px;"></span>
<span style="font-size: 18px;"><strong></strong></span>

## El proceso puede tener varios estados, aqui los enlistare de manera cronologica:
<span style="font-size: 18px;"><strong>Nuevo</strong></span> <span style="font-size: 17px;">El proceso acaba de ser creado, sin embargo, aun no ha sido iniciado, pues aun no esta listo ni se le ha asignado nada.</span> 

<span style="font-size: 18px;"><strong>Listo(Ready):</strong></span> <span style="font-size: 17px;">Ya en este paso, ya esta listo para iniciarse, solamente que aun no se le ha asignado un proceso el cual sera el encargado de ejecutarlo.</span> <span style="font-size: 17px;">Nota: Un proceso puede volver al estado "Listo" si el sistema operativo decide interrumpirlo para dar prioridad a otro.</span>

<span style="font-size: 18px;"><strong>En ejecución(running):</strong></span> <span style="font-size: 17px;">La CPU está ejecutando activamente las instrucciones del proceso. Solo un proceso puede estar en este estado por núcleo del procesador.</span>.

<span style="font-size: 18px;"><strong>En espera (Waiting o Blocked):</strong></span> <span style="font-size: 17px;">El proceso no puede continuar porque está esperando un evento, como la finalización de una operación de entrada/salida (E/S) o la disponibilidad de un recurso.</span>
   
- <span style="font-size: 16.5px;">Ejemplo: Si un proceso necesita leer un archivo, entra en este estado mientras espera a que el sistema de archivos lo cargue.</span>

<span style="font-size: 18px;"><strong>Terminado (Terminated):</strong></span> <span style="font-size: 17px;">El proceso ha completado su ejecución o ha sido detenido por el sistema operativo.
Los recursos asignados al proceso se liberan y el sistema operativo elimina su referencia de la tabla de procesos.</span>

#
# Transiciones entre estados
### ¿Qué significa las transiciones entre estados?
### R: De Nuevo a Listo: Ocurre cuando el sistema operativo ha terminado de configurar el proceso.
### De Listo a En ejecución: El proceso es seleccionado por el planificador de la CPU (Scheduler) para ejecutarse.
### En ejecución a Listo: Ocurre cuando el proceso es interrumpido, ya sea por el sistema operativo o porque se ha alcanzado el límite de tiempo de CPU asignado (time slice).
### En ejecución a En espera: El proceso necesita esperar un recurso o la finalización de una operación.
### En espera a Listo: El evento esperado ocurre, y el proceso puede continuar ejecutándose.
### En ejecución o Listo a Terminado: El proceso completa su tarea o es terminado por el sistema.

- <span style="font-size: 17px;">Representación:</span>

          Nuevo
            ↓
         Listo ←→ En ejecución
            ↓         ↓
        En espera    Terminado

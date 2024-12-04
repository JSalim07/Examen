# **Estados de un Proceso**

## El proceso puede tener varios estados, aquí se enlistan de manera cronológica:

| Estado | Descripción |
|--------|-------------|
| **Nuevo** | El proceso acaba de ser creado, sin embargo, aún no ha sido iniciado, pues aún no está listo ni se le ha asignado nada. |
| **Listo (Ready)** | Ya en este paso, está listo para iniciarse, solamente que aún no se le ha asignado un proceso el cual será el encargado de ejecutarlo. <br> **Nota:** Un proceso puede volver al estado "Listo" si el sistema operativo decide interrumpirlo para dar prioridad a otro. |
| **En ejecución (Running)** | La CPU está ejecutando activamente las instrucciones del proceso. Solo un proceso puede estar en este estado por núcleo del procesador. |
| **En espera (Waiting o Blocked)** | El proceso no puede continuar porque está esperando un evento, como la finalización de una operación de entrada/salida (E/S) o la disponibilidad de un recurso. <br> **Ejemplo:** Si un proceso necesita leer un archivo, entra en este estado mientras espera a que el sistema de archivos lo cargue. |
| **Terminado (Terminated)** | El proceso ha completado su ejecución o ha sido detenido por el sistema operativo. Los recursos asignados al proceso se liberan y el sistema operativo elimina su referencia de la tabla de procesos. |

## Transiciones entre Estados

### ¿Qué significan las transiciones entre estados?

- **De Nuevo a Listo:** Ocurre cuando el sistema operativo ha terminado de configurar el proceso.
- **De Listo a En ejecución:** El proceso es seleccionado por el planificador de la CPU (Scheduler) para ejecutarse.
- **En ejecución a Listo:** Ocurre cuando el proceso es interrumpido, ya sea por el sistema operativo o porque se ha alcanzado el límite de tiempo de CPU asignado (time slice).
- **En ejecución a En espera:** El proceso necesita esperar un recurso o la finalización de una operación.
- **En espera a Listo:** El evento esperado ocurre, y el proceso puede continuar ejecutándose.
- **En ejecución o Listo a Terminado:** El proceso completa su tarea o es terminado por el sistema.

### Representación Gráfica:

```plaintext
          Nuevo
            ↓
         Listo ←→ En ejecución
            ↓         ↓
        En espera    Terminado

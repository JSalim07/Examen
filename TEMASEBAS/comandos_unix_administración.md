# **$Comandos$ $UNIX$ $para$ $la$ $administración$ $de$ $procesos$**

### A continuación, se presentan los comandos más utilizados en UNIX para la administración de procesos, organizados de manera formal y profesional.

## Comandos para Visualización de Procesos

| Comando | Descripción | Ejemplo |
|---------|-------------|---------|
| `ps`    | Muestra información sobre los procesos en ejecución. | `ps` |
| `ps -e` | Muestra todos los procesos en ejecución. | `ps -e` |
| `ps -f` | Proporciona información detallada sobre los procesos (usuario, PID, etc.). | `ps -f` |
| `ps aux`| Muestra todos los procesos con detalles adicionales. | `ps aux` |

## Comandos para Monitoreo de Procesos

| Comando | Descripción | Ejemplo |
|---------|-------------|---------|
| `top`   | Monitorea los procesos en tiempo real. | `top` |
| `htop`  | Versión más colorida y amigable de `top`. | `htop` |

## Comandos para Gestión de Procesos

| Comando | Descripción | Ejemplo |
|---------|-------------|---------|
| `kill`  | Termina un proceso usando su PID. | `kill 1234` |
| `killall` | Termina todos los procesos con un nombre específico. | `killall google` |
| `jobs`  | Muestra los procesos en segundo plano. | `jobs` |
| `fg`    | Trae un proceso en segundo plano al primer plano. | `fg %1` |
| `bg`    | Envía un proceso al segundo plano. | `bg %1` |

## Comandos para Priorización de Procesos

| Comando | Descripción | Ejemplo |
|---------|-------------|---------|
| `nice`  | Inicia un proceso con una prioridad específica (siendo 1 la mayor prioridad). | `nice -n 10 comando` |
| `renice`| Cambia la prioridad de un proceso existente. | `renice 5 -p 1234` |

## Otros Comandos Útiles

| Comando | Descripción | Ejemplo |
|---------|-------------|---------|
| `pidof` | Obtiene el PID de un proceso específico. | `pidof nombre_del_proceso` |

### Ejemplos de Uso

- **Visualización de Procesos:**
  - `ps -e` muestra todos los procesos en ejecución.
  - `ps -f` proporciona información detallada sobre los procesos.

- **Monitoreo de Procesos:**
  - `top` monitorea los procesos en tiempo real.
  - `htop` es una versión más amigable de `top`.

- **Gestión de Procesos:**
  - `kill 1234` termina el proceso con PID 1234.
  - `killall google` termina todos los procesos con el nombre "google".
  - `jobs` muestra los procesos en segundo plano.
  - `fg %1` trae el proceso número 1 del segundo plano al primer plano.
  - `bg %1` envía el proceso número 1 al segundo plano.

- **Priorización de Procesos:**
  - `nice -n 10 comando` inicia un proceso con prioridad 10.
  - `renice 5 -p 1234` cambia la prioridad del proceso con PID 1234 a 5.

- **Otros Comandos:**
  - `pidof nombre_del_proceso` obtiene el PID del proceso especificado.

Estos comandos son esenciales para la administración eficiente de procesos en sistemas UNIX, permitiendo a los usuarios monitorear, gestionar y priorizar procesos de manera efectiva.

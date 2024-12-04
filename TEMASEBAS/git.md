# **GIT**

## ¿Qué es GIT?

GIT es un sistema de control de versiones, es decir, un programa que ayuda a gestionar cambios realizados en un proyecto. Un ejemplo de su uso es el programa **GIT BASH**, que se puede vincular con la plataforma de GitHub, permitiendo subir, modificar y borrar archivos, rastrear cambios realizados por ti o tus compañeros, trabajar desde múltiples dispositivos y crear un respaldo de tus proyectos.

## Tipos de Sistemas de Control de Versiones

Existen varias variaciones de sistemas de control de versiones:

| Tipo de Sistema | Descripción | Ejemplo |
|-----------------|-------------|---------|
| **Sistemas Locales** | Todo es manipulado en un solo equipo. | - |
| **Sistemas Centralizados** | Las versiones son almacenadas en un servidor central. | Subversion (SVN) |
| **Sistemas Distribuidos** | Todos los usuarios tienen una copia completa del historial del proyecto, pudiendo incluso trabajar sin conexión. | GIT |

## Características de GIT

### Ventajas

- **Distribuido:** Cada usuario tiene una copia completa del historial del proyecto.
- **Velocidad:** Las operaciones locales son muy rápidas.
- **Integridad:** Cada cambio es registrado con un hash criptográfico.
- **Flexibilidad:** Soporta múltiples flujos de trabajo y modelos de desarrollo.

### Comandos Básicos:

| Comando | Descripción |
|---------|-------------|
| `git init` | Inicializa un nuevo repositorio GIT. |
| `git clone` | Clona un repositorio existente. |
| `git add` | Añade archivos al área de preparación. |
| `git commit` | Guarda los cambios en el historial del proyecto. |
| `git push` | Envía los cambios al repositorio remoto. |
| `git pull` | Actualiza el repositorio local con los cambios del remoto. |
| `git status` | Muestra el estado de los archivos en el repositorio. |
| `git log` | Muestra el historial de commits. |

## Flujo de Trabajo en GIT

1. **Inicialización:** Crear un nuevo repositorio con `git init` o clonar uno existente con `git clone`.
2. **Modificación:** Realizar cambios en los archivos del proyecto.
3. **Preparación:** Añadir los cambios al área de preparación con `git add`.
4. **Confirmación:** Guardar los cambios en el historial del proyecto con `git commit`.
5. **Sincronización:** Enviar los cambios al repositorio remoto con `git push` y actualizar el repositorio local con `git pull`.

## TIPS

- **Commits Frecuentes:** Realizar commits pequeños y frecuentes para facilitar el seguimiento de cambios.
- **Mensajes Claros:** Escribir mensajes de commit descriptivos y claros.
- **Ramas:** Utilizar ramas para desarrollar nuevas características o corregir errores sin afectar la rama principal.
- **Revisiones de Código:** Realizar revisiones de código para mantener la calidad del proyecto.

## Recursos Adicionales

- [Documentación Oficial de GIT](https://git-scm.com/doc)
- [Guía de GIT en GitHub](https://guides.github.com/introduction/git-handbook/)
- [Curso Interactivo de GIT](https://learngitbranching.js.org/)


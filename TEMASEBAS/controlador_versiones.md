# Controlador de Versiones

### Un controlador de versiones es una herramienta utilizada para gestionar cambios realizados a un conjunto de archivos a lo largo del tiempo. Es ampliamente utilizado por profesionales de "IT" ya que permite rastrear modificaciones del código y colaborar con otros desarrolladores.

## ¿Por qué es importante?

- **Historial de Cambios:** Permite mantener un registro detallado de los cambios realizados, incluyendo información sobre quién hizo cada cambio y qué incluye la modificación. Esto se conoce como "seguimiento de cambios".
- **Colaboración:** Facilita el trabajo en equipo, permitiendo que varias personas trabajen en el mismo proyecto desde diferentes computadoras, pudiendo subir, modificar o borrar archivos.
- **Reversión de Cambios:** Si se comete un error, es posible remediarlo fácilmente volviendo a una versión anterior del proyecto utilizando el comando `git checkout <ID-del-commit>`. Para conocer el identificador de los commits, se puede usar el comando `git log`, que muestra un historial de los commits realizados.

## Tipos de Sistemas de Control de Versiones

| Tipo           | Descripción                                                                 | Ejemplo                      |
|----------------|-----------------------------------------------------------------------------|------------------------------|
| **Locales**    | Los archivos y el historial de cambios se gestionan en un único equipo.     | Copias manuales de archivos. |
| **Centralizados** | Un servidor central almacena todos los cambios y los usuarios deben conectarse para obtener la versión más reciente o para guardar cambios. | Subversion (SVN)             |
| **Distribuidos** | Cada usuario tiene una copia completa del repositorio, lo que permite trabajar sin conexión y sincronizar cambios posteriormente. | Git (el más popular hoy en día) |

## Beneficios del Control de Versiones

- **Seguridad:** Los cambios se almacenan de forma segura, evitando la pérdida de datos.
- **Productividad:** Permite a los equipos trabajar simultáneamente en diferentes partes del proyecto sin interferir entre sí.
- **Documentación:** Proporciona un registro detallado de qué cambios se hicieron, quién los hizo y por qué.
- **Compatibilidad:** Facilita mantener múltiples versiones de un proyecto, como lanzamientos anteriores y nuevos desarrollos.
#
## Ejemplo Práctico

<span style="font-size: 16.8px;">Inicializar un nuevo repositorio</span>

   -  ```git bash
        git init
        ```

<span style="font-size: 16.8px;">Añadir cambios:</span>

   -  ```git bash
        git add archivo.txt
        ```

<span style="font-size: 16.8px;">Registrar los cambios</span>

   -  ```git
        git commit -m "Mensaje del cambio"
        ```
<span style="font-size: 16.8px;">Obtener cambios del equipo:</span>

   -  ```git
        git pull
        ```

<span style="font-size: 16.8px;">Enviar cambios:</span>

   -  ```git
        git push
        ```
#
# Ejemplo de Sistemas Populares

| Sistema   | Descripción                                                                 |
|-----------|-----------------------------------------------------------------------------|
| Git       | Distribuido, rápido, versátil, usado por plataformas como GitHub, GitLab, y Bitbucket. |
| SVN       | Centralizado, aún usado en algunas organizaciones más antiguas.             |
| Mercurial | Distribuido, con una curva de aprendizaje más suave que Git.                |
| Perforce  | Popular en grandes empresas por su robustez en proyectos de gran escala.    |

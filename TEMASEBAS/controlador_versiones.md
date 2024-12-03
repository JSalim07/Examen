# **$Controlador$ $de$ $versiones$**
### Un controlador es una herramienta que es utilizada para gestionar cambios hechos a un conjunto de archivos a lo largo del tiempo. Es muy usado por personas pertenecientes al mundo de "IT", pues da la posibilidad de rastrear modificaciones del código y colaborar con otros desarrolladores.
## ¿Por qué es importante?
### Puedes tener un historial de los cambios realizados e información tanto de quién hizo dicho cambio, como de que incluye la modificación. A esto se le conoce como "seguimiento de cambios".
### Una ventaja de usar git bash o en sí cualquier controlador de versiones, es la "colaboración", nuestro siguiente apartado. Esto último se basa en poder trabajar en un mismo proyecto desde varias computadoras a la vez, pudiendo cualquier persona que de sea parte del trabajo; subir, modificar o borrar archivos.
### Si alguien comete un error, se puede remediar facilmente volviendo a la versión anterior. Esto es posible haciendo el siguiente comando: "git checkout <ID-del-commit>", esto lo que hara sera poner tu proyecto en el estado de ese commit en especifico; para conocer el identificador de los commits deberas hacer le comando "git log" que es un historial de los commits hechos hasta el momento.
#
## Tipos de sistemas de control de versiones.
### **Locales:** Los archivos y el historial de cambios se gestionan en un único equipo.

- <span style="font-size: 16.8px;">Ejemplo: Copias manuales de los archivos.</span>

### **Centralizados:** Un servidor central almacena todos los cambios y los usuarios deben conectarse para obtener la versión más reciente o para guardar cambios.
- <span style="font-size: 16.8px;">Ejemplo: Subversion (SVN).</span>

### **Distribuidos:** Cada usuario tiene una copia completa del repositorio, lo que permite trabajar sin conexión y sincronizar cambios posteriormente.
- <span style="font-size: 16.8px;">Ejemplo: Git (el más popular hoy en día).
</span>

# 
## Beneficios del control de versiones
### Seguridad: Los cambios se almacenan de forma segura, evitando la pérdida de datos.

### Productividad: Permite a los equipos trabajar simultáneamente en diferentes partes del proyecto sin interferir entre sí.

### Documentación: Proporciona un registro detallado de qué cambios se hicieron, quién los hizo y por qué.

### Compatibilidad: Facilita mantener múltiples versiones de un proyecto, como lanzamientos anteriores y nuevos desarrollos.

#
#
# Ejemplo practico
## Inicializar un repositorio:

### Crear un nuevo repositorio para almacenar archivos y su historial.
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
#
# Ejemplo de sistemas populares
----------

### **Git:** Distribuido, rápido, versátil, usado por plataformas como GitHub, GitLab, y Bitbucket.
### **SVN:** Centralizado, aún usado en algunas organizaciones más antiguas.
### **Mercurial:** Distribuido, con una curva de aprendizaje más suave que Git.
### **Perforce:** Popular en grandes empresas por su robustez en proyectos de gran escala.

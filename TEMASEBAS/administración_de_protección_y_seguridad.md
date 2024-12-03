# Administración de la protección y seguridad.
### La administración de la protección y seguridad es una de las tareas más importantes que realiza un sistema operativo (SO). Su objetivo es garantizar que los recursos del sistema (como datos, archivos, procesos y hardware) estén protegidos contra accesos no autorizados, modificaciones maliciosas o daños accidentales. Además, asegura que los usuarios legítimos puedan acceder a los recursos que necesitan.

### A continuación, se explica en detalle cómo los sistemas operativos gestionan la protección y la seguridad:

<span style="font-size: 18px;">Protección</span>
- <span style="font-size: 16.5px;">La protección en un sistema operativo se centra en el control del acceso a los recursos. Esto incluye archivos, procesos, memoria, dispositivos y otros componentes. Los principales aspectos de la protección son:</span>

- <span style="font-size: 16.5px;">Control de Acceso
</span>
- <span style="font-size: 16.5px;">El sistema operativo define políticas que determinan quién puede acceder a un recurso y qué acciones pueden realizar.
Utiliza listas de control de acceso (ACL), que especifican los permisos para cada usuario o grupo.
Ejemplo: Solo un usuario puede leer o modificar un archivo, mientras que otros solo pueden visualizarlo.</span>

<span style="font-size: 18px;">Mecanismos de Protección</span>
- <span style="font-size: 16.5px;">Autenticación: Verifica la identidad de un usuario mediante contraseñas, sistemas biométricos (huella dactilar, reconocimiento facial), o tokens.
Autorización: Determina si un usuario tiene los permisos necesarios para realizar una acción específica.
</span>

- <span style="font-size: 16.4px;">Cifrado: Protege los datos almacenados o en tránsito, para que solo los usuarios autorizados puedan acceder a ellos.</span>
- <span style="font-size: 16.8px;">Aislamiento</span>

    - <span style="font-size: 16.5px;">
        El SO aísla los procesos para que no interfieran entre sí. Esto asegura que un proceso malicioso no afecte a otros.
        La memoria y los recursos asignados a cada proceso están protegidos de accesos no autorizados por parte de otros procesos.</span>

<span style="font-size: 18px;"> Seguridad:</span>

<span style="font-size: 16.5px;">La seguridad se ocupa de proteger el sistema frente a amenazas externas, como malware, hackers o fallos del sistema. Los sistemas operativos implementan múltiples medidas para garantizar la seguridad:</span>

<span style="font-size: 16.5px;">Autenticación y Gestión de Usuarios</span>

- <span style="font-size: 16.5px;">Contraseñas Seguras: Requiere contraseñas fuertes y fomenta políticas de cambio periódico.
</span>
- <span style="font-size: 16.5px;">Múltiples Niveles de Usuario: Diferencia entre usuarios regulares y administradores con más privilegios.</span>

- <span style="font-size: 16.5px;">Inicio de Sesión Seguro: Implementa medidas para evitar ataques como el "phishing" o la adivinación de contraseñas.</span>

<span style="font-size: 16.5px;">Permisos y Privilegios</span>

<span style="font-size: 16.5px;">Cada archivo, directorio y proceso tiene un conjunto de permisos que define qué usuarios o grupos pueden:</span>

- <span style="font-size: 16.5px;">Leer (R - read)</span>

- <span style="font-size: 16.5px;">Escribir (W - write)</span>

- <span style="font-size: 16.5px;">Ejecutar (X - execute)</span>

<span style="font-size: 16.5px;">Ejemplo en UNIX: chmod y chown permiten modificar estos permisos.</span>

<span style="font-size: 18px;">Firewall y Seguridad en Red</span>

<span style="font-size: 16.5px;">Un firewall es una barrera de seguridad que controla el tráfico de red entrante y saliente basado en reglas de seguridad predeterminadas. Los firewalls pueden ser hardware, software o una combinación de ambos.</span>

<span style="font-size: 16.5px;">Tipos de Firewalls:</span>

- <span style="font-size: 16.5px;">Firewalls de Red: Protegen redes enteras y se colocan en el perímetro de la red.</span>
- <span style="font-size: 16.5px;">Firewalls de Host: Protegen dispositivos individuales y se instalan en cada dispositivo.</span>

<span style="font-size: 16.5px;">Funciones de un Firewall:</span>

- <span style="font-size: 16.5px;">Filtrado de Paquetes: Inspecciona los paquetes de datos y permite o bloquea su paso según las reglas de seguridad.</span>
- <span style="font-size: 16.5px;">Inspección de Estado: Monitorea el estado de las conexiones de red y permite el paso solo a los paquetes que forman parte de una conexión establecida.</span>
- <span style="font-size: 16.5px;">Proxy: Actúa como intermediario entre los usuarios y los recursos de red, proporcionando una capa adicional de seguridad.</span>
- <span style="font-size: 16.5px;">NAT (Traducción de Direcciones de Red): Oculta las direcciones IP internas de la red, haciendo que todas las solicitudes salientes parezcan provenir de una única dirección IP pública.</span>

<span style="font-size: 16.5px;">Configuración de un Firewall:</span>

- <span style="font-size: 16.5px;">Definir Reglas de Seguridad: Establecer reglas claras sobre qué tráfico se permite y qué tráfico se bloquea.</span>
- <span style="font-size: 16.5px;">Monitoreo y Registro: Supervisar el tráfico de red y mantener registros de las actividades para detectar y responder a posibles amenazas.</span>
- <span style="font-size: 16.5px;">Actualización Regular: Mantener el firewall actualizado con las últimas definiciones de amenazas y parches de seguridad.</span>

- <span style="font-size: 16.5px;">El SO incluye un firewall que regula el tráfico de red entrante y saliente según las reglas definidas.</span>
- <span style="font-size: 16.5px;">Bloquea accesos no autorizados desde la red, como intentos de hacking.</span>

- <span style="font-size: 16.5px;">Protección contra Malware</span>
- <span style="font-size: 16.5px;">Escanea archivos en busca de virus, troyanos o programas maliciosos.</span>
- <span style="font-size: 16.5px;">Implementa estrategias de sandboxing, donde las aplicaciones se ejecutan en entornos aislados, reduciendo el impacto de un posible malware.</span>

<span style="font-size: 16.5px;">Auditoría y Registro (Logging)</span>
- <span style="font-size: 16.5px;">El sistema operativo mantiene registros de las acciones realizadas por los usuarios y procesos. Esto ayuda en la detección y análisis de posibles fallos de seguridad o violaciones. Los aspectos clave incluyen:</span>

- <span style="font-size: 16.5px;">Registros de Acceso: Muestran quién accedió a un archivo o recurso y qué acciones realizó.</span>
- <span style="font-size: 16.5px;">Alertas de Seguridad: Notifican intentos de acceso no autorizado.</span>
- <span style="font-size: 16.5px;">Análisis Posterior: Permiten reconstruir los eventos en caso de un incidente.</span>

<span style="font-size: 16.5px;">Cifrado de Datos</span>
- <span style="font-size: 16.5px;">El cifrado asegura que los datos sean accesibles solo para usuarios autorizados. El sistema operativo puede cifrar:</span>

- <span style="font-size: 16.5px;">Archivos individuales: Para proteger información sensible.</span>
- <span style="font-size: 16.5px;">Discos completos: Para proteger datos en dispositivos de almacenamiento (como discos duros o unidades USB).</span>

<span style="font-size: 16.5px;">Respaldo y Recuperación</span>
- <span style="font-size: 16.5px;">El sistema operativo facilita la creación de copias de seguridad de los datos importantes y la restauración en caso de pérdida o corrupción:</span>

- <span style="font-size: 16.5px;">Respaldo Automático: Los datos se guardan periódicamente en ubicaciones seguras.</span>
- <span style="font-size: 16.5px;">Restauración Rápida: Permite recuperar archivos o configuraciones dañadas.</span>

<span style="font-size: 16.5px;">Políticas de Seguridad</span>
- <span style="font-size: 16.5px;">Los sistemas operativos modernos permiten a los administradores establecer políticas de seguridad que:</span>

- <span style="font-size: 16.5px;">Restringen el acceso a recursos críticos.</span>
- <span style="font-size: 16.5px;">Implementan límites de tiempo de sesión.</span>
- <span style="font-size: 16.5px;">Obligan a los usuarios a utilizar contraseñas seguras.</span>

<span style="font-size: 16.5px;">Actualizaciones y Parches</span>
- <span style="font-size: 16.5px;">Los sistemas operativos se actualizan regularmente para corregir vulnerabilidades descubiertas y fortalecer la seguridad del sistema. Las actualizaciones pueden incluir:</span>

- <span style="font-size: 16.5px;">Correcciones de errores.</span>
- <span style="font-size: 16.5px;">Mejoras en la gestión de permisos.</span>
- <span style="font-size: 16.5px;">Nuevas herramientas de protección.</span>

- <span style="font-size: 16.5px;">Resumen de Protección y Seguridad en el SO</span>
- <span style="font-size: 16.5px;">Aspecto Descripción</span>
- <span style="font-size: 16.5px;">Autenticación Verifica la identidad del usuario mediante contraseñas, biometría o tokens.</span>
- <span style="font-size: 16.5px;">Autorización Define qué acciones puede realizar un usuario sobre un recurso.</span>
- <span style="font-size: 16.5px;">Cifrado Protege datos sensibles mediante técnicas de encriptación.</span>
- <span style="font-size: 16.5px;">Firewall Controla el tráfico de red para evitar accesos no autorizados.</span>
- <span style="font-size: 16.5px;">Auditoría Registra las actividades del sistema para detectar y analizar violaciones de seguridad.</span>
- <span style="font-size: 16.5px;">Actualizaciones Mantiene el sistema protegido con los últimos parches de seguridad.</span>
- <span style="font-size: 16.5px;">Gestión de Permisos Restringe acciones como lectura, escritura o ejecución para archivos y procesos.</span>

- <span style="font-size: 16.5px;">Importancia</span>
- <span style="font-size: 16.5px;">La protección y seguridad en un sistema operativo son fundamentales para:</span>

- <span style="font-size: 16.5px;">Prevenir la pérdida de datos.</span>
- <span style="font-size: 16.5px;">Evitar accesos no autorizados.</span>
- <span style="font-size: 16.5px;">Proteger la privacidad del usuario.</span>
- <span style="font-size: 16.5px;">Garantizar el funcionamiento confiable del sistema.</span>

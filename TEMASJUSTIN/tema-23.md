## $Virtualización$ $del$ $CPU$

## Máquina Virtual (VM): 
Una máquina virtual simula un sistema completo (incluido el procesador) que opera de forma independiente.

## Hypervisor:

Es un software que gestiona la virtualización (por ejemplo, VMware, Hyper-V, o VirtualBox).
El hypervisor utiliza las tecnologías de virtualización del CPU para asignar núcleos lógicos y recursos a las VMs.

## Asignación de núcleos:

Cada VM puede tener asignados uno o más núcleos físicos o lógicos.
Aunque una VM puede "ver" múltiples núcleos virtuales, estos son gestionados por el hypervisor para compartirlos entre todas las máquinas virtuales.

## $Virtualización$ $de$ $Memoria$

La virtualización de memoria permite que los programas usen direcciones virtuales, las cuales el sistema operativo traduce a direcciones físicas en la RAM. 

## Direcciones virtuales y físicas: 
Las direcciones virtuales son usadas por los programas, mientras que las físicas corresponden a la RAM real.

## Segmentación: 
Divide la memoria en segmentos de tamaño variable, asociando cada uno con diferentes partes del programa.

## Paginación: 
Divide la memoria en páginas y marcos de pagina, usando una tabla de páginas para mapear direcciones virtuales a físicas.

## MMU (Unidad de Gestión de Memoria): 
Traduce las direcciones virtuales a físicas mediante la tabla de páginas.

## Swapping: 
Mueve datos entre la RAM y el almacenamiento secundario (como un disco duro o SSD) cuando la RAM está llena.
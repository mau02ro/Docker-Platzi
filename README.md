# Curso de Docker

    Docker te permite construir, distribuir y ejecutar cualquier aplicación en cualquier lado.

1. **Construir** - Escribir código en la máquina del desarrollador. (Compile, que no compile, arreglar el bug, compartir código, etc. )

**Problemática**:

- Entorno de desarrollo (paquetes)
- Dependencias (Frameworks, bibliotecas)
- Versiones de entornos de ejecución (runtime, versión Node)
- Equivalencia de entornos de desarrollo (compartir el código)
- Equivalencia con entornos productivos (pasar a producción)
- Servicios externos (integración con otros servicios ejem: base de datos)

2. **Distribuir** - Llevar la aplicación donde se va a desplegar (Transformarse en un artefacto)

**_Problemática_**:

- Output de build heterogeo (múltiples compilaciones)
- Acceso a servidores productivos (No tenemos acceso al servidor)
- Ejecución nativa vs virtualizada
- Entornos Serverless

3. **Ejecutar** - Implementar la solución en el ambiente de producción (Subir a producción). El reto Hacer que funcione como debería funcionar

**Problemática**:

- Dependencia de aplicación (paquetes, runtime)
- Compatibilidad con el entorno productivo (sistema operativo poco amigable con la solución)
- Disponibilidad de servicios externos (Acceso a los servicios externos)
- Recursos de hardware (Capacidad de ejecución - Menos memoria, procesador más debil)

## Virtualización

_Permite atacar en simultáneo los tres problemas del desarrollo de software profesional._

La virtualización es la creación a través de software de una versión virtual de algún recurso tecnológico, como puede ser una plataforma de hardware, un sistema operativo, un dispositivo de almacenamiento o cualquier otro recurso de red.

Dicho de otra manera, se refiere a la abstracción de los recursos de una computadora, llamada Hypervisor o VMM (Virtual Machine Monitor) que crea una capa de abstracción entre el hardware de la máquina física (host) y el sistema operativo de la máquina virtual (virtual machine, guest), dividiéndose el recurso en uno o más entornos de ejecución.

<img src="./assets/docker-vs-virtual-machines.png" />

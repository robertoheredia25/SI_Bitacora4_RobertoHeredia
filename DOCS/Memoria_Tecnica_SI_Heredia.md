# 

# 

# El Marco Legal y la Estructura del "Relato"

Nombre:Roberto Heredia Chaves  
Fecha: 15/05/2026
Ciclo:DAM


**Tabla de Contenido:**

**Índice**   
1. [Análisis de Necesidades](#id1)
2. [Segundo apartado](#id2)


# 1. Análisis de Necesidades <a name="id1"></a>
## ¿Qué problema de la empresa resolvemos con Guacamole y Docker

El principal problema que solucionamos en la empresa gracias a Guacamole y Docker es el típico “en mi ordenador sí funciona”. Muchas veces una aplicación funciona correctamente en un equipo, pero al intentar ejecutarla en otro aparecen errores por diferencias en configuraciones, librerías, versiones o sistemas operativos.

Docker evita este problema porque permite empaquetar la aplicación dentro de un contenedor junto con todo lo necesario para que funcione correctamente, como librerías, bases de datos, dependencias y configuraciones. De esta forma, el entorno siempre será el mismo independientemente del ordenador donde se ejecute.

Además, al ser compatible con distintos sistemas operativos como Windows, Linux o macOS, los contenedores pueden moverse fácilmente entre diferentes equipos sin necesidad de volver a configurar todo desde cero. Esto facilita mucho el trabajo en equipo y reduce errores técnicos.

Por otro lado, Guacamole permite acceder de forma remota a los servicios y aplicaciones desde el navegador, sin depender de instalar programas específicos en cada ordenador. Gracias a la combinación de ambas tecnologías conseguimos un entorno más estable, portable y fácil de administrar para todos los usuarios de la empresa.

## ¿Por qué elegimos esta solución y no conectar directamente por RDP a cada máquina?

Elegimos esta solución en lugar de conectarnos directamente por RDP a cada máquina porque Docker ofrece un entorno mucho más ligero, portátil y eficiente. A diferencia de las máquinas virtuales tradicionales, Docker no necesita instalar un sistema operativo completo dentro de otro, sino que utiliza directamente los recursos del sistema anfitrión. Esto reduce considerablemente el consumo de memoria, almacenamiento y procesamiento.

Gracias a esto, los equipos con menos recursos pueden trabajar de forma más fluida, evitando problemas de rendimiento como ralentizaciones, sobrecalentamientos o incluso apagados provocados por el exceso de carga al ejecutar varios sistemas operativos al mismo tiempo. Los contenedores se inician más rápido y requieren menos mantenimiento que una máquina virtual convencional.

Además, Docker facilita mucho la portabilidad y la administración del entorno. Un mismo contenedor puede ejecutarse en diferentes ordenadores manteniendo exactamente la misma configuración, lo que evita errores y ahorra tiempo en instalaciones o configuraciones manuales.

Otra ventaja importante es que dentro de un mismo contenedor podemos tener funcionando distintas herramientas y servicios relacionados, como un ERP y una base de datos conectada, permitiendo trabajar de manera más organizada y centralizada sin depender de múltiples conexiones RDP a diferentes equipos.
# titulo 2<a name="id2"></a>
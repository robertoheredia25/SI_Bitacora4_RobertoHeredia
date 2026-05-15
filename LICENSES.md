# Licencias del software utilizado en la infraestructura

A continuación, se detallan las licencias del software utilizado en la infraestructura definida mediante Docker Compose. Para cada componente se indica el nombre del software, el tipo de licencia y la fuente oficial.

---

# 1. Apache Guacamole

Apache Guacamole es una plataforma de acceso remoto sin cliente que permite conectarse a escritorios remotos mediante navegador web utilizando protocolos como RDP, VNC y SSH.

## Licencia
Apache Guacamole se distribuye bajo la **Apache License 2.0**.

Esta es una licencia de software libre y de código abierto de tipo permisivo. Permite usar, modificar y distribuir el software incluso con fines comerciales, siempre que se mantenga el aviso de copyright y la licencia original.

## Fuente oficial
- Sitio oficial: https://guacamole.apache.org/
- Licencia oficial: https://www.apache.org/licenses/LICENSE-2.0

---
# 2. OpenSSH

OpenSSH es una implementación libre del protocolo SSH utilizada para conexiones remotas seguras, administración de sistemas y transferencia cifrada de archivos.

En esta infraestructura se utiliza mediante la imagen Docker:

`linuxserver/openssh-server`

## Licencia
OpenSSH se distribuye principalmente bajo la **Licencia BSD**.

La licencia BSD es una licencia permisiva de software libre que permite reutilizar y modificar el código con muy pocas restricciones.

## Fuente oficial
- Sitio oficial: https://www.openssh.com/
- Información de licencia: https://www.openssh.com/licenses.html

---

# 3. Docker Compose

Docker Compose es una herramienta que permite definir y ejecutar aplicaciones multicontenedor mediante archivos YAML.

## Licencia
Docker Compose se distribuye bajo la **Apache License 2.0**.

Esta licencia permite el uso, modificación y distribución del software de forma libre, incluyendo usos comerciales.

## Fuente oficial
- Sitio oficial: https://docs.docker.com/compose/
- Licencia oficial: https://github.com/docker/compose/blob/main/LICENSE

---
# 4. Docker

Docker es una plataforma de virtualización ligera basada en contenedores que permite empaquetar aplicaciones y sus dependencias.

## Licencia
Docker Engine utiliza principalmente la **Apache License 2.0**.

Esta licencia open source permite usar, modificar y distribuir el software libremente.

## Fuente oficial
- Sitio oficial: https://www.docker.com/
- Licencia oficial: https://github.com/moby/moby/blob/master/LICENSE

---

# 5. Ubuntu XFCE

La imagen `linuxserver/webtop:ubuntu-xfce` utiliza Ubuntu junto con el entorno gráfico XFCE para proporcionar acceso remoto a un escritorio Linux.

## Licencia
Ubuntu y la mayoría de sus componentes se distribuyen bajo diferentes licencias de software libre, principalmente:

- GPL (GNU General Public License)
- LGPL
- MIT
- BSD

XFCE se distribuye bajo la **GPL**.

## Fuente oficial
- Ubuntu: https://ubuntu.com/
- Licencias Ubuntu: https://ubuntu.com/licensing
- XFCE: https://www.xfce.org/

---

# 6. LinuxServer.io Images

Las imágenes Docker utilizadas (`linuxserver/openssh-server` y `linuxserver/webtop`) son mantenidas por LinuxServer.io.

## Licencia
El contenido y scripts de las imágenes LinuxServer.io se distribuyen generalmente bajo la **GNU General Public License v3 (GPLv3)**.

## Fuente oficial
- Sitio oficial: https://www.linuxserver.io/
- GitHub oficial: https://github.com/linuxserver

---

# Conclusión

La infraestructura utilizada emplea principalmente software de código abierto con licencias permisivas como Apache 2.0 y BSD. Esto permite utilizar, modificar y distribuir el software legalmente, siempre respetando las condiciones específicas de cada licencia.


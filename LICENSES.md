# Licencias del software utilizado en la infraestructura

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

# 3. Docker

Docker es una plataforma de virtualización ligera basada en contenedores que permite empaquetar aplicaciones y sus dependencias.

## Licencia
Docker Engine utiliza principalmente la **Apache License 2.0**.

Esta licencia open source permite usar, modificar y distribuir el software libremente.

## Fuente oficial
- Sitio oficial: https://www.docker.com/
- Licencia oficial: https://github.com/moby/moby/blob/master/LICENSE

---

# 4. Ubuntu XFCE

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

# 5. LinuxServer

Las imágenes Docker utilizadas (`linuxserver/openssh-server` y `linuxserver/webtop`) son mantenidas por LinuxServer.io.

## Licencia
El contenido y scripts de las imágenes LinuxServer.io se distribuyen generalmente bajo la **GNU General Public License v3 (GPLv3)**.

## Fuente oficial
- Sitio oficial: https://www.linuxserver.io/
- GitHub oficial: https://github.com/linuxserver



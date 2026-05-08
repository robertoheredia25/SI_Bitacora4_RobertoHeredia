# Tarea 1: Despliegue de la Infraestructura
![IMAGEN1](FOTOS\IMAGEN1.png)

# SSH: Forjando la Llave Maestra

Paso A (Conexión Inicial): Conéctate al contenedor usando ssh alumno@localhost -p 2222. La contraseña es sistemas_informaticos.

En este caso nos sale un error entrando con @localhost entonces usamos la ip de local host 127.0.0.1

![IMAGEN2](FOTOS\IMAGEN2.png)

# Paso B (Generación de Identidad): En tu máquina anfitriona, generaremos un par de llaves: ssh-keygen -t ed25519 -C "tu_correo@ejemplo.com"

![IMAGEN3](FOTOS\IMAGEN3.png)

# Paso C (Transferencia): Copia tu llave pública al servidor. Puedes usar ssh-copy-id -p 2222 alumno@localhost o hacerlo manualmente pegando el contenido en ~/.ssh/authorized_keys dentro del contenedor.


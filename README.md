# Tarea 1: Despliegue de la Infraestructura
![IMAGEN1](FOTOS/IMAGEN1.png)

# SSH: Forjando la Llave Maestra

Paso A (Conexión Inicial): Conéctate al contenedor usando ssh alumno@localhost -p 2222. La contraseña es sistemas_informaticos.

En este caso nos sale un error entrando con @localhost entonces usamos la ip de local host 127.0.0.1

![IMAGEN2](FOTOS/IMAGEN2.png)

# Paso B (Generación de Identidad): En tu máquina anfitriona, generaremos un par de llaves: ssh-keygen -t ed25519 -C "tu_correo@ejemplo.com"

![IMAGEN3](FOTOS/IMAGEN3.png)

# Paso C (Transferencia): Copia tu llave pública al servidor. Puedes usar ssh-copy-id -p 2222 alumno@localhost o hacerlo manualmente pegando el contenido en ~/.ssh/authorized_keys dentro del contenedor.

Creamos la key para poder iniciar sesion sin contraseña con alumno para ello usaremos el comando de la siguiente imagen 

![IMAGEN4](FOTOS/IMAGEN4.png)

Y probamos que modemos iniciar sesion sin contraseña 
Este es el problema que tenemos:
El error de Escritorio Remoto 0x1104 ("Protocol Error at the Client") indica un fallo de compatibilidad o configuración en la conexión RDP [0x5.3]. Generalmente se soluciona desactivando estilos visuales en la experiencia de cliente, habilitando el acceso remoto o ajustando el firewall de Windows para permitir RDP en la máquina destino [0x5.1, 0x5.4].

![IMAGEN5](FOTOS/IMAGEN5.png)

# 3.2. RDP: El Escritorio en tu Navegador
Nos sale error al contectarnos por escritorio remoto 
![IMAGEN9](FOTOS/IMAGEN9.png)

Nos conectamos por localhost:3000 ya que por escritorio remoto no sale que ya tenemos a alguien conectado 

![IMAGEN6](FOTOS/IMAGEN6.png)

Creamos la prueba 

![IMAGEN7](FOTOS/IMAGEN7.png)

# Configuracion del sshd_config
![IMAGEN8](FOTOS/IMAGEN8.png)

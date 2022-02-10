
# Tarea 3, Grupo 4

| Carné         | Nombre                        |
| --------      | --------                      |
| 201513626     | Manuel Alejandro De Mata Mayen|
| 201800516     | Mynor Alison Isai Saban Che   |
| 201800722     | José Daniel Velásquez Orozco  |
| 201807316     | Jorge Isaac Xicol Vicente     |

## Configuración VPN en Google Cloud

## Conexión Ping y configuración del protocolo IP
1. Ingresar a la consola de la máquina virtual y crear una carpeta con el archivo **openvpn-install.ssh**
![](https://i.imgur.com/HrHfirj.png)

2. Crear el usuario a traves de la consola de la máquina virtual (esta acción se realizó por cada miembro del equipo).
![](https://i.imgur.com/OvJf7pg.png)
![](https://i.imgur.com/tvDATBU.png)

3. Obtener la direccion IP del usuario, dirigiendonos al directorio del archivo recien creado y ejecutando el comando **ip adress**.
 ![](https://i.imgur.com/vqLae5a.png)
 ![](https://i.imgur.com/333VLM6.png)

4. Se ejecuto el comando **ipconfig** en windows, obteniendo los siguientes datos del servicio VPN.
 ![](https://i.imgur.com/vUk2pfl.jpg)
 
5. Igualmente en la maquina virtual se ejecuto el comando **ifconfig** obteniendo el siguiente resultado.
![](https://i.imgur.com/DWFxdFU.png)


6. En una consola externa de la máquina local hacer ping a la dirección IP de la máquina virtual **ping 10.8.0.1** (Miembro 201800722 - José Daniel Velásquez Orozco).
![](https://i.imgur.com/4eaZ8gx.jpg)

### Comprobacion de conexión en las máquinas de los miembros restantes.
- Miembro 201513626 - Manuel Alejandro De Mata Mayen
![](https://i.imgur.com/rTFtu1M.jpg)
- Miembro 201807316 - Jorge Isaac Xicol Vicente
![](https://i.imgur.com/osZVENJ.png)
- Miembro 201800516 - Mynor Alison Isai Saban Che
![](https://i.imgur.com/3iEppkh.png)

 

## Configuración openVPN
Simplemente abrir el cliente, importar el archivo descargado y conectarse automáticamente
![](https://i.imgur.com/det8RgY.png)


  > Nota: Para que OVPN funcione adecuadamente, se desactivo el firewall de windows en las configuraciones del sistema.

## Integrantes del grupo IAM
![](https://i.imgur.com/qAJapHl.png)

## Creación y configuración de la instancia en Google Cloud
1. En esta seccion se nombra nuestra maquina, se coloca la regin donde se ubicara la maquina.
![](https://i.imgur.com/VpfVlw8.jpg)

2. Aqui se puede seleccionar el tipo de maquina que se requira, todo depende de cual sea nuestra necesidad, algo importante mencionar es importante elegir el tipo de maquina que se adapte al presupuesto.
![](https://i.imgur.com/rumP46P.jpg)

3. En la seccion de arraque, se puede seleccionar el tamaño de disco que tendra la maquina, tambien el tipo de sistema operativo que tendra.
![](https://i.imgur.com/Eb7baxF.jpg)

4. Se dan los permisos a la maquina, tambien se permiten los traficos de red los cuales estan ubicados en FIREWALL, estos siven para el acceso de la maquina desde internet. Se presiona el boton crear.
![](https://i.imgur.com/26FvvqA.jpg)

5.  Ya realizado los pasos anteriores, se genera nuestra maquina la cual esta ya esta lista segun nuestras configuraciones previas
![](https://i.imgur.com/KJJE8qD.jpg)

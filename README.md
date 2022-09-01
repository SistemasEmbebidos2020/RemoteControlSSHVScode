# RemoteControlSSHVScode

## En Visual Studio Code Instalar:
###### Remote - ssh
![image](https://user-images.githubusercontent.com/78398897/188000268-c2f19f4f-27ff-4753-a0ce-07acbbfd327f.png)
> En la parte de abajo izquierdo, hacer clic y seleccionar Conect to host
![2022-09-01 (2)](https://user-images.githubusercontent.com/78398897/188002038-676bcd41-da21-4a34-90ec-de986a3f0976.jpg)
 - colocar el usuario de su raspberry@direcciónIp por ejemplo:
 - pi@192.168.0.101

> Se abrirá una nueva ventana donde la primera vez se demorará para realizar correctamente la conexión
> ingresar la contraseña de su raspberry
![image](https://user-images.githubusercontent.com/78398897/188003287-1d9a8786-8a5b-4b05-9024-23ccf30627cd.png)

 - una vez establecida la conexión, en extensiones les asomará una segurencia de instalar una extensión en el raspberry

![2022-09-01 (3)](https://user-images.githubusercontent.com/78398897/188002538-aaec3d98-97cd-4704-ada6-0e1bf0e74c2d.jpg)

- instalarla y esperar hasta que se realice correctamente la conexión
 - si solicita un reload o reboot, hacerlo

> A continuació poner en abrir carpeta y ahí podrá seleccionar la carpeta de su raspberry que quiere acceder
![image](https://user-images.githubusercontent.com/78398897/188003724-9db34cf1-3f41-4d9e-b57d-1d714119e498.png)
- Yo accedo a home/pi
- Probablemente les solicite poner de nuevo la contraseña de su raspberry
![image](https://user-images.githubusercontent.com/78398897/188003795-36458748-595e-4702-a41b-de567a44573d.png)

> Al final colocar en un nuevo terminal dentro de VSCode el siguiente comando dando acceso 
> - a la carpeta que desee guardar los archivos donde programará
![2022-09-01 (8)](https://user-images.githubusercontent.com/78398897/188004071-8b68dbca-1de2-4f31-858c-e51ceba6de01.jpg)
 
 - sudo chown -R pi /home/pi/photos  donde photos es la carpeta que yo creé anteriormente
 ![image](https://user-images.githubusercontent.com/78398897/188002862-7f084e95-824e-4e20-b68d-1bb5e3422724.png)


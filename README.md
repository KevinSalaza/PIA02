# Sistema-Criptografico
Se desarrollará un programa que permita guardar información encriptada y firmada, de manera que se pueda identificar que usuario la almaceno por medio de certificados digitales.
## Información
- Materia: Criptografía
- Maestro: Alejandro Muniz Solorio
- Grupo: 063
- Nombre del Proyecto: Sistema-Criptografico
## Equipo
| Matricula | Alumno |
| --- | --- |
| 1827227 | K3vin Yair Peña Salzar |

## Instalación
Desde la carpte src que esta en repositorio.
```	
> virtualenv env
> cd .\env\Scripts\activate
> cd ..\..
> python -m pip install -r requirements.txt
```
## Ejecución
Ejecutar el script que se encuentra en la carpeta src del repositorio.

```	
> python main.py
```
```
 ____  _     _
/ ___|(_)___| |_ ___ _ __ ___   __ _
\___ \| / __| __/ _ \ '_ ` _ \ / _` |
 ___) | \__ \ ||  __/ | | | | | (_| |
|____/|_|___/\__\___|_| |_| |_|\__,_|

  ____      _       _                         __ _
 / ___|_ __(_)_ __ | |_ ___   __ _ _ __ __ _ / _(_) ___ ___
| |   | '__| | '_ \| __/ _ \ / _` | '__/ _` | |_| |/ __/ _ \
| |___| |  | | |_) | || (_) | (_| | | | (_| |  _| | (_| (_) |
 \____|_|  |_| .__/ \__\___/ \__, |_|  \__,_|_| |_|\___\___/
             |_|             |___/
[1] Login
[2] Registro
[3] Limpiar
[4] Salir
[*] Selecciona una opción >
```
## Registro
Primero, hay que crear un certificado, seleccionamos la opción 2 del menú.
```
[*] Selecciona una opción > 2
Ingresa el nombre del usuario > Kevin
Ingresa la contraseña > K3v1n123
Se registro el usuario Andres al sistema criptografico
Se genero el certificado y la llave privada
```
## Login
Después de crear un certificado, podemos iniciar sesión al seleccionar la opción 1 del menú.
```
[*] Selecciona una opción > 1
Certificado (.cer) > Kevin.cer
Clave privada (.key) > Kevin.key
Contraseña de la clave privada > K3v1n123
Bienvenido al sistema de mensajería!
```
## Sistema de Mensajeria
Al iniciar sesión correctamente, podemos cifrar y descifrar mensajes. 
```
 __  __                       _           _
|  \/  | ___ _ __  ___  __ _ (_) ___ _ __(_) __ _
| |\/| |/ _ \ '_ \/ __|/ _` || |/ _ \ '__| |/ _` |
| |  | |  __/ | | \__ \ (_| || |  __/ |  | | (_| |
|_|  |_|\___|_| |_|___/\__,_|/ |\___|_|  |_|\__,_|
                           |__/
[1] Cifrar mensaje
[2] Descifrar mensaje
[3] Cerrar sesión
[*] Selecciona una opción >
```
Seleccionamos la primera opción para escribir el mensaje.
```
[*] Selecciona una opción > 1
AVISO, Cifrado Cesar
Escribe tu mensaje > Mensaje Cifrado
Mensaje encriptado > Phqvdmh fliudgr
Apúntalo, se genero el archivo cifrado.txt
```
Ahora la opción 2, para descifrar el mensaje.
```
[*] Selecciona una opción > 2
Sugerencia: copia y pega abajo el mensaje encriptado
Ingresa el mensaje encriptado > Phqvdmh fliudgr
Mensaje desencriptado > Mensaje Cifrado
```
Al seleccionar la opción 3 volvemos al menú principal.
## Limpiar
Seleccionar la opción 3 para limpiar la consola o terminal.
```
[*] Selecciona una opción > 3
```
## Salir
Por último, seleccionar la opción 4 para salir.
```
[*] Selecciona una opción > 4
Hasta luego!
```

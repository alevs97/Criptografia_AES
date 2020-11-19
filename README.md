# Criptografia_AES
Biblioteca para el uso de AES en JavaScript

La biblioteca cuenta con el AES para sus tres versiones 128,192 y 256 bits para la llave.
Ademas de contar con el modo de operacion counter. CUenta con las siguientes caracteristicas.
Al igual que OFB, el modo contador convierte una unidad de cifrado por bloques en una unidad de flujo de cifrado. 
Genera el siguiente bloque en el flujo de claves cifrando valores sucesivos de un contador. 
El contador puede ser cualquier función sencilla que produzca una secuencia de números donde los resultados se repiten con muy baja frecuencia. 
Si bien la operación más usada es un contador, 
el modo CTR tiene características similares al OFB, pero permite también usar una propiedad de acceso aleatorio para el descifrado. 

Para correr la libreria y usar sus fucniones de cifrador y descifrador, se usan los siguientes comandos:
* ctr.encrypt(plaintext,password,n-bits)
* ctr.desencrypt(cyphertext,password,n-bits)

Donde:
plaintext.- Archivo de texto a encriptar.
cyphertext.- Archivo encriptado.
password.- la clave que se usara para codificar.
n-bits.- numero de bits de la clave(128,192 y 256)

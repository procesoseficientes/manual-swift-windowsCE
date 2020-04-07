# Manual Swift WindowsCE
Manual de implentación de Swift para Windows CE

Los detalles con capturas están en el pdf dentro de este repositorio.

## Restauración para MC67 y MC55
1. Abrir menu de inicio
2. Navegar al explorador de archivos
3. Navegar hacia la tarjeta SD
4. Copiar el contenido del archivo “Cleanboot”
5. Navegar hacia “My Device”.
6. Abrir el directorio “Temp”.
7. Pegar el contenido de “Cleanboot”.
8. **¡Este paso es importantisimo!**, conectar la Handheld a alguna fuente de poder.
9. Presionar una vez en el archivo “StartUpdLdr”.

## Configuración WiFI
1. En el menú de inicio abrir las configuraciones.
2. Dentro de las configuraciones entrar a “Connections”.
3. Entrar a WiFi.
4. En el primer campo seleccionar “Work”.
5. En el segundo seleccionar la tarjeta de WiFi, **el nombre de la tarjeta depende de cada modelo de HH**.
6. 	Presionar “Okay” en esa y en la siguiente pantalla
7.	Regresar a la pantalla de inicio
8. 	Seleccionar WiFi en el menú de inicio
9. 	Presionar el botón de “Fusion Manager” en la esquina inferior derecha
10. 	En el primer campo seleccionar “Regulatorio”
11. 	En el segundo campo el país en el que se esté usando la HH, en nuestro caso “Guatemala”
12. 	Deseleccionar el cheque
13. 	Guardar y presionar “Okay” a las siguiente pantallas

## Configurar Red
1. En “Fusion Manager” buscar WLAN
2. Crear perfil a la red que se desea conectar
3. Aceptar todos los pasos hasta que pregunté el tipo de seguridad. Ahí dejar el tipo de encriptación predeterminada.
4. Elegir “Pass-phrase”
5. Quitar cheque de enmascarar contraseña
6. 	Ingresar la contraseña
7. 	En el manejador de perfiles, mantener presionado el perfil a conectarse
8. 	Presionar en “Connect”
9. 	Esperar unos segundos y si se conecto con éxito en la pantalla de inicio deberá de salir el nombre de la red y la fuerza de la señal

## Instalar Aplicación
1. Navegar a “My Device”
2. Abrir “Program Files”
3. Pegar la carpeta ahí “swift3plmobile”
4. Abrir el ejectuble “Swift3PLMobile”

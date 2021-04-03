# REACT

# 1. INSTALAR VSCODE Y SUS PLUGINS PLUGIN RECOMENDADOS PARA REACT

ES7 React/Redux/GraphQL/React-Native snippets

Bracket Pair Colorizer

Material Icon Theme

Path Intellisense

Prettier Code Formatter, formatea el codigo al guardar (en el icono de configuracion parte inferior izqierda, luego setttings, en el buscador save y luego activar casilla editor format on save)

tema night owl

# 2. INSTALAR NODE.JS

Descargar node desde la web original https://nodejs.org/es/

Luego de instalado desde la terminal confirmar si quedó correctamente instalado, debemos escribir en la terminal  node -v y alli nos indicara la version que instalamos.

# 3. INSTALAR MANEJADOR DE DEPENDENCIAS YARN O NPM(NPM SE INSTALA AUTOMATICAMENTE CON NODE)  (https://yarnpkg.com/) https://yarnpkg.com/getting-started/install

Instalando yarn desde la terminal escribimos  npm install -g yarn 

Si sale algun error de permisos se debe forzsar la instalacion con  sudo npm install -g yarn --force

Para confiramr que quedó bien instalado escribimos en la terminal yarn -v

Para instalar un paquete con yarn se utiliza la siguiente sentencia  yarn  add nombredepaquete

Para instalar un paquete con npm se utiliza la siguiente sentencia  npm  install nombredepaquete

# 4. INSTALAR REACT NATIVE EXPO CLI

Entrear a la web https://reactnative.dev/  luego en get started, luego environment setup, Setting up the development environment.

En la pagina de Setting up the development environment debe aparecerla sentencia que se debe escribir en la terminal, npm install -g expo-cli

Para confiramr que quedó bien instalado escribimos en la terminal expo --version

Para probar que si esta funcionando bien creamos una nueva aplicacion, por ejemplo creamos un anueva carpeta en el escritorio,

En la terminal escribimos cd y arrastramos al carpeta a la terminal para tomar la direccion y presionamos enter

Luego escribimos al siguiente sentencia expo init nombredeaplicacion

Y nos debe aparecer el siguiente menu en donde podemos escoger con enter si queremos una app en blanco o con configuracion de typescript

Luego de escoger la opcion preferida, se empiezan a crear todos los fcheros necesarios

![image](https://user-images.githubusercontent.com/57473369/113483441-087fc400-9469-11eb-9603-42408fa89e25.png)


# 5. VIRTUALIZACION DE UN SISTEMA ANDROID

Se debe instalar Android Studio, luego de isntalado nos vamos a la opcion AVD MANAGER

Luego  CREATE VIRTUAL DEVICE

Se recomienda agregar una con una resolucion grande como PIXEL 3XL y uno con una resolucion pequeña como el NEXUS4
NEXT

LUEGO ESCOGER AL VERSION DEL ANDROID, SE RECOMIENDA ESCOGER LA VERSION ESTABLE 
NEXT

Luego un paso importante escoger un nombre apra el dispositivo virtual, es recomendable dejarle el que viene por defecto

Luego en Graphics si tu sabes que tienes una tarjeta d evideo escoge hardware si no escoge automatic

Finalizar

Listo para correrlo le das en el icono de play.

/CONFIGURAR PATH SDK

En el buscador de inicio de windows  buscar "Editar las variables del entorno de esta cuenta"

En la ventana que se abre hacer click en NUEVO, luego en nombre de la: ANDROID_HOME

En "Valor de la"  se debe poner la ruta de SDK (La ruta se encuentra en File - Settings es la ruta que sale en  ANDROID SDK LOCATION 

C:\Users\Mario_Andres\AppData\Local\Android\Sdk 

Luego aceptar y aceptar

# 6. CORRER LA APLICACION EN EL EMULADOR ANDROID

Luego de creada la aplicacion de prueba debemos apuntar en el terminal a la carpeta en donde se creo

Ej: cd C:\Users\mario\Desktop\TEST> 

Luego para correr la aplicacion en el emulador android escribimos la siguiente sentencia en la terminal:  yarn android


# 7. CORRER LA APLICACION EN EL EQUIPO FISICO

Instalar en el celular EXPO GO desde la play store, conectar elc elular al computador por usb

Luego de instalado corremos la aplicacion con yarn start

Se debe abrir una pagina web en donde debe aparecer  un codigo QR 

Leemos el codigo QR con el n celular y alli debe correr la aplicacion

Si sale un error diciendo que el dispositivo no esta autorizado simplemente se debe desconectar el celular del computador,

Luego entrar a las opciones de desarrollador y revocar  autorizaciones de depuracion usb

Luego volver a conectar el celular al computador y debe salir un mensaje pidiendo permisos para depuracion, se debe dar aceptar.


# 8. CUENTA DE EXPO Y PUBLICANDO APP PARA PRUEBAS

Primero sedebe crear una cuenta en la web https://expo.io/

En la terminal ya estando situados en la carpeta d ela aplicacion de prueba Ej: cd C:\Users\mario\Desktop\TEST> 

Hay 2 formas de plublicarla, atravez de un boton o atravez de la terminal

Para publicarla por boton: Ejecutamos la sentencia yarn start

![image](https://user-images.githubusercontent.com/57473369/113484564-9ca05a00-946e-11eb-9d38-779926890d2b.png)

Luego se debe abrir una pagina y hay que hacerle clicl al boton publish or republish project

![image](https://user-images.githubusercontent.com/57473369/113484629-ef7a1180-946e-11eb-8278-1090a519f7e2.png)


Para publicarla desde la terminal: Ejecutamos la sentencia para loguearnos en EXPO: expo login

![image](https://user-images.githubusercontent.com/57473369/113484706-5697c600-946f-11eb-9a1d-f6095b52481e.png)

Luego de estar logueado correctamente escribimos al siguiente sentencia: expo publish

Una vez termine de publicar debemos irnos ala web de https://expo.io/ loguearnos e irnos a la seccion de proyectos y hacerla publica en options

Una vez hecha publica abrimos en el celular Expo Go y alli nos debe aparecer la aplicacion, simplementer es escogerla y abirla


# 9. INSTALAR ROBO 3T PARA GESTIONAR LA BASE DE DATOS EN MONGO DB

Abrimos al web https://robomongo.org/ 

En la web nos vamos a Download y descargamos la version que dice Download Robo 3t Only, una vez descargada se instala.





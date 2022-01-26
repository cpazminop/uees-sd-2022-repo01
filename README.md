# uees-sd-2022-repo01
Implementación del modelo cliente-servidor 

CARACTERISTICAS DE LA INSTALACION

1. Se decargo el programa de Virtual Machine desde el servidor de www.oracle.com
2. Luego se instalo la maquina virtual en un entorno Windows 10
3. A continuacion se descarga la version de UBUNTU 20.6 desde el servidor de https://ubuntu.com/download/desktop
4. Se ejecuta virtual machine y se configura una nueva instancia para un sistema Ubuntu con las siguientes parametrizaciones para el sistema virtual:
	Memoria RAM sobre las 2GB
	Capacidad de almacenamiento de 20GB
	Capacidad de procesamiento de 2 Procesadores

5. Configuramos las opciones para Procesador, Memoria RAM, Espacio en Disco y se selecciona el archivo iso para que arranque la instalacion desde el dispoditivo optico
6. Luego de la configuracion basica de Ubuntu, ya dentro del sistema LINUX, descargamos el jdk 8 desde lal terminal a traves del siguiente comando
	sudo apt-get install oracle-java8-set-default
   	Haciendo que esta version sea la que se usara por defecto

7. Luego desde la pagina de netbeans descargamos la version para linux del IDE para Java
	https://netbeans.apache.org/download/nb126/nb126.html
	Se selecciona el archivo con extension sh.

8. Abrimos terminal desde la carpeta de descargas de UBUNTU y colocamos las siguientes instrucciones
	chmod +x nombredelarchivo.sh
	./nombredelarchivo.sh
	Se empieza a instalar el programa

9. La plataforma queda lista para utilizarse


CARACTERISTICAS ESPECIALES DEL SISTEMA

1. El programa consta de dos proyectos uno cliente y un servidor que se pueden ejecutar desde el entorno NETBEANS por separado
2. Para conocer el IP Adress de la maquina virtual Ubuntu utilizamos el comando en linea ifconfig, el cual de no estra presente en el sistema podemos instalarlo
3. Esta direccion es necesaria que sea configurada dentro del codigo del proyecto cliente con el objeto de configurar adeuadamente el funcionamiento del SOCKET creado para la comunicacion entre ambas partes
4. los JFrames generados representan una interface grafica que permite interactuar con el sistema generado.


COMPILACION DESDE SISTEMA LINUX

1. Dentro de las opcinones de cada proyecto podemos generar el CLEAN AND BUILD, lo que permite crear el archivo JAR en NETBEANS
2. Otra opcion seria abrir terminal en la carpeta del documento donde se ecnuentren los archivos JAVA y compilarlos con el comando javac
3. Ya desde la terminal de Linux, podemos ejecutar dicho archivo por medio del comando java


DERECHOS DE AUTORIA

1. La investigacion por intertnet siempre va a ser importante debido a la necesidad de ampliar conocimiento y desarrollar habilidades
2. La comprension del proyecto llevo a escuchar y verificar informacion que se encuentra en la Web desde diferentes fuentes
3. Algunas de ellas tenian que ver con temas como SOCKET, TCPIP, DATAFRAMES, CLIENTE SERVIDOR
4. estas son algunas de las direcciones utilizadas para la implementacion del presente sistema
	YOUTUBE
		https://www.youtube.com/watch?v=3wJTI9LMOsk
		https://www.youtube.com/watch?v=XN0J4rzj-NA
		https://www.youtube.com/watch?v=eEhHMg-In8o
	PAGINAS WEB
		http://www.jc-mouse.net/proyectos/ejemplo-socket-java-clienteservidor
		https://proyectoa.com/enviar-mensaje-de-un-cliente-a-un-servidor-por-socket-con-java-y-intellij-idea/
		http://codigoprogramacion.com/cursos/java/103-sockets-en-java-con-cliente-y-servidor.html#.YfFBnvi229I
5. Tambien se consulto sobre procesos de manejo de metodos Random, DataOutputStream, DataInputStream, ReadUTF, WriteUTF, ServerSocket, metotodos de generadion de numeros randomicos, manejo de objetos JAVA.

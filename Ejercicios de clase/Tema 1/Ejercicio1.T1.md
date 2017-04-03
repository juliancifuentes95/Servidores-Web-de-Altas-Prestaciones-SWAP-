# Ejercicio 1. Tema 1: Introducción. Servidores Web de Altas Prestaciones (SWAP)
## Buscar información sobre las tareas o servicios web para los que se usan los siguientes programas:                              
                                                                                                                                       
        * apache                                                                                                                        
		* nginx                                                                                                                        
		* thttpd                                                                                                                        
		* Cherokee                                                                                                                      
		* node.js 




—APACHE—

El servidor HTTP Apache es un servidor web HTTP de código abierto, para plataformas Unix, Microsoft Windows, Apple Macintosh y otras, que implementa el protocolo HTTP/1.12 y la noción de sitio virtual. Cuando comenzó su desarrollo en 1995 se basó inicialmente en código del popular NCSA HTTPd 1.3, pero más tarde fue reescrito por completo.

El servidor Apache es desarrollado y mantenido por una comunidad de usuarios bajo la supervisión de la Apache Software Foundation dentro del proyecto HTTP Server (httpd).

Apache presenta entre otras características altamente configurables, bases de datos de autenticación y negociado de contenido, pero fue criticado por la falta de una interfaz gráfica que ayude en su configuración.


Entre las principales características de Apache, se encuentran las siguientes:

    - Soporte de seguridad SSL y TLS.
    - Puede realizar autentificación de datos utilizando SGDB.
    - Puede dar soporte a diferentes lenguajes, como Perl, PHP, Python y tcl.




Fuentes:

[1] https://es.wikipedia.org/wiki/Servidor_HTTP_Apache
[2] http://culturacion.com/que-es-apache/










—NGINX—

NGINX es un servidor web HTTP de código abierto que también incluye servicios de correo electrónico con acceso al Internet Message Protocol (IMAP) y al servidor Post Office Protocol (POP). Además, NGINX está listo para ser utilizado como un proxy inverso. En este modo, NGINX se utiliza para equilibrar la carga entre los servidores back-end, o para proporcionar almacenamiento en caché para un servidor back-end lento.

Características básicas:

	- Servidor de archivos estáticos, índices y autoindexado.
	- Proxy inverso con opciones de caché.
	- Balanceo de carga.
	- Tolerancia a fallos.
	- Soporte de HTTP y HTTP2 sobre SSL.
	- Soporte para FastCGI con opciones de caché.
	- Servidores virtuales basados en nombre y/o en dirección IP.
	- Streaming de archivos FLV y MP4.14
	- Soporte para autenticación.
	- Compatible con IPv6
	- Soporte para protocolo SPDY
	- Compresión gzip.
	- Habilitado para soportar más de 10.000 conexiones simultáneas.15



Fuentes:

[1]https://blog.desdelinux.net/nginx-una-interesante-alternativa-a-apache/
[2]https://es.wikipedia.org/wiki/Nginx











—THTTPD—

THTTPD (tiny/turbo/throttling HTTP server) es un servidor web de código libre disponible para la mayoría de las variantes de Unix. Se caracteriza por ser simple, pequeño, portátil, rápido, y seguro, ya que utiliza los requerimientos mínimos de un servidor HTTP. Esto lo hace ideal para servir grandes volúmenes de información estática.



Caraterísticas:

	- Simple, porque esto maneja solo el mínimo necesario para poner en práctica el protocolo HTTP, algunas veces un poco más que el mínimo.
	- Pequeño, porque esto también tiene un pequeño tamaño de período de explotación, ya que esto no se divide en dos partes y es muy cuidadoso sobre la asignación de memoria.
	- Portátil, porque esto se compila limpiamente sobre la mayoría de sistemas operativos, expresamente incluyendo FreeBSD, SunOS 4, Solaris 2, BSD/OS, GNU/Linux, OSF.
	- Rápido, porque en el empleo típico es sobre todo más rápido que los mejores servidores "destacados" (Apache), y bajo la carga extrema es mucho más rápido.
	- Seguro, porque este se extiende a grandes longitudes para proteger el servidor Web contra ataques de otros sitios.

El uso apropiado de esta herramienta es obtener velocidad en la transferencia de archivos y reducción de gastos innecesarios para funciones que no son requeridas en el servidor, debido a tener solo la posibilidad de utilizar servidores estándar (Apache).

Este rasgo importante permite al administrador de servidor limitar la tasa de bit máxima para ciertos tipos de archivos transferidos, generando, una aplicación mucho más ligera y rápida.

La principal ventaja es que el administrador puede decidir restringir la transferencia de archivos de imagen JPEG a 20 kilobytes por segundo. Esto evita la saturación la conexión, de modo que el servidor pueda seguir siendo accesible bajo una carga de trabajo pesada, con la desventaja de que se reduce la velocidad de transferencia de los archivos. Los promedios de carga caen debido a la reducción de la transferencia gráfica gracias a thttpd.

Tiene una desventaja con respecto a Apache, ya que no podríamos obtener aplicaciones de un software estándar.


Fuentes:

[1]https://es.wikipedia.org/wiki/Thttpd










—CHEROKEE—

Cherokee es un servidor web multiplataforma. Su objetivo es ser rápido y completamente funcional, sin dejar de ser liviano comparado con otros servidores web. Está escrito completamente en C. Puede usarse como un sistema embebido y soporta complementos para aumentar sus funcionalidades. Es software libre, disponible bajo la Licencia Pública General de GNU.

Entre las principales características, podemos tener:

	- Soporta tecnologías como: FastCGI, SCGI, PHP, CGI, SSI, SSL/TLS.5
	- Soporta la configuración de servidores virtuales.
	- Permite la realización de redirecciones.
	- Permite su utilización como balanceador de carga.
	- Dispone de un panel de autenticación.


Fuentes:

[1]https://es.wikipedia.org/wiki/Cherokee_(servidor_web)










—NODEJS—

Concebido como un entorno de ejecución de JavaScript orientado a eventos asíncronos, Node está diseñado para construir aplicaciones en red escalables.

Esto contrasta con el modelo de concurrencia más común hoy en día, donde se usan hilos del Sistema Operativo. Las operaciones de redes basadas en hilos son relativamente ineficientes y son muy difíciles de usar. Además, los usuarios de Node están libres de preocupaciones sobre el bloqueo del proceso, ya que no existe. Casi ninguna función en Node realiza I/O directamente, así que el proceso nunca se bloquea. Debido a que no hay bloqueo es muy razonable desarrollar sistemas escalables en Node.

Node.js incorpora varios "módulos básicos" compilados en el propio binario, como por ejemplo el módulo de red, que proporciona una capa para programación de red asíncrona y otros módulos fundamentales, como por ejemplo Path, FileSystem, Buffer, Timers y el de propósito más general Stream. Es posible utilizar módulos desarrollados por terceros, ya sea como archivos ".node" precompilados, o como archivos en javascript plano. Los módulos Javascript se implementan siguiendo la especificación CommonJS para módulos, utilizando una variable de exportación para dar a estos scripts acceso a funciones y variables implementadas por los módulos.




Fuentes:

[1]https://nodejs.org/es/
[2]https://es.wikipedia.org/wiki/Node.js



				

# Ejercicio 3 Tema 5 SWAP
## Buscar información sobre características, disponibilidad para diversos SO, etc de herramientas para monitorizar las prestaciones de un servidor. Para empezar, podemos comenzar utilizando las clásicas de Linux: top, vmstat, netstat. 

La orden top se encarga de mostrar los procesos en Linux, o en este caso, en MacOS.

![imagentop](https://github.com/juliancifuentes95/Servidores-Web-de-Altas-Prestaciones-SWAP-/blob/master/Ejercicios%20de%20clase/Tema%205/Imágenes/top.png)

La orden netstat se encarga de mostrar por pantalla las diferentes conexiones establecidas así como las mascaras de conexión y las tablas de rutas.

![imagennetstat](https://github.com/juliancifuentes95/Servidores-Web-de-Altas-Prestaciones-SWAP-/blob/master/Ejercicios%20de%20clase/Tema%205/Imágenes/netstat.png)

La orden vmstat muestra las estadísticas de la memoria del sistema.

Otras posibles herramientas son: 

- ps: La herramienta ps toma una instantánea de un grupo selecto de procesos activos. Este grupo se limita, de forma predeterminada, a los procesos pertenecientes al usuario actual y que están asociados a la misma terminal. Puede proporcionar información más detallada sobre procesos que top, pero no es dinámica.

- sar: El SAR (Reportero de actividad del sistema) recolecta y reporta información sobre la actividad del sistema hasta el momento de hoy. La salida predeterminada cubre el uso de CPU de hoy en intervalos de 10 minutos desde el comienzo del día. Esta herramienta es una alternativa útil para intentar crear reportes periódicos sobre la actividad del sistema mediante top o herramientas similares.

A continuación se muestra la ejecución de   ps en la terminal de MacOS:

![imagenps](https://github.com/juliancifuentes95/Servidores-Web-de-Altas-Prestaciones-SWAP-/blob/master/Ejercicios%20de%20clase/Tema%205/Imágenes/ps.png)




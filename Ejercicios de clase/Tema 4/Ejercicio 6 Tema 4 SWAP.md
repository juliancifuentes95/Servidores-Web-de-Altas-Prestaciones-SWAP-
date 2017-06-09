# Ejercicio 6 Tema 4 SWAP
## Buscar información sobre los bloques de IP para los distintos países o continentes. Implementar en JavaScript o PHP la detección de la zona desde donde se conecta un usuario. 

He consultado la [página web](http://www.ripe.net 
) que viene en las transparencias del tema 4 de SWAP, en la que viene información sobre los bloques de IPs asignadas a la región que incluye Europa y África.

Como implementación, creo que valdría el siguiente fragmento de código, haciendo uso de PHP y AJAX, para obtener la IP de los usuarios que se conectan.

	// Usaremos la IP de un servidor de google como ejemplo
	var IP = '74.125.224.72';

	// La api de cors-anywhere espera como argument la URL de destino
	var CorsAnyWhereUrl = 'https://cors-anywhere.herokuapp.com/';

	// La URL de geoplugin que espera la 	IP de usuario
	var GeoPluginUrl =  "http://	www.geoplugin.net/json.gp?ip=";

	// Hacer llamada usando jQuery
	$.getJSON(CorsAnyWhereUrl + GeoPluginUrl + ip,function(response){
    console.log(response);
    
    // Hola visitante de "Pais"
    alert("Hola visitante de "+ response.geoplugin_countryName);
		});

	// o hacer llamada a geoplugin usando javascript plano
	var xhttp = new XMLHttpRequest();
	xhttp.onreadystatechange = function() {
    var respuesta = this.responseText;
    var response = JSON.parse(respuesta);
    
    if (this.readyState == 4 && this.status == 200) {
        alert("Hola visitante de "+ response.geoplugin_countryName);
    }
	};
	xhttp.open("GET", CorsAnyWhereUrl + 	GeoPluginUrl + ip , true);
	xhttp.send();



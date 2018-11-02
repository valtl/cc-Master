# Project de CC

## Descripción del problema

En mi coro se vende las entradas de la obra de una forma de lista a rayas que es muy propenso a errores. Hacer la cuenta no es fácil no si alguien quiere devolver una entrada. En el día de la obra se debe romper las entradas para verificar la validez por una única vez.

## Descripción del proyecto

Construir una aplicación web que permite hacer todo de forma digital. Por eso las entradas van a tener un código de barras para identificarlas. Eso se puede leer con un escanear que sea conectado con Bluetooth. La aplicación debe funcionar con computadores igual que móviles. Por el "frontend" voy a utilizar html, css y js y por el "backend" en un server de Apache PHP y MySQL pero igualmente unos microservicios sean en otros idiomas. Por la autirazion del acceso se va a utilizar .htaccess.
Estas cosas son las más importante:
- Interface del vendedor: Por eso se necesita un micro servicio que responde si la entrada escaneada ya es vendido y sí cuándo y por cuanto. Otro micro servicio que cambia la base de datos al respecto que de las entradas comprado y/o las devolviendo. 
- Interface de la gente q controla en la entrada: Por eso quiero desarrollar un micro servicio que busca en la base de datos si la entrada ya entró una vez y si sí por cual de las puertas entró. La respuesta sea que ya entro por esa puerta o que no entró y puede pasar.
- Otras funcionalidades voy a presentar luego.


## Licencia

Se va a aplicar la "GNU General Public License v3.0"

## Referencias

- [Coro en Alemania](http://www.unichor.de/?page_id=136)

## Pagina web

La pagina web con informaciones es [este]( https://valtl.github.io/cc-Master)

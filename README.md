# Networking

https://developer.mozilla.org/en-US/docs/Web/HTTP

Separación de enter entre el encabezado y el cuerpo

Pasos:
Creo un socket para escuchar en un puerto
Alguien quiere conectarse le doy el puerto
Creo un socket adicional para escribir/leer (bidireccional) - Viva para siempre hasta que alguien lo mate
Usa TCP porque siempre la deja abierta y HTTP la cierra

Nosotros vamos a crearlo sin hilos

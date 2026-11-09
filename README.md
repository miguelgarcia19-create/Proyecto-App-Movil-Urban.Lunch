NOMBRE DEL PROYECTO: App-Movil-Urban.Lunch
OBJETIVO DEL PROYECTO: Este proyecto se realizo para validar que los requisitos solicitados por el usuario dentro de la app funcionaran y se vieran de la manera correcta en varios dispositivos moviles.
QUE SE BUSCO CON ESTE PROYECTO: Validar que todo lo relacionado la funcionamiento y al diseño de la app estuviera aplicado de manera correcta en diferentes tipos de equipos móviles.
DOCUMENTACIÓN: Se trabajo con los requisitos solicitados por el usuario para la app Urban.Lunch
TECNOLOGÍAS UTILIZADAS: Android Studio,Android 9.0, Dispositivo Honor de 5.5" y resolución de 1080x1920
CASOS DE PRUEBA: Se realizaron los siguientes casos de prueba para la revisión de los requisitos:

	SELECCIÓN DEL PUNTO DE RECOGIDA
1	El mapa muestra los puntos de recogida de los pedidos.
2	Ninguno de los puntos de recogida,están seleccionados de forma predeterminada
3	Cuando tocas un punto de recogida se pone en color negro y se considera seleccionado.
4	Al dar click sobre un punto de recogida seleccionado,cancela la selección.
5	"Si hay un punto de recogida seleccionado y se da click
 en otro punto,se cambia el punto de recogida."
	ELECCIÓN DE PLATILLOS
6	La lista de platillos contiene el nombre de cada platillo.
7	La lista de platillos contiene los botones "+" y "-"
8	La lista de platillos contiene un contador de platillos.
9	La lista de platillos contiene una flecha al lado derecho del botón "+"
10	Si se da click en cualquier parte del listado,excepto en los botones "+" y "-"te muestra los detalles del platillo.
11	Al hacer click en el botón "+",el platillo se agrega a la lista de pedidos.
12	"Al hacer click en el botón ""-"",se elimina la selección 
del platillo en la lista de pedidos."
13	El progreso del pedido se muestra a pie de página
14	El primer paso del progreso se marca completo en color y el segundo paso se marca en curso.
15	La descripción del platillo consta de una fotografía del mismo,con su nombre en la parte superior.
16	La descripción del platillo muestra una descripción general del mismo.
17	La descripción del platillo muestra los ingredientes del mismo.
18	La descripción del platillo muestra el restaurante donde esta disponible y el precio.
19	 A la izquierda del nombre,aparece una flecha que al darle click regresa al listado de los platillos.
20	La descripción del platillo cuenta con los botones "+" y "-"
21	Al dar click en el botón "+",el platillo se agrega a la lista de pedidos.
22	Al dar click en el botón "-",se elimina la selección del platillo de la lista de pedidos.
23	El botón "siguiente" permanece inactivo si no hay platillos en la lista de pedidos.
	CONFIRMACIÓN DEL PEDIDO
24	La pantalla de confirmación del pedido,muestra el nombre del punto de recogida del platillo.
25	La pantalla de confirmación del pedido,muestra el listado de platillos pedidos.
26	La pantalla de confirmación del pedido muestra el importe total del pedido.
27	La pantalla de confirmación del pedido muestra el tiempo estimado de entrega el punto de recogida.
28	Al seleccionar el botón "Pedir",cambia la pantalla y muestra el tiempo estimado de entrega del pedido.
29	Si la lista del pedido es muy larga,se puede desplazarse entre la misma para ver todos los platillos.
30	El precio mostrado es el total de los platillos preparados y la entrega.
31	En el pie de página de la pantalla de confirmación,se ve el progreso del pedido.
32	Los 2 primeros pasos se marcan como completados y el tercer paso se marca en curso.
33	En la pantalla de confirmación,aparece el botón "Pedir"
34	Al dar click en el botón "Pedir",manda al usuario a la pantalla de seguimiento de pedidos.
35	PANTALLA DE SEGUIMIENTO DE PEDIDOS.(RECOGIDA DE PEDIDOS)
36	La pantalla de seguimiento muestra el punto en el que puedes recoger tu pedido.
37	La pantalla de seguimiento muestra los restaurantes en donde se prepararon los platillos.
38	La pantalla de seguimiento muestra las rutas desde los restaurantes hasta los puntos de recogida.
39	La pantalla de seguimiento muestra el tiempo de preparación restante de los platillos.
40	La pantalla de seguimiento muestra el costo total de los platillos pedidos.
41	La pantalla de seguimiento muestra el tiempo de entrega desde el restaurante hasta el punto de recogida.
42	Si hay muchos elementos en la lista de pedidos,nos podemos desplazar en la pantalla de arriba a abajo,para verlos todos.
43	La pantalla de seguimiento muestra un temporizador que muestra el tiempo que queda hasta que se recoje el pedido.
44	Cuando se entregan todos los pedidos,el temporizador se muestra en ceros.
45	Cuando el temporizador esté en ceros,se produce el cambio de pantalla a "El pedido ha sido enviado".
46	EL PEDIDO HA SIDO ENVIADO
47	"El cambio a la pantalla ""El pedido ha sido enviado"",se hace en automático al
 momento de que el temporizador se pone en ceros."
48	El mapa muestra el punto de recogida deseado.
49	En la pantalla "El pedido ha sido enviado" aparece el botón "Recibí el pedido".
50	Al dar click en el botón "Recibí el pedido",el pedido se considera completado.
51	Después de considerarse completado el pedido al dar click en el botón "Recibí el pedido"redirecciona al usuario a la página de Feedback.
52	Al momento de terminar el pedido,aparece mensaje "El pedido se ha enviado"
	Al dar click en "Recibí la orden",se redirecciona al Feedback.
53	Al finalizar el Feedback,se redirecciona al usuario a un punto de recogida para generar un nuevo pedido.

APRENDIZAJE: Con este proyecto, aprendí a trabajar en pruebas con dispositivos móviles y sus aplicaciones, así como reforzar mis conocimientos en la creación de casos de prueba y manejo de errores dentro de Jira.
54	Si no se da acceso a la geolocalización en la aplicación,debe aparecer un mensaje de error.
55	Si intentas hacer un pedido sin agregar platillos,aparece un mensaje de error.

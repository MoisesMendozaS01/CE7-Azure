# Wordpress (PaaS)
-------

Para crear una página Web desde 0 con el servicio de Azure simplemente buscamos el servico de Wordpress.

<img src="./images/image8.png" width=1000 align='center' border=5>


Seleccionamos el servicio y le damos en crear.
Esto nos creará varios recursos de azure!


<img src="./images/image9.png" width=1000 align='center' border=5>

Usamos la **suscripción** que nos a dado Azure (Azure para estudiantes) (Se pueden tener varias suscripciones).

Creamos un nuevo **grupo de recursos**. Lo llamare "Sesion2-practica1"

<img src="./images/image10.png" width=1000 align='center' border=5>

La **región** se elige dependiendo donde se encuentran tus usuarios, por que entre mas lejano esté la región mayor latencia tendrá.

De **nombre** le pondremos 'sesion2-practicaone'.

<img src="./images/image11.png" width=1000 align='center' border=5>

Tambien tenemos etiquetas, estas solos sirven para 3 cosas.
*   Sacar reportes de costos.
*   Cumplir normativas de seguridad.
*   Dar mas información a quien no sepa de Azure.

Por ejemplo nombre= importante, valor=critical
o nombre = Área, Valor = Ventas.

Damos a Revisar y crear

<img src="./images/image12.png" width=1000 align='center' border=5>

Detalles de creación, y damos en crear.

<img src="./images/image13.png" width=1000 align='center' border=5>

Este proceso puede tardar un poco, nos comienza a crear los diversos servicios que se utilizarán.

<img src="./images/image14.png" width=1000 align='center' border=5>

Una vez completada la implementacion podemos acceder al recurso.

<img src="./images/image15.png" width=1000 align='center' border=5>

Una vez dentro observamos el nombre de nuestro carpeta de recursos, tambien las opciones para detener el recurso, esto para evitar pagar por recursos que no se esten aprovechando.

En la parte inferior observamos las etiquetas y en la parte derecha podemos acceder al link de la página de Wordpress.

<img src="./images/image16.png" width=1000 align='center' border=5>

Podemos seleccionar el idioma de preferencia.

<img src="./images/image17.png" width=1000 align='center' border=5>

Agregamos los datos del administrador para crear la cuenta de Wordpress.

<img src="./images/image18.png" width=1000 align='center' border=5>

Y listo ya podemos acceder a nuestra pagina en Wordpress.

<img src="./images/image19.png" width=1000 align='center' border=5>

Accedemos con nuestro usuario.

<img src="./images/image20.png" width=1000 align='center' border=5>

Y observamos nuestra página, esta todavia se debe modificar a corde a las necesidades de cada uno, pero ya podemos encontrar esta página en internet y cualquiera puede acceder a ella.

<img src="./images/image21.png" width=1000 align='center' border=5>

REgresando al grupo de recursos, podemos observar que tenemos 3 servicios activos.

<img src="./images/image22.png" width=1000 align='center' border=5>

'Sesion2-practica1' es el grupo de recursos de Azure para la página de Azure, podemos observar que no esta ningun servicio llamado Wordpress, porque Wordpress es un software para hacer páginas que se monta sobre estos 3 servicios.
*   App service: es el servicio de Azure, para hacer páginas web y aplicaciones web.
*   Plan de app service: nos sirve para hacer mas grande este servicio, por ejemplo escalarlo verticalmente u horizontalmente.

<img src="./images/image23.png" width=1000 align='center' border=5>

*   Servicio unico de Azure database for MySQL, guarda información. (este servicio cobra) hay que apagar o eliminar este servicio si no se esta usando.

<img src="./images/image24.png" width=1000 align='center' border=5>

Una vez desactivados los servicios, ya no podemos acceder, esto es necesario cuando un recurso o servicio no se esta usando para evitar que continue cobrando por este servico y agote nuestro crédito

<img src="./images/image25.png" width=1000 align='center' border=5>
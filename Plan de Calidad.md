***Especificación de requisitos de software***

***Proyecto: Software para la gestión de delincuentes PONAL*** 
 
***CONTENIDO***
*FICHA DEL DOCUMENTO	
CONTENIDO*	

1	INTRODUCCIÓN														1.1	Propósito														
1.2	Alcance															
1.3	Personal involucrado													
1.4	Resumen															
2	DESCRIPCIÓN GENERAL													
2.1	Perspectiva del producto												
2.2	Funcionalidad del producto												
2.3	Características de los usuarios												
2.4	Restricciones														
2.5	Suposiciones y dependencias												
2.6	Evolución previsible del sistema											
3	REQUISITOS ESPECÍFICOS													
3.1	Requisitos comunes de los interfaces											
3.1.1	Interfaces de usuario													
3.1.2	Interfaces de hardware													
3.1.3	Interfaces de software													
3.1.4	Interfaces de comunicación												
3.2	Requisitos funcionales													
3.3	Requisitos no funcionales												
3.3.1	Requisitos de rendimiento												
3.3.2	Seguridad														
3.3.3	Fiabilidad														
3.3.4	Disponibilidad														
3.3.5	Mantenibilidad														
3.3.6	Portabilidad														

 
*1. Introducción*

Una de las problemáticas que más afecta a la sociedad Colombiana es la delincuencia, por lo que debería ser un tema en el que se pusiera bastante énfasis para reducirla lo más posible, lastimosamente no hay una herramienta que permita identificar a los delincuentes y no se entrega a la sociedad para conocer quiénes son las personas riesgosas en la comunidad. Es por eso que se propone el desarrollo de una plataforma en donde se recopile la información importante de los crímenes de dichas personas y también logrando que la comunidad realice sus denuncias a través de la recopilación de los eventos criminales, ya que a partir del avance tecnológico, se puede tener un registro de los crímenes y ser fácilmente reportados por medio de las tecnologías de información con las que se cuentan.

*1.1 Propósito*
- Desarrollar herramientas tecnológicas enfocadas a la resolución de problemas en la sociedad.
- Implementar los conceptos de Ingeniería de Software con toda la planeación correspondiente aprendida en el curso.
- Asignar roles a los implicados en el Desarrollo, dependiendo del perfil necesario.
- Diseñar una planificación profunda de cada operación necesaria en el desarrollo del Software.
- Realizar la entrega del Software según los estándares planteados.
- Implementar un servicio de control de Delincuentes para la grabación de delitos e implicados.


*1.2 Alcance*
Los alcances se determinarán mediante una estructura de descomposición de trabajo, cada componente tendrá su propio alcance, sin embargo, se determina como alcance general el despliegue de una plataforma web, para la gestión de delincuentes en Colombia.
Para los otros alcances, se descompone cada componente del objetivo del proyecto hasta lograr el punto en el que se llegue a lo particular de cada uno de los objetivos generales.


*1.3 Personal involucrado*

![PERSONAL](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rol1.png)
![PERSONAL](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rol2.png)
![PERSONAL](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rol3.png)
![PERSONAL](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rol4.png)
![PERSONAL](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rol5.png)
![PERSONAL](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rol6.png)
![PERSONAL](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rol7.png)


*1.4 Resumen*

El proyecto consiste en un aplicativo web en el cual el usuario podrá tener acceso a información de criminales registrados, cada uno tendrá información de sus delitos, su recompensa e información adicional que serán tomados por difusión de información de la comunidad.
Meta del proyecto:
Generar una plataforma acoplada a una base de datos que permita un soporte y facilidad a usuarios que inserten los datos requeridos y estimados que se tendrán en cuenta para los procesos. Así mismo como módulos vinculados a los administradores en los cuales podrán gestionar todos los datos y por cada uno de ellos, el sistema generará una base para el soporte de datos y respuestas.

*2. DESCRIPCIÓN GENERAL*

*2.1 Perspectiva del producto*

El sistema brindará soporte a una serie de administradores locales, en el ámbito de la gestión de datos y el manejo de las recompensas a contribuyentes de información. En el cual se manejara una base de datos donde los usuarios podrán subir sus denuncias y mediante un mediador se encargará de decidir si la información es verídica y realizará su respectiva publicación.

*2.2 Funcionalidad del producto*

- Establecer un sistema que acepte según las entradas de los usuarios la información insertada y almacenada. Logrando que el cliente pueda tener gestión a dicha información.
- Disponer de múltiples módulos de distintos tipos de información en la cual se los usuarios tendrán dichas opciones y facilidades con el producto para un mejor uso de la plataforma
- Procurar tener un sistema con una óptima capacidad de actualización y agilidad para que los usuarios tengan una experiencia agradable al momento de diligenciar, notificar y recibir nuevas informaciones.
- Optar por una base de datos confiable para almacenar la información brindada por todos los usuarios de la plataforma.
- Generar un sistema seguro contra ataques y perdidas de información.

*2.3 Características de los usuarios*

![CARACTERÍSTICAS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Carac1.PNG)
![CARACTERÍSTICAS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Carac2.PNG)
![CARACTERÍSTICAS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Carac3.PNG)

*2.4 Restricciones*

El sistema tendrá restricciones de sistemas operativos extraños y de navegadores en los que no tengan una fiabilidad con el sistema, por ejemplo: aplicaciones de navegador creadas por terceros y no sean garantizadas para el correcto funcionamiento del sistema. Todo ello para evitar fallas futuras. No presentaremos restricciones de hardware, únicamente de software.

*2.5 Suposiciones y dependencias*

El sistema será completamente independiente de alguno ya establecido por el usuario. Es completamente nuevo. En cuestión de nuevas modificaciones, adaptaciones, cambios y nuevas. Se determinará por realizar los respectivos cambios o actualizaciones en un tiempo establecido según la suposición. Ya que. Estas suelen ser inevitables y se determinará que el sistema no pierda fiabilidad ni reputación entre la comunidad de los usuarios.


*2.6 Evolución previsible del sistema*

El sistema se encuentra abierto a cambios y propuestas establecidas después de la entrega, se desarrollara con una facilidad de mantenimiento y de modificación, la cual permitirá, según el establecimiento de un nuevo contrato la correspondiente modificación y evolución de dicho sistema, todo ello por la observación de que nuestros sistemas evolucionan y son sujetos a cambios.

*3 REQUISITOS ESPECÍFICOS*

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq1.png)

Requerimiento para la creación de un administrador, para ello, ya debe haber sido generado desde el principio un administrador principal.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq2.PNG)

Requerimiento para la modificación de un administrador, para ello, ya debe haber sido generado desde el principio un administrador principal.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq3.PNG)

Requerimiento para la eliminación de un administrador, para ello, ya debe haber sido generado desde el principio un administrador principal. Para que de esta manera no quede el modulo sin una rama principal.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq4.PNG)

Requerimiento para la creación de un Moderador, para ello, el administrador es el único que puede realizar esto.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq5.PNG)

Requerimiento para la creación de un Moderador, para ello, el administrador es el único que puede realizar esto.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq6.PNG)

Requerimiento para la eliminación de un Moderador, para ello, el administrador es el único que puede realizar esto.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq7.PNG)

Requerimiento para la examinación y revisión de alerta ciudadana.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq8.PNG)

Requerimiento para la examinación y revisión del módulo de denuncias.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq9.PNG)

Requerimiento para la examinación, atención y revisión del CRUD de delincuentes.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq10.PNG)

Publicación de contenido en el módulo de alerta ciudadana, teniendo en cuenta la información validada de los usuarios.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq11.PNG)

Publicación de contenido en el módulo de denuncias, teniendo en cuenta la información validada de los usuarios.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq12.PNG) 
 
Publicación de contenido en el módulo del CRUD de delincuentes, teniendo en cuenta la información validada de los usuarios.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq13.PNG)

Publicación de contenido en el módulo de denuncias, teniendo en cuenta la información validada de los usuarios.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq14.PNG)

Creación del usuario según la solicitud del usuario, verificando correctamente los datos y generando una contraseña aleatoria.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq15.PNG)

Modificación de la información de un usuario normal, tomando en cuenta una solicitud y verificación por el usuario, Moderador y/o administrador.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq16.PNG)

Eliminación de la información de un usuario normal, tomando en cuenta una solicitud y verificación por el usuario, Moderador y/o administrador.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq17.PNG)

Envió de información por parte de un usuario sobre una denuncia a la alerta ciudadana, esta se validará por un mediador y/o Administrador.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq18.PNG)

Envió de información por parte de un usuario sobre una denuncia, esta se validará por un Moderador y/o Administrador.

![REQUISITOS](https://github.com/adrianga96/Gestion-CVVS/blob/master/Imagenes/Calidad/Rq19.PNG)

Envió de información por parte de un usuario sobre una actualización al CRUD de delincuentes, esta información se validará por un Moderador y/o Administrador.

*3.1 Requisitos comunes de los interfaces*

Entre los requisitos comunes tenemos en la mayoría de casos los CRUD de cada uno de los roles, en la cual nosotros tenemos diferencias notorias sobre la seguridad y los permisos que requieren cada uno de los roles, también de que cada rol tiene exclusividades de modificaciones, creaciones o eliminaciones. Otro requisito en común es el de la publicación de información, en la que cualquiera de los roles puede realizar esta correspondiente.

*3.1.1 Interfaces de usuario*

- Acceso al login para todos los roles
- Creación de cuenta para Usuario
- Modificación y Configuración de cuenta de usuario
- Creación de cuenta para Moderador
- Modificación y Configuración de cuenta de Moderador
- Creación de cuenta para Administrador
- Modificación y configuración de cuenta de Administrador
- Interfaz de vista de publicaciones en el módulo de alerta ciudadana.
- Interfaz de vista de publicaciones en el módulo de denuncias.
- Interfaz de vista de publicaciones en el módulo CRUD delincuentes.
- Interfaz de vista de saldos y recompensas.
- Interfaz de publicaciones en el módulo de alerta ciudadana.
- Interfaz de publicaciones en el módulo de denuncias.
- Interfaz de publicaciones en el módulo CRUD delincuentes.

*3.1.2 Interfaces de hardware*

Las interfaces de hardware variarán según el tipo de dispositivo que se use para acceder a la plataforma, depende también de su definición y tamaño del dispositivo, el sistema se ocupara de ajustar sus dimensiones al dispositivo, en los que comúnmente son PC, tabletas, Smartphone, Smart TV y demás medios comunes de comunicación.

*3.1.3 Interfaces de software*

Se tendría en cuenta una interfaz de software externa si por ejemplo lanzamos una app para celulares o computadores, requeriríamos una configuración extra y unos permisos adicionales con las interfaces de dichos medios.

*3.1.4	Interfaces de comunicación*

La comunicación regularmente la tendremos de manera web, con protocolos 802.3 y 802.11.

*3.2 Requisitos funcionales*

- Validación en cada uno de los medios de comunicación, ya sea CRUD para cada uno de los roles.
- Validación para entradas de información que se envía a los moderadores y/o a los administradores.
- Validación y comprobación de cuentas como por ejemplo al momento de enviar registros o recompensas.
- Generación de las correspondientes respuestas generadas por el sistema al momento de diligenciar cualquier registró.
- Generación de mensajes en cuestión de anomalía y en ese caso, entrar en un estado de mantenimiento temporal para que el sistema determine los errores y se corresponda a una solución los más rápida posible.
- Las conversiones de información deben ser almacenadas correctamente en la nube, la cual es requisito que siempre esté en funcionamiento
Conservar medidas de recuperación de información en cuestiones de fallas del sistema

*3.3	Requisitos no funcionales*

*3.3.1 Requisitos de rendimiento*

En el sistema se espera tener la mejor calidad para que el programa tenga una ejecución de respuesta inmediata, esto en los casos de login, inscripción, envió de información. Todo externo al sistema de respuestas el cual es prácticamente manual y será tomado como una ejecución en la que si se deliberara tiempo mientras se comprueba, esperamos que principalmente los envíos e intercambios de información tengan ese requisito primordial de rendimiento.

*3.3.2 Seguridad*

- El sistema corresponde a una base en la que se enviara y recibirá información muy importante, lo cual debe enviarse de una manera especial, con una seguridad más conformada y detallada. Esto puede tomarse como de manera de encriptación de la información y constar de que esta información no quede a la deriva en cuestiones de fallas.
- En cuestión del login de cada rol, el sistema estará preparado para determinar correctamente que tipo de usuario intenta ingresar al sistema y teniendo en cuenta el tipo de cuenta que este usuario conlleva en la base de datos, este realizara su correspondiente reenvió de información de rol y accederá de manera correcta.
- Cualquier usuario que se desconecte mientras esta en la sesión, será automáticamente sacado de la plataforma, esto para evitar que intenten irrumpir el sistema mientras esta desconectado provocando fallas y respuestas incorrectas como modificación de la información.

*3.3.3 Fiabilidad*

El sistema se diseñara a prueba de errores comunes, los cuales se han tenido en cuenta de proyectos anteriores, no obstante, siempre suelen aparecer nuevas y diferentes fallas, las cuales caerán en medida de modificación si se llegaran a presentar, aún no sabemos que nuevas anomalías puedan pasar, pero estaremos confiados de que el sistema tendrá la calidad de mediar correctamente de estas.

*3.3.4 Disponibilidad*

Esperamos ya tener el software en el menor tiempo estipulado a la fecha de la entrega, entendemos que el cliente requiere lo más pronto posible de este, pero la calidad de dicho software está ligado a cuando tiempo le empeñemos en determinar todos sus requisitos, esto es alrededor del 85% o 90% del tiempo estipulado.

*3.3.5 Mantenibilidad*

En las labores de mantenibilidad, determinamos que el software será libre a cambios estipulados, a mejoras o a correcciones de fallas que se presente durante el lanzamiento. También en brindar muchos análisis de comportamiento en marcha de dicho sistema para tener en cuenta en que debemos actuar y empeñarle más tiempo en la ejecución de los correspondientes mantenimientos.

*3.3.6 Portabilidad*

En cuestión de la portabilidad, los diseñamos primordialmente como una estructura, para que al momento de realizar adaptaciones o cambios drásticos, mantengamos el hilo que llevamos de dicho sistema, sin refundir requisitos y no saltarnos nada de ello, si el software requiere un cambio demasiado grande, es necesario analizar qué tipo de cambio para así, tomar la mayor cantidad de funcionalidades que ya teníamos para realizar los correspondientes cambios. Lo primordial es tener un software sujeto a cambios y a fácil portabilidad.


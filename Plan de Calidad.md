































Especificación de requisitos de software

Proyecto: Software para la gestión de delincuentes PONAL



















		

 
Contenido
FICHA DEL DOCUMENTO	3
CONTENIDO	4
1	INTRODUCCIÓN	6
1.1	Propósito	6
1.2	Alcance	6
1.3	Personal involucrado	6
1.4	Resumen	6
2	DESCRIPCIÓN GENERAL	7
2.1	Perspectiva del producto	7
2.2	Funcionalidad del producto	7
2.3	Características de los usuarios	7
2.4	Restricciones	7
2.5	Suposiciones y dependencias	7
2.6	Evolución previsible del sistema	7
3	REQUISITOS ESPECÍFICOS	7
3.1	Requisitos comunes de los interfaces	8
3.1.1	Interfaces de usuario	8
3.1.2	Interfaces de hardware	8
3.1.3	Interfaces de software	8
3.1.4	Interfaces de comunicación	8
3.2	Requisitos funcionales	8
3.2.1	Requisito funcional 1	9
3.2.2	Requisito funcional 2	9
3.2.3	Requisito funcional 3	9
3.2.4	Requisito funcional n	9
3.3	Requisitos no funcionales	9
3.3.1	Requisitos de rendimiento	9
3.3.2	Seguridad	9
3.3.3	Fiabilidad	9
3.3.4	Disponibilidad	9
3.3.5	Mantenibilidad	10
3.3.6	Portabilidad	10

 
1	Introducción

Una de las problemáticas que más afecta a la sociedad Colombiana es la delincuencia, por lo que debería ser un tema en el que se pusiera bastante énfasis para reducirla lo más posible, lastimosamente no hay una herramienta que permita identificar a los delincuentes y no se entrega a la sociedad para conocer quiénes son las personas riesgosas en la comunidad. Es por eso que se propone el desarrollo de una plataforma en donde se recopile la información importante de los crímenes de dichas personas y también logrando que la comunidad realice sus denuncias a través de la recopilación de los eventos criminales, ya que a partir del avance tecnológico, se puede tener un registro de los crímenes y ser fácilmente reportados por medio de las tecnologías de información con las que se cuentan.

1.1	Propósito
•	Desarrollar herramientas tecnológicas enfocadas a la resolución de problemas en la sociedad.
•	Implementar los conceptos de Ingeniería de Software con toda la planeación correspondiente aprendida en el curso.
•	Asignar roles a los implicados en el Desarrollo, dependiendo del perfil necesario.
•	Diseñar una planificación profunda de cada operación necesaria en el desarrollo del Software.
•	Realizar la entrega del Software según los estándares planteados.
•	Implementar un servicio de control de Delincuentes para la grabación de delitos e implicados.


1.2	Alcance
Los alcances se determinarán mediante una estructura de descomposición de trabajo, cada componente tendrá su propio alcance, sin embargo, se determina como alcance general el despliegue de una plataforma web, para la gestión de delincuentes en Colombia.
Para los otros alcances, se descompone cada componente del objetivo del proyecto hasta lograr el punto en el que se llegue a lo particular de cada uno de los objetivos generales.


1.3	Personal involucrado
Nombre	Carlos Fuentes
Rol	Director del proyecto
Categoría profesional	Ingeniero de sistemas
Responsabilidades	Dirección del proyecto, gestión de las decisiones y supervisor de cada uno de los requisitos del sistema, así como de que las funciones sean válidas y coordinadas correctamente para la entrega con el cliente.

Nombre	Daniel Camargo
Rol	Ingeniero de Automatización
Categoría profesional	Ingeniero de sistemas
Responsabilidades	Automatizar los procesos que involucren que el sistema presente despliegues en ambientes de pruebas y de producciones, así como la comunicación con los demás departamentos para ir modificando y avanzando las respectivas modificaciones en el proyecto.

Nombre	Brayan Vargas
Rol	Ingeniero DevOps
Categoría profesional	Ingeniero de sistemas
Responsabilidades	Analizar y determinar según los desarrollos de los demás departamentos y especialmente de las pruebas, los respectivos cambios y modificaciones innovando procesos y  modelando las respectivas mejoras.

Nombre	Jorge Aguilar
Rol	Ingeniero de software
Categoría profesional	Ingeniero de sistemas
Responsabilidades	Desarrollar principalmente los módulos administrativos y de CRUD para el proyecto. 

Nombre	Diego Muñoz
Rol	Desarrollador
Categoría profesional	Ingeniero de sistemas
Responsabilidades	Determinar según los requisitos del ingeniero de software, el proceso a desarrollar mediante la programación. El desarrollo de cada uno de los módulos establecidos para el proyecto.

Nombre	Adrián Garavito
Rol	Desarrollador
Categoría profesional	Ingeniero de sistemas
Responsabilidades	Determinar según los requisitos del ingeniero de software, el proceso a desarrollar mediante la programación. El desarrollo de cada uno de los módulos establecidos para el proyecto, como el Modulo de denuncias y el Modulo Alerta ciudadana.

Nombre	Cristian Bravo
Rol	Ingeniero QA
Categoría profesional	Ingeniero de sistemas
Responsabilidades	Determinar según los desarrollos del proyecto, para establecer un margen de errores y correcciones a realizar para la realización de un informe que se entregara al ingeniero DevOps y establecer la capacitación de la plataforma.

1.4	Resumen

El proyecto consiste en un aplicativo web en el cual el usuario podrá tener acceso a información de criminales registrados, cada uno tendrá información de sus delitos, su recompensa e información adicional que serán tomados por difusión de información de la comunidad.
Meta del proyecto:
Generar una plataforma acoplada a una base de datos que permita un soporte y facilidad a usuarios que inserten los datos requeridos y estimados que se tendrán en cuenta para los procesos. Así mismo como módulos vinculados a los administradores en los cuales podrán gestionar todos los datos y por cada uno de ellos, el sistema generará una base para el soporte de datos y respuestas.

2	Descripción general

2.1	Perspectiva del producto
El sistema brindará soporte a una serie de administradores locales, en el ámbito de la gestión de datos y el manejo de las recompensas a contribuyentes de información. En el cual se manejara una base de datos donde los usuarios podrán subir sus denuncias y mediante un mediador se encargará de decidir si la información es verídica y realizará su respectiva publicación.
2.2	Funcionalidad del producto

•	Establecer un sistema que acepte según las entradas de los usuarios la información insertada y almacenada. Logrando que el cliente pueda tener gestión a dicha información.
•	Disponer de múltiples módulos de distintos tipos de información en la cual se los usuarios tendrán dichas opciones y facilidades con el producto para un mejor uso de la plataforma
•	Procurar tener un sistema con una óptima capacidad de actualización y agilidad para que los usuarios tengan una experiencia agradable al momento de diligenciar, notificar y recibir nuevas informaciones.
•	Optar por una base de datos confiable para almacenar la información brindada por todos los usuarios de la plataforma.
•	Generar un sistema seguro contra ataques y perdidas de información.

2.3	Características de los usuarios

Tipo de usuario	Administradores
Formación	Profesional en gestión
Habilidades	Gestión, Administración y Supervisión.
Actividades	Gestionar los módulos y encargarse de cada uno de los módulos creados. Encargado del CRUD de los moderadores y también de los demás usuarios.

Tipo de usuario	Moderadores
Formación	Profesionales en cargos de monitorias
Habilidades	Monitorear, Actualizar, Comprobar.
Actividades	Comprobar la información de los usuarios y establecer soluciones para cada una de las entregas de datos para realizar su correspondiente respuesta. Estos pueden también tener constancia sobre las interacciones de los usuarios que ingresan en el modulo

Tipo de usuario	Usuario común
Formación	Cualquiera (debe registrarse seleccionando unos determinados campos de comprobación).
Habilidades	Notificar e informar
Actividades	Los usuarios del común tienen el deber de estar informando a los moderadores de las denuncias y demás. Esta solicitud de estos, debe ser gestionada y autorizada por el departamento para ser publicada en el módulo establecido. Así como el poder tener visión de las informaciones de nuevas denuncias y de realizar las correspondientes medidas.

2.4	Restricciones
El sistema tendrá restricciones de sistemas operativos extraños y de navegadores en los que no tengan una fiabilidad con el sistema, por ejemplo: aplicaciones de navegador creadas por terceros y no sean garantizadas para el correcto funcionamiento del sistema. Todo ello para evitar fallas futuras. No presentaremos restricciones de hardware, únicamente de software.
2.5	Suposiciones y dependencias

El sistema será completamente independiente de alguno ya establecido por el usuario. Es completamente nuevo. En cuestión de nuevas modificaciones, adaptaciones, cambios y nuevas. Se determinará por realizar los respectivos cambios o actualizaciones en un tiempo establecido según la suposición. Ya que. Estas suelen ser inevitables y se determinará que el sistema no pierda fiabilidad ni reputación entre la comunidad de los usuarios.



2.6	Evolución previsible del sistema
El sistema se encuentra abierto a cambios y propuestas establecidas después de la entrega, se desarrollara con una facilidad de mantenimiento y de modificación, la cual permitirá, según el establecimiento de un nuevo contrato la correspondiente modificación y evolución de dicho sistema, todo ello por la observación de que nuestros sistemas evolucionan y son sujetos a cambios.

3	Requisitos específicos

Número de requisito	1

Nombre de requisito	Crear Administrador
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Requerimiento para la creación de un administrador, para ello, ya debe haber sido generado desde el principio un administrador principal.



Número de requisito	2

Nombre de requisito	Modificar Administrador
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Requerimiento para la modificación de un administrador, para ello, ya debe haber sido generado desde el principio un administrador principal.



Número de requisito	3

Nombre de requisito	Eliminar Administrador
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Requerimiento para la eliminación de un administrador, para ello, ya debe haber sido generado desde el principio un administrador principal. Para que de esta manera no quede el modulo sin una rama principal.



Número de requisito	4

Nombre de requisito	Crear Moderador
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Requerimiento para la creación de un Moderador, para ello, el administrador es el único que puede realizar esto.



Número de requisito	5

Nombre de requisito	Crear Moderador
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Requerimiento para la creación de un Moderador, para ello, el administrador es el único que puede realizar esto.



Número de requisito	4

Nombre de requisito	Crear Moderador
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Requerimiento para la creación de un Moderador, para ello, el administrador es el único que puede realizar esto.



Número de requisito	5

Nombre de requisito	Modificar Moderador
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Requerimiento para la modificación de un mediador, para ello, el administrador es el único que puede realizar esto.


Número de requisito	6

Nombre de requisito	Eliminar Moderador
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Requerimiento para la eliminación de un Moderador, para ello, el administrador es el único que puede realizar esto.


Número de requisito	7

Nombre de requisito	Revisar Alerta Ciudadana
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador, Moderador
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Requerimiento para la examinación y revisión de alerta ciudadana.


Número de requisito	8

Nombre de requisito	Revisar Modulo Denuncias
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador, Moderador
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Requerimiento para la examinación y revisión del módulo de denuncias.


Número de requisito	9

Nombre de requisito	Revisar CRUD Delincuentes
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador, Moderador
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Requerimiento para la examinación, atención y revisión del CRUD de delincuentes.


Número de requisito	10

Nombre de requisito	Publicar en Alerta Ciudadana
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador, Moderador
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Publicación de contenido en el módulo de alerta ciudadana, teniendo en cuenta la información validada de los usuarios.


Número de requisito	11

Nombre de requisito	Publicar respuestas en Modulo de Denuncias
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador, Moderador
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Publicación de contenido en el módulo de denuncias, teniendo en cuenta la información validada de los usuarios.


Número de requisito	12

Nombre de requisito	Publicar información en el CRUD de delincuentes
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador, Moderador
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Publicación de contenido en el módulo del CRUD de delincuentes, teniendo en cuenta la información validada de los usuarios.

Número de requisito	13

Nombre de requisito	Publicar respuestas en Modulo de Denuncias
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador, Moderador
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Publicación de contenido en el módulo de denuncias, teniendo en cuenta la información validada de los usuarios.

Número de requisito	14

Nombre de requisito	Creación de Usuario normal
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador, Moderador
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Creación del usuario según la solicitud del usuario, verificando correctamente los datos y generando una contraseña aleatoria.

Número de requisito	15

Nombre de requisito	Modificación de Usuario normal
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador, Moderador, Usuario normal
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Modificación de la información de un usuario normal, tomando en cuenta una solicitud y verificación por el usuario, Moderador y/o administrador.

Número de requisito	16

Nombre de requisito	Eliminación de Usuario normal
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador, Moderador, Usuario normal
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Eliminación de la información de un usuario normal, tomando en cuenta una solicitud y verificación por el usuario, Moderador y/o administrador.

Número de requisito	17

Nombre de requisito	Subir denuncia en alerta ciudadana
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador, Moderador, Usuario normal
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Envió de información por parte de un usuario sobre una denuncia a la alerta ciudadana, esta se validará por un mediador y/o Administrador.

Número de requisito	18

Nombre de requisito	Subir denuncia módulo de denuncias
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador, Moderador, Usuario normal
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Envió de información por parte de un usuario sobre una denuncia, esta se validará por un Moderador y/o Administrador.

Número de requisito	19

Nombre de requisito	Subir información al CRUD de delincuentes
Tipo	X Requisito	0 Restricción

Fuente del requisito	Administrador, Moderador, Usuario normal
Prioridad del requisito	X Alta/Esencial	0 Media/Deseado
0 Baja/ Opcional


Envió de información por parte de un usuario sobre una actualización al CRUD de delincuentes, esta información se validará por un Moderador y/o Administrador.

3.1	Requisitos comunes de los interfaces

Entre los requisitos comunes tenemos en la mayoría de casos los CRUD de cada uno de los roles, en la cual nosotros tenemos diferencias notorias sobre la seguridad y los permisos que requieren cada uno de los roles, también de que cada rol tiene exclusividades de modificaciones, creaciones o eliminaciones. Otro requisito en común es el de la publicación de información, en la que cualquiera de los roles puede realizar esta correspondiente.
3.1.1	Interfaces de usuario

•	Acceso al login para todos los roles
•	Creación de cuenta para Usuario
•	Modificación y Configuración de cuenta de usuario
•	Creación de cuenta para Moderador
•	Modificación y Configuración de cuenta de Moderador
•	creación de cuenta para Administrador
•	Modificación y configuración de cuenta de Administrador
•	Interfaz de vista de publicaciones en el módulo de alerta ciudadana.
•	Interfaz de vista de publicaciones en el módulo de denuncias.
•	Interfaz de vista de publicaciones en el módulo CRUD delincuentes.
•	Interfaz de vista de saldos y recompensas.
•	Interfaz de publicaciones en el módulo de alerta ciudadana.
•	Interfaz de publicaciones en el módulo de denuncias.
•	Interfaz de publicaciones en el módulo CRUD delincuentes.

3.1.2	Interfaces de hardware

Las interfaces de hardware variarán según el tipo de dispositivo que se use para acceder a la plataforma, depende también de su definición y tamaño del dispositivo, el sistema se ocupara de ajustar sus dimensiones al dispositivo, en los que comúnmente son PC, tabletas, Smartphone, Smart TV y demás medios comunes de comunicación.

3.1.3	Interfaces de software

Se tendría en cuenta una interfaz de software externa si por ejemplo lanzamos una app para celulares o computadores, requeriríamos una configuración extra y unos permisos adicionales con las interfaces de dichos medios.
3.1.4	Interfaces de comunicación
La comunicación regularmente la tendremos en cuenta es por medio web, con protocolos 802.3 y 802.11.
3.2	Requisitos funcionales

•	Validación en cada uno de los medios de comunicación, ya sea CRUD para cada uno de los roles.
•	Validación para entradas de información que se envía a los moderadores y/o a los administradores.
•	Validación y comprobación de cuentas como por ejemplo al momento de enviar registros o recompensas.
•	Generación de las correspondientes respuestas generadas por el sistema al momento de diligenciar cualquier registró.
•	Generación de mensajes en cuestión de anomalía y en ese caso, entrar en un estado de mantenimiento temporal para que el sistema determine los errores y se corresponda a una solución los más rápida posible.
•	Las conversiones de información deben ser almacenadas correctamente en la nube, la cual es requisito que siempre esté en funcionamiento
•	Conservar medidas de recuperación de información en cuestiones de fallas del sistema
3.3	Requisitos no funcionales
3.3.1	Requisitos de rendimiento

En el sistema se espera tener la mejor calidad para que el programa tenga una ejecución de respuesta inmediata, esto en los casos de login, inscripción, envió de información. Todo externo al sistema de respuestas el cual es prácticamente manual y será tomado como una ejecución en la que si se deliberara tiempo mientras se comprueba, esperamos que principalmente los envíos e intercambios de información tengan ese requisito primordial de rendimiento.
3.3.2	Seguridad

•	El sistema corresponde a una base en la que se enviara y recibirá información muy importante, lo cual debe enviarse de una manera especial, con una seguridad más conformada y detallada. Esto puede tomarse como de manera de encriptación de la información y constar de que esta información no quede a la deriva en cuestiones de fallas.
•	En cuestión del login de cada rol, el sistema estará preparado para determinar correctamente que tipo de usuario intenta ingresar al sistema y teniendo en cuenta el tipo de cuenta que este usuario conlleva en la base de datos, este realizara su correspondiente reenvió de información de rol y accederá de manera correcta.
•	Cualquier usuario que se desconecte mientras esta en la sesión, será automáticamente sacado de la plataforma, esto para evitar que intenten irrumpir el sistema mientras esta desconectado provocando fallas y respuestas incorrectas como modificación de la información.
3.3.3	Fiabilidad

El sistema se diseñara a prueba de errores comunes, los cuales se han tenido en cuenta de proyectos anteriores, no obstante, siempre suelen aparecer nuevas y diferentes fallas, las cuales caerán en medida de modificación si se llegaran a presentar, aún no sabemos que nuevas anomalías puedan pasar, pero estaremos confiados de que el sistema tendrá la calidad de mediar correctamente de estas.
3.3.4	Disponibilidad

Esperamos ya tener el software en el menor tiempo estipulado a la fecha de la entrega, entendemos que el cliente requiere lo más pronto posible de este, pero la calidad de dicho software está ligado a cuando tiempo le empeñemos en determinar todos sus requisitos, esto es alrededor del 85% o 90% del tiempo estipulado.

3.3.5	Mantenibilidad

En las labores de mantenibilidad, determinamos que el software será libre a cambios estipulados, a mejoras o a correcciones de fallas que se presente durante el lanzamiento. También en brindar muchos análisis de comportamiento en marcha de dicho sistema para tener en cuenta en que debemos actuar y empeñarle más tiempo en la ejecución de los correspondientes mantenimientos.
3.3.6	Portabilidad

En cuestión de la portabilidad, los diseñamos primordialmente como una estructura, para que al momento de realizar adaptaciones o cambios drásticos, mantengamos el hilo que llevamos de dicho sistema, sin refundir requisitos y no saltarnos nada de ello, si el software requiere un cambio demasiado grande, es necesario analizar qué tipo de cambio para así, tomar la mayor cantidad de funcionalidades que ya teníamos para realizar los correspondientes cambios. Lo primordial es tener un software sujeto a cambios y a fácil portabilidad.


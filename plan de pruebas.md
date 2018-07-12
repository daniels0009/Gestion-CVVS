# Plan de Pruebas

### Historial de Versiones:

<table summary="versiones">
  <thead>
    <tr>
      <th scope="col">Fecha de entrega</th>
      <th scope="col">Versión</th>
      <th scope="col">Autor</th>    
</tr>
  </thead>
  <tbody>
    <tr>
      <td>12/07/2018</td>
      <td>1.0</td>
      <td>Daniel camargo</td>    
</tr>
  </tbody>
</table>

## Aprobaciones:
<table summary="Aprobaciones">
  <thead>
    <tr>
      <th scope="col">Nombre y Apellidos</th>
      <th scope="col">Cargo</th>          
</tr>
  </thead>
  <tbody>
    <tr>
      <td>Carlos fuentes</td>
      <td>Director</td>
    </tr>
  </tbody>
</table>

## Introduccion:

-	**proyecto:** software para la gestion de delincuentes y la denuncia de estos.
-	**tipo de proyecto:** proyecto socio tecnologico educativo.
-	**documentos relacionados:** plan de calidad
-	**Equipo de proyecto:** Jorge Aguilar Obregón 20132020020,
Cristian Alexander Bravo 20142020074,Daniel Camargo Pepinosa 20142020094,Carlos Fuentes Linares 20142020107,Rafael Adrián Garavito Tello 20132020051,Diego Alexander Muñoz Reyes 20131020078,Brayan Vargas Vargas 20132020054.
-	**Responsable del proyecto:** carlos fuentes.
-	**tutor:**  profesor e ingeniero alejandro daza

## Objetivos del plan de pruebas:

Este documento tiene como finalidad entregar los pasos a seguir para la aplicacion correcta de las estrategias y pruebas necesarias en el sistema presente . con el fin de verificar las funciones y procesos de los distintos modulos del software , asi como tambien encontrar los posibles fallos o errores que se presentan durante el periodo de pruebas. Ademas validar si el sistema cumple con los requerimientos que contemplen el funcionamiento total del mismo.

Las Fases en las que se realizan las pruebas son:

-	**Planificacion de las pruebas:** identificar los requisitos para las pruebas.Desarrollar la estrategia de pruebas. Identificar los recursos necesarios para realizar las pruebas y Generar el plan de pruebas
-	**Diseño de las pruebas:** Desarrollo de las pruebas identificar y describir los casos de prueba.
-	**Implementacion de las pruebas:** Establecer el entorno de prueba. Desarrollar las clases de prueba los componentes de prueba y los datos de prueba.
-	**Ejecuccion de las pruebas:** Ejecutar los casos de prueba. Evaluar la ejecucion del proceso de prueba. verificar los reusltados . investigar los resultados no esperados y registrar los defectos.
-	**Evaluacion de las pruebas:** Evaluar la cobertura de los casos de prueba. Evaluar la cobertura del codigo . Analizar los defectos . Determinar si se han alcanzado los criterios de las pruebas. crear los informes de evaluacion de las pruebas.


Los elementos de pruebas considerados, son aquellos componentes construidos en el sistema, que se presentan a continuación.

-	**Registro de usuario:** hace referencia a la gestión de registro, modificación, eliminación, autenticación y listado de los diferentes tipos de usuarios: visitante, empleado y recluso, además del administrador, quien se encarga de la gestión general.
-	**Solicitud de Denuncia:** este módulo se encarga de registrar las diferentes solicitudes de denuncia, además de su modificación, para actualización de estado (si es aceptada o no) o eliminación. El rol de empleado o administrador, tiene acceso al listado de las denuncias para hacer los cambios requeridos ,evaluar su aceptación y la seguridad del cliente .
-	**Verificación de requerimientos de  la denuncia:** este módulo tiene como función hacer contacto con la entidad de Registraduría para verificar la identidad de la persona como denunciante; se encarga de confirmar o no la veracidad de la información suministrada por la persona. 
-	**Agendamiento de un pago por la denuncia:** este módulo tiene como fin llevar a cabo un registro de las solicitudes de denuncias logradas y  aceptadas, de acuerdo a la disponibilidad existente y a las fechas de operativos  establecidas, relacionando a la policia  con el denunciado al que se desea apresar, para finalmente generar un pago.
-	**Vistas:** este módulo hace referencia a la creación de las diferentes interfaces gráficas de usuario por rol, así como los formularios de registro.

<table summary="Critarios de aprovacion o rechazo">
  <thead>
    <tr>
      <th scope="col">Criterio</th>
      <th scope="col">Descripcion</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Aprovado</td>
      <td>Se aprovara el proyecto con el 100% de las pruebas ejecutadas pero con el 90% de la aceptacion. Eso quiere decir que el 90% de las pruebas tienen que ser exitosas y sin errores. El 10% pueden tener errores medios y bajos pero no graves</td>
    </tr>
    <tr>
      <td>Rechazado</td>
      <td>En caso de ocurrir que elm proyecyo no cumpla con el nicel exigido, el proyecto se rechaza completo en su etapa de despliegue.</td>
    </tr>
      </tbody>
</table>



#### Criterios

-	**Errores graves:** Informacion critica presente erroneamente , informacion mal registrada en la base de datos ya que es la vida de una persona , caida de progrmas , incumplimiento con los objetivos en funciones principales .
-	**Errores medios:** presentacion , incumplimiento de objetivos en funciones secundarias y caida de programas auxiliares. 
-	**Errores leves:** Errores en presentacion de datos secundarios, no adecaucion a estandares de operacion.

<table summary="Resumen de las pruebas">
  <thead>
    <tr>
      <th scope="col">Tarea</th>
      <th scope="col">Descripcion</th>

    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Componentes a ser aprovados</td>
      <td>Modulo de registro,Modulo de registro de denuncia
,Modulo de eliminacion modificacion,Modulo de seguimiento.
</td>
    </tr>
    <tr>
      <td>objetivo de las pruebas</td>
      <td>En los modulos anteriores se relizaran las pruebas para validar:
verificar la conectividad ,Efecturar de manera correcta cada uno de los procesos,
Facil usabilidad para el usuario,Realizar de manera logica cada proceso.
</td>
    </tr>

    <tr>
      <td>Detalle del orden de ejecuccion de los componentes</td>
      <td> los modulos anteriores se deben ejecutar en forma independiente pero consecutivos en el orden siguiente:
-	**Registar usuario :** 
-	**Registrar denuncia:** .
-	**modificacion eliminacion y busqueda de esta denuncia:** . 
-	** Pago de esta denuncia:** .
</td>
    </tr>

    <tr>
      <td>Responsabilidad de la prueba</td>
      <td>Las pruebas son responsabilidad de Daniel camargo lider de pruebas del proyecto. 
</td>
    </tr>

      </tbody>
</table>



### Enfoque de Pruebas (Estrategia):

En las Tablas a continuación, se describen los diferentes enfoques de pruebas para el proyecto.

#### Pruebas de caja negra
<table summary="Caja negra">
  <tbody>
    <tr>
      <td>Objetivo</td>
      <td>Comportamiento de entrada/salida del sistema</td>
    </tr>
    <tr>
      <td>Descripción</td>
      <td>Se prueba que los datos que el usuario ingrese sean correctamente leídos, y así mismo, que lo que se obtenga de esos datos también sea correcto y significativo para el usuario.</td>
    </tr>
    <tr>
      <td>Técnicas</td>
      <td>Se probará cada uno de los componentes donde el usuario debe ingresar cualquier tipo de información.</td>
    </tr>
    <tr>
      <td>Entorno de prueba</td>
      <td>Se realizará en un dispositivo diferente en donde esta desplegado el entorno base.</td>
    </tr>
  </tbody>
</table>

#### Prebas de despliegue e instalación
<table summary="Despliegue e instalación">
  <tbody>
    <tr>
      <td>Objetivo</td>
      <td>Comprobar el comportamiento del sistema frente a los requisitos de hardware./td>
    </tr>
    <tr>
      <td>Descripción</td>
      <td>Se prueba que la aplicación quede correctamente instalada y se ejecute efectivamente en cualquier entorno.</td>
    </tr>
    <tr>
      <td>Técnicas</td>
      <td>Se instalará y ejecutará la información en los entornos establecidos</td>
    </tr>
    <tr>
      <td>Entorno de prueba</td>
      <td>Se realizará en otra maquina diferente en donde esta montado el proyacto y se comparan. 
.</td>
    </tr>
  </tbody>
</table>


#### Pruebas unitarias
<table summary="Unitarias">
  <tbody>
    <tr>
      <td>Objetivo</td>
      <td>Verificar el comportamiento aislado de cada una de las piezas del software./td>
    </tr>
    <tr>
      <td>Descripción</td>
      <td>Se prueba el correcto funcionamiento de cada uno de los componentes del sistema.</td>
    </tr>
    <tr>
      <td>Técnicas</td>
      <td>Se ejecutará un script de prueba por cada uno de los módulos que se desarrollaron en el software.</td>
    </tr>
    <tr>
      <td>Entorno de prueba</td>
      <td>Se realizará en una maquina distinta a donde esta montado el sistema nativamente.</td>
    </tr>
  </tbody>
</table>

#### Pruebas de integración
<table summary="Integración">
  <tbody>
    <tr>
      <td>Objetivo</td>
      <td>Verificar la interacción entre componentes del sistema de software./td>
    </tr>
    <tr>
      <td>Descripción</td>
      <td>Se prueba la comunicación y capacidad de interacción entre los módulos del sistema.</td>
    </tr>
    <tr>
      <td>Técnicas</td>
      <td>Se ejecutará un script de prueba por cada una de las relaciones existentes entre diferentes componentes del sistema.</td>
    </tr>
    <tr>
      <td>Entorno de prueba</td>
      <td>Se realizará en otra maquina y no donde esta nativo el proyecto y se comparan.</td>
    </tr>
  </tbody>
</table>

#### Pruebas de sistema 
<table summary="Sistema">
  <tbody>
    <tr>
      <td>Objetivo</td>
      <td>Verificar el comportamiento del sistema en su conjunto./td>
    </tr>
    <tr>
      <td>Descripción</td>
      <td>Se prueba el sistema en general, comprobando los requerimientos no funcionales del sistema, como lo son seguridad, velocidad, fiabilidad, etc.</td>
    </tr>
    <tr>
      <td>Técnicas</td>
      <td>Se ejecutará un script para probar: comunicación entre componentes o sistemas, utilidades, entorno operativo, interfaces externas, etc.</td>
    </tr>
    <tr>
      <td>Entorno de prueba</td>
      <td>Se realizará en otra maquina y no donde esta nativamente el proyecto y se comparan.</td>
    </tr>
  </tbody>
</table>


### Criterios de Suspensión:

Serán criterios de suspensión del plan de pruebas los siguientes:

-	Enfermedad grave que afecte al equipo de pruebas.
-	Daños en el hardware donde se ejecutan las pruebas.
-	Daños en el sistema operativo y software necesario para las pruebas.
-	Ocurrencia de desastres naturales.
-	Calamidades domésticas o de fuerza mayor del equipo de pruebas.
-	Ocurrencia de un error de gravedad contemplado en la fase de diseño del producto.

### Criterios de Reanudación:
Se reanudará el plan de pruebas bajo los siguientes criterios:

-	Cuando la persona enferma vuelva a estar en condiciones óptimas para realizar la prueba.
-	Cuando el hardware donde se ejecutan las pruebas haya sido reparado.
-	Cuando los daños en el sistema operativo o el software hayan sido corregidos, o en caso contrario un formateo y reinstalación del software se haya efectuado.
-	Cuando el entorno de trabajo sea seguro para operar las pruebas.
-	Cuando el miembro del equipo haya resuelto sus calamidades domésticas y esté en condiciones de realizar las pruebas.
-	Cuando el error de gravedad en el diseño se haya corregido y se hayan hecho los ajustes pertinentes.

## Recursos:

### Requerimientos de Entornos – Hardware :

-	Computadora de mano con Intel Core i7 8770k, 4GB ram DDR4, SSD 1TB.
-	Explorador. 

### Requerimientos de Entornos – Software  :

-	Sistema operativo Windows 10.
-	Navegador Google Chrome, Firefox, Microsoft Edge, Opera, Safari.
-	Angular JS.
-	Php.
-	Html.


### Herramientas de Pruebas Requeridas:

Durante las pruebas se utilizarán las siguientes herramientas de pruebas:

-	DevOps: metodología de desarrollo ágil orientada a la automatización de la integración y pruebas.
-	Selenium: Herramienta para la automatización de pruebas de aplicativos web
-	Jenkins: Herramienta para la automatización de la integración y despliegue de la aplicación.
-	Docker: Herramienta para el montaje del entorno de pruebas.

### Personal:

-	Un (1) Ingeniero DevOps:  Coordina las actividades dentro de la metodología ágil
-	Un (1) Administrador del plan de pruebas: Coordina que el plan de pruebas se lleve a cabo correctamente y hacer la planeación del mismo
-	Dos (2) Aseguradores de calidad: Verifican que el software esté realizado conforme a los estándares de calidad
-	Dos (2) Especialistas en automatización de pruebas: Encargados de generar los scripts de automatización para las pruebas y ejecutar las mismas.
-	Cinco (5) Testers: Encargados de probar el sistema como si fueran usuarios de la aplicación.

### Entrenamiento:

Para poder llevar a cabo el plan de pruebas es necesario realizar capacitaciones en:
-	Metodología DevOps.
-	Uso de la plataforma Caron.
-	Uso de Selenium.
-	Uso de Jenkins.
-	Uso de Docker.


### Dependencias y Riesgos: 

-	Disponibilidad de recursos: se puede presentar ausencia de algún miembro del equipo por enfermedad, accidente, emergencias familiares, y demás situaciones. Como es un riesgo que no puede evitarse, se dispone que el resto del equipo asumirá las tareas del miembro faltante en la división que más convenga de acuerdo a las actividades ya establecidas.
-	Restricciones de tiempo: el tiempo para desarrollar el proyecto puede no ser suficiente, o parecer no suficiente; es por ello que se establece un cronograma donde se considerar holguras, y entregables por hitos. En caso de seguir presentando falta de tiempo, se debe comunicar al cliente las fallas y las soluciones propuestas. 
-	Premisas que no resultan ciertas: la premisa del tiempo y del recurso humano tienen relación con los dos riestos expuestos anteriormente; además, si se presentara que no existe disponibilidad de las herramientas establecidad, o se debe hacer un cambio, los miembros del equipo ya han sido preparados para el uso de otras herramientas que se estudiaron previamente y se eligieron como respaldo.


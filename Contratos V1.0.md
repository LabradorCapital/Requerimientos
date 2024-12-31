# ALCANCE 

## Funciones generales de la herramienta de contratos para la Versión 1.0:
### Capturar datos de una persona que fue seleccionada en el proceso de reclutamiento de apoderados y resguardar la información en el sistema.
### Guardar información de los apoderados y mostrar la ficha técnica del aspirante y ficha informativa del apoderado con la información definida por el área comercial y habilitar el modo edición para actualizar los datos del apoderado en la base de datos.
### Desplegar el formato definido de contratos (aspirante y provisional, primer año, consolidado) con la información precargada en la base de datos de apoderados.
### Guardar los datos capturados previamente, así como los cambios de tipo de contrato y generar los estatus de aspirante, numero de provisional, primer año y consolidado.
### Generar listado de contratos por vencer por día, semana, mes. (Vista calendario).
### Identificar de forma automática el formato por tipo de contrato con los datos revisados y capturados previamente, para poder generar el contrato correspondiente con ayuda del sistema.


# DOCUMENTACIÓN 

# # **Existen diferentes tipos de contratos para agentes**=
## `aspirante y provisional`
## `primer año`
## `consolidado `
## `Anexo coach`

### El área comercial inicia con el proceso de reclutamiento y selección de apoderados, en el cual al seleccionar a una persona en este proceso, el primer paso es recabar los datos generales para el primer registro. (datos generales, Ver en sección de Requerimientos) 
### Contrato de aspirante: Se firma por 3 meses, para los agentes de nuevo ingreso, con la finalidad de que los agentes realicen los exámenes y trámites de obtención de su cédula.
### Contrato provisional: se genera una vez finalizado el contrato de aspirante (3 meses); es  una excepción del proceso de contratos de agentes, de acuerdo al tema relativo a la obtención de la cédula de apoderados.
### ## Formato de  Contrato de Aspirante: 
El formato establecido para el contrato de aspirante y que debe ser precargado en el sistema es:
[https://docs.google.com/document/d/1797yUZTIdLMEAibQtejoCgtQ9XkL3jSf/edit](https://docs.google.com/document/d/1797yUZTIdLMEAibQtejoCgtQ9XkL3jSf/edit)

## Los documentos que se solicitan para conformar el **Expediente de Agentes** son:
### INE vigente
### Comprobante de domicilio 
### Constancia de estudios Bachillerato 
### Resultados de la prueba BUO
### constancia de situación fiscal 


### Contrato de primer año: Se firma para aquellos agentes que ya cuentan con cédula digital, pero por ser de nuevo ingreso se encuentran en programa de financiamiento.
regla: el tiempo de financiamiento es únicamente por 15 meses.
los 15 meses serán el resultado de sumar las vigencias de los contratos de aspirante, provisional y primer año.
El contrato de primer año se firma al término del contrato de aspirante por 3 meses o en su caso al término de un provisional.
El contrato de primer año no podrá exceder de 12 meses.
El formato establecido para el contrato de primer año y que debe ser precargado en el sistema es:
https://docs.google.com/document/d/1mdIPJxoypOFF3xepMDS7B5eRlNPKKaqA/edit
[https://docs.google.com/document/d/1mdIPJxoypOFF3xepMDS7B5eRlNPKKaqA/edit](https://docs.google.com/document/d/1mdIPJxoypOFF3xepMDS7B5eRlNPKKaqA/edit)

### Convenio de terminación: se firma con cada contrato (aspirante, 1er año, provisional o consolidado) y deberá establecer la fecha de fin.


### Contrato consolidado: Este Contrato se firma al término del contrato de primer año, y su vigencia nunca excederá de la vigencia de la cédula de Apoderado expedida por la Comisión Nacional de Seguros y Fianzas=3 AÑOS.
El formato establecido para el contrato de "consolidado" que debe ser precargado en el sistema es:
[https://drive.google.com/drive/u/0/folders/1DYJekzVraIgSIo2HPuHd7DtJz_XvkeHh](https://drive.google.com/drive/u/0/folders/1DYJekzVraIgSIo2HPuHd7DtJz_XvkeHh)
Para los apoderados de contrato consolidado se deberá realizar una evaluación periódica definida por la dirección comercial y con base a dicha evaluación se genera un contrato con vigencia definida por el área comercial; 

## Contrato de Terminación al contrato de Primer año: Se firma con el Contrato de Primer año y deberá establecer la fecha de fin de dicho documento.
## Contrato de Terminación al contrato consolidado: Se firma con el Contrato de Primer año y deberá establecer la fecha de fin de dicho documento.
El formato establecido para el contrato de terminación que debe ser precargado en el sistema es:
https://docs.google.com/document/d/1lGOdlDUQ4oBV-25Pv-cQ4xVJhffQDQoM/edit#heading=h.gjdgxs
[https://docs.google.com/document/d/1lGOdlDUQ4oBV-25Pv-cQ4xVJhffQDQoM/edit#heading=h.gjdgxs](https://docs.google.com/document/d/1lGOdlDUQ4oBV-25Pv-cQ4xVJhffQDQoM/edit#heading=h.gjdgxs)

## Anexo de Coach: Cuando el área comercial haga la solicitud de cambiar un apoderado consolidado a estatus de COACH el responsable de la elaboración de Contratos deberá citar al apoderado para la firma de éste documento en cuál constan los pagos de las comisiones por éste concepto.
El formato establecido para el anexo coach, que debe ser precargado en el sistema es:
[https://docs.google.com/document/d/1GDdIVYuI9yV1JmM99JPFEDo5Q8uNLgZk/edit?usp=drive_link&ouid=106317758571399911125&rtpof=true&sd=true](https://docs.google.com/document/d/1GDdIVYuI9yV1JmM99JPFEDo5Q8uNLgZk/edit?usp=drive_link&ouid=106317758571399911125&rtpof=true&sd=true)

## De manera general para el proceso de emisión de contratos:
### 1.-Realizar captura inicial de información de la persona reclutada.
### 2.-Revisar la información de la documentación entregada por el aspirante y modificar en caso de ser necesario..
### 3.-Para generar el contrato de aspirante se debe mostrar el formato de contrato de aspirante con los datos del agente capturados previamente. 
### 4. Se deberá generar la información de vencimientos del mes y calendarizar las firmas de los contratos de forma mensual.
### 5.- Para el caso de vencimientos de contratos se deberá identificar el tipo de contrato que se va a generar (aspirante, provisional, primer año, consolidado) 
### 6.- Para el caso de generar un contrato de aspirante se deberá generar una `FICHA TÉCNICA DEL ASPIRANTE `en la cual se pueda revisar la información general del reclutado.
### 7.- Para el caso de generar un contrato apoderado de 1er año y consolidado se deberá revisar la `FICHA INFORMATIVA DEL APODERADO` en la cual se podrá revisar la información general y la información de ventas.
### 8.- La información mostrada en la ficha técnica del aspirante y la ficha informativa del apoderado deberá ser revisada por el área comercial y el director general para dar el VoBo. del ingreso del aspirante para firma del contrato.
### 9.- Una vez que se haya revisado y autorizado la contratación del apoderado en el esquema correspondiente, entonces se deberá imprimir y programar la firma del apoderado. 
### 10.- la información del tipo de esquema de contratación que se firma, deberá ser registrado y guardado en el sistema para poder continuar con el proceso de generación de contratos.


# REQUERIMIENTOS DEL SISTEMA 

## El sistema despliega campos de captura para la persona reclutada:
## **Datos generales de la persona reclutada** 
`Nombre completo`
`Promotoría`
`tipo de aspirante: ingreso o reingreso`
`edad`
`estado civil`
`Folio INE`
`RFC` 
`Dirección Fiscal `
`domicilio particular `
`dependientes económicos= #`
`teléfono de contacto `
`correo electrónico`
`grado académico`
`fecha de registro`
## Datos de cédula (si es que cuenta con los datos) dato de cédula vigente (si tiene cédula se captura folio y vigencias) 
Nota: estos campos serán capturados de acuerdo al proceso de obtención de cédula de apoderados, por el usuario administrador. 
`número de cédula de apoderado de seguros `
`ramos acreditados por la CNSF`
`tipo de cédula`
`vigencia inicial`
`vigencia final `
`fecha examen`

### Una vez que se tiene el registro completo de la persona reclutada, el sistema deberá guardar la información en la base de datos de apoderados del sistema.
### Con cada solicitud de ingreso o reclutamiento de apoderados, el sistema deberá mostrar la información de la persona en **FICHA TÉCNICA DEL ASPIRANTE** (extraer datos de la base de datos de apoderados) 
### Con cada solicitud para generar un **contrato de aspirante**, el sistema deberá mostrar el formato establecido para el contrato de aspirante con los datos extraídos de la base de datos de apoderados, generando el contrato de aspirante para impresión y firma.
`Nombre completo`
`RFC con homoclave`
`dirección de constancia fiscal = calle, numero ext, numero int, delegación o municipio, ciudad, código postal `
`fecha (al día de la firma)`
`folio INE vigente`
`leyenda de aspirante o Número de provisional`
 
### El sistema deberá guardar el registro de los contratos de aspirantes con la información previamente capturada,
### El contrato provisional es el mismo formato que el contrato de aspirante para este caso una vez terminado el periodo del contrato de aspirante de 3 meses deberá identificar y asignar el primer contrato provisional y los subsecuentes de manera consecutiva.
### El sistema deberá enviar una notificación del vencimiento del contrato 1 mes antes (30 días antes) de acuerdo a la fecha de vigencia del contrato.
ejemplo: fecha de firma del contrato de aspirante con vigencia de 3 meses=30 junio 2024, entonces el sistema deberá realizar la notificación de vencimiento en el mes de agosto de 2024, dando aviso  al usuario del próximo vencimiento el día 30 de agosto de 2024, con el objetivo de que el usuario de contratos pueda gestionar las autorizaciones y programar la firma de los nuevos contratos antes del vencimiento.  
## El sistema debe mostrar al usuario todos los **CONTRATOS POR VENCER** al mes próximo, podría ser generada en forma calendario y mostrar  de forma mensual y por día los contratos que se vencen indicados (tipo calendar de google) vista calendario ver archivo:

[https://docs.google.com/spreadsheets/d/1VVcZRnnzmR7kOcqNAuet1wxIfKu-hjLH/edit?usp=drive_link&ouid=106317758571399911125&rtpof=true&sd=true](https://docs.google.com/spreadsheets/d/1VVcZRnnzmR7kOcqNAuet1wxIfKu-hjLH/edit?usp=drive_link&ouid=106317758571399911125&rtpof=true&sd=true)

Datos de contratos por vencer ver archivo: [https://docs.google.com/spreadsheets/d/1n46ygfNTBNRkLHJNLDDlctDRbe-TQ2oJ/edit?gid=928495608#gid=928495608](https://docs.google.com/spreadsheets/d/1n46ygfNTBNRkLHJNLDDlctDRbe-TQ2oJ/edit?gid=928495608#gid=928495608) deberá mostrar la información por tipo de contrato.

## El sistema debe mostrar la información de **## CONTRATOS POR VENCER **  con los datos:
`promotoría, clave de agente, nombre del apoderado, tipo de contrato vigente, fecha de vencimiento, ventas ultimo contrato, venta total, no tomadas, canceladas, sustituciones, total de contraindicadores,` 

## Contrato de Primer Año: 

Con cada solicitud para generar un **contrato de primer año**, el sistema deberá mostrar el formato establecido para el contrato de primer año, los datos que el sistema debe extraer de la base de datos de apoderados para personalizar el contrato son: 
`leyenda o título= 1er año`
`Nombre completo`
`número de cédula` dato por actualizar en la base de datos de apoderados (el usuario en este momento deberá actualizar en la base de datos)
`tipo de cédula` dato por actualizar en la base de datos de apoderados (el usuario en este momento deberá actualizar en la base de datos)
`ramos acreditados por la CNSF` dato por actualizar en la base de datos de apoderados (el usuario en este momento deberá actualizar en la base de datos)
`domicilio convencional `precargado
`correo electrónico `precargado
`RFC con homoclave` precargado
tipo de contrato= precargado primer año
`Lugar y fecha de firma` precargado
`vigencia del contrato` campo abierto de captura en el formato de contrato
`nombre del apoderado` precargado

### El sistema deberá guardar la información del registro de cambio de contrato de aspirante o provisional a primer año. 
### El usuario agenda cita con el apoderado para firma del contrato de primer año y digitaliza el contrato recién firmado; El sistema deberá guardar en el ## "Expediente Digital de Agentes" el contrato generado de primer año con vigencia, identificando los datos y documentos del apoderado anteriormente registrados en el sistema.
### El sistema deberá contar con la opción de Buscar a un apoderado con su número de clave y deberá mostrar el estatus actual como agente de primer año.

### El sistema deberá dar la opción de ## Editar datos## cuando se realiza una consulta en la base de datos de apoderados, con el perfil definido con permiso para modificar datos.




## Contrato Consolidado: 
### El sistema deberá mostrar la información de "FICHA INFORMATIVA DE APODERADO"   sirve al usuario del área comercial para visualizar la información del apoderado

Cada vez que se tiene la solicitud de generar un ** Contrato consolidado**, el sistema deberá mostrar el formato establecido para el contrato de consolidado ver formato de contrato consolidado: 
[https://docs.google.com/document/d/1F8P1_hGhcgsOQ_SEYoyvWjFzuztgjuxz/edit?usp=drive_link&ouid=106317758571399911125&rtpof=true&sd=true](https://docs.google.com/document/d/1F8P1_hGhcgsOQ_SEYoyvWjFzuztgjuxz/edit?usp=drive_link&ouid=106317758571399911125&rtpof=true&sd=true)

los datos que el sistema deberá extraer de la base de datos del apoderado son:

`nombre del agente` `número de cédula` `vigencia de la cédula` 
`vigencia del contrato` campo abierto de captura 
 `ramos acreditas por la CNSF`
 `domicilio convencional`
 `correo electrónico` `telefono` `RFC`  
`Fecha de firma` como aparece en el formato 
`nombre del apoderado` como aparece en el formato

## El sistema deberá guardar la información del registro de cambio de contrato de primer año a consolidado 
## El sistema deberá guardar en el ## "Expediente Digital de Apoderados" el contrato generado de consolidado con fecha de vigencia  que no podrá exceder la vigencia de la cédula de agente. 
## El sistema deberá generar un calendario en el cual el usuario pueda agendar las citas mensualmente para firma de contrato de acuerdo las fechas de vigencia y próximos vencimientos. Ver archivo Calendario vencimientos.
## El sistema deberá generar el "Expediente Digital de Agentes" el cual esta compuesto por:
`Check list de documentos del agente` 
[https://docs.google.com/document/d/1_l3_ix5yPW3_pYc8ZumG8E5b5nTKpnTQ/edit](https://docs.google.com/document/d/1_l3_ix5yPW3_pYc8ZumG8E5b5nTKpnTQ/edit)
`Ficha Informativa del apoderado `
`Contrato de agente `(contratos anteriores y contrato actual que se firma)
## El sistema debe generar la función para poder adjuntar los documentos escaneados al Expediente Digital de Apoderados

## El sistema deberá guardar la información de registro del nuevo contrato del apoderado y actualizar el estatus de acuerdo al tipo de contrato generado y firmado con la nueva vigencia establecida. 
### los estatus de acuerdo al tipo de contrato firmado pueden ser:
`Estatus: Aspirante Número de contrato provisional firmado.(2,3,4,5,6)`
`Estatus: Primer año `
`Estatus: Consolidado`
`estatus=coach`
El sistema deberá enviar una notificación vía correo electrónico a las áreas de Contabilidad, Legal, Dirección General, Administración, Operaciones informando: 
alta de contrato de aspirantes
alta de contrato de primer año
alta de contrato consolidado 
alta de anexo coach
la notificación deberá informar:
aspirante tipo, activación de clave de agente, designación coach, nombre y la promotoría 
provisional, numero, vigencia de 3 messes, clave, y nombre
consolidado. cambio de 1er año a comisiones, promotoria, clave y nombre, obtención de cédula digital
extension de consolidado, promotoria, clave, nombre y leyenda de extensión 
primer año, 
`tipo de contrato` `nombre del agente`  `clave de agente` `vigencia del contrato` `promotoría`  `estatus y número de la cédula`

El sistema deberá generar la **FICHA INFORMATIVA DE APODERADO** con los datos.
`nombre Apoderado` `promotoría ` ` clave del agente` `Fecha de ingreso`  `tipo de contrato vigente ` `vigencia del contrato` `prima emitida de riesgo ultimo contrato` `prima emitida de riesgo total`` tipo y folio de cédula` `coach` 
### la "FICHA INFORMATIVA DE APODERADO" sirve al usuario de área comercial para visualizar la información del agente y tomar una decisión en cuanto a la autorización de la generación y firma de su próximo tipo de contrato.

La autorización del cambio de tipo de contrato deberá ser responsabilidad del área Comercial y la dirección General, tomando en cuenta la **_FICHA INFORMATIVA DEL APODERADO_**

# PERFILES DEL SISTEMA

## Los perfiles que se requieren generar son: 
### Perfil Administrador de agentes: Realiza el proceso de alta, baja y modificaciones de los contratos de agentes 
### Perfil área comercial y Legal: Consulta Información de la base de datos de agentes. 
### Perfil Dirección General y Dirección Comercial: Autorización de altas, bajas y modificaciones. 

# REGLAS DE OPERACION 

### regla: el sistema solo podrá generar un único convenio de terminación para cada tipo de contrato generado.
### regla: el tiempo de financiamiento es únicamente por 15 meses, los 15 meses serán el resultado de sumar las vigencias de los contratos de aspirante, provisional y primer año. Pendiente validar regla Legal con DG.
### Las vigencias de los contratos no pueden ser mayores a las vigencias de las cédulas de apoderados.
### las modificaciones realizadas en la base de datos de apoderados, solo puede realizarlas el usuario administrador y por lo mismo el usuario deberá ser responsable de la información generada o modificada en dicha base.
### el proceso de evaluación de apoderados (comercial, DG y administración de apoderados)  deberá realizarse la última semana de cada mes, por lo que el sistema deberá ser capaz de generar las `Fichas Informativas de los apoderados` y los calendarios de contratos de vencimientos en  ese mismo periodo del mes;
el sistema deberá extraer los vencimientos del mes futuro y generar las fichas 1 semana antes. 



<a name="br1"></a> 

**3.1.1.2 Gestión de defectos mayores**

FOR-01 -> Enfoque en la identiﬁcación temprana de defectos graves. Permite

abordar problemas críticos de manera prioritaria.

FOR-02 -> Colaboración con un especialista externo (Satair Group) para abordar y

solucionar problemas en componentes con defectos graves. Aprovechamiento de la

experiencia y recursos especializados de Satair Group.

FOR-03 -> Realización de pruebas en tierra y vuelos de prueba para evaluar el

rendimiento de las aeronaves después de las reparaciones. Asegura la funcionalidad

y seguridad de los componentes reparados en situaciones de vuelo real.

FOR-04 -> Certiﬁcación ﬁnal que valida y documenta la conclusión exitosa del

proceso de mantenimiento. Proporciona una capa adicional de garantía y

credibilidad al proceso de mantenimiento.

**3.1.2.2 Debilidades**

DEB-01 -> Dependencia de la disponibilidad y capacidad de Satair Group para

abordar y reparar defectos graves.

DEB-02 -> Posibilidad de demoras en la resolución de problemas debido a factores

externos.

DEB-03 -> Las pruebas en tierra y los vuelos de prueba pueden ser procesos

complejos y costosos.

DEB-04 -> Requieren recursos adicionales y coordinación precisa.

DEB-05 -> El proceso de certiﬁcación puede enfrentar desafíos, especialmente si no

se cumplen todos los requisitos.

DEB-06 -> Puede haber presiones para certiﬁcar aeronaves incluso con reparaciones

cuestionables.

DEB-07 -> La certiﬁcación y documentación ﬁnal deben ser rigurosas y detalladas.

DEB-08 -> Puede haber riesgos si la documentación no reﬂeja con precisión el

estado real de las reparaciones.



<a name="br2"></a> 

**3.2.2.1 Descripción de Actores de Negocio Actuales**

Actores de Negocio Actuales:

-Cliente o Usuário inicial

Galvatec:

-Equipo de Mantenimiento

Satair Group:

-Reparación de Componentes

-Pruebas en tierra

-Pilotos de prueba

-Certificación y Registro

**En Galvatec:**

Actor-001: Cliente o Usuario Inicial

● *Descripción:* Cliente que inicia el proceso de mantenimiento al programar y

coordinar las actividades de reparación de piezas de aeronaves.

● *Comentario:* Rol esencial para la iniciación del proceso, proporcionando la

información inicial necesaria.

Actor-002: Equipo de Mantenimiento

● *Descripción:* Personal de Galvatec encargado de recopilar la información del

cliente, realizar inspecciones iniciales y llevar a cabo el mantenimiento de las

piezas de aeronaves.

● *Comentario:* Rol central en la ejecución y supervisión de las actividades de

mantenimiento.

**En Satair Group:**

Actor-003: Reparación de Componentes

● *Descripción:* Equipo especializado en Satair Group que se encarga de la

reparación de componentes de aeronaves, especialmente aquellos con

defectos graves.

● *Comentario:* Rol crítico para abordar y solucionar problemas en componentes

con defectos graves.



<a name="br3"></a> 

Actor-004: Pruebas en Tierra

● *Descripción:* Realiza pruebas en tierra para asegurar que los componentes

reparados funcionen correctamente antes de los vuelos de prueba.

● *Comentario:* Contribuye a garantizar la funcionalidad y seguridad de los

componentes reparados antes de los vuelos.

Actor-005: Pilotos de Prueba

● *Descripción:* Realizan vuelos de prueba para evaluar el rendimiento de las

aeronaves después de las reparaciones.

● *Comentario:* Rol clave para evaluar la efectividad de las reparaciones en

situaciones de vuelo real.

Actor-006: Certiﬁcación y Registro

● *Descripción:* Certiﬁca que la aeronave está en condiciones de vuelo y registra

las actividades de mantenimiento que ha tenido.

● *Comentario:* Rol ﬁnal que valida y documenta la conclusión exitosa del

proceso de mantenimiento.



<a name="br4"></a> 

**3.2.2 Descripción de procesos de negocio actuales**

El proceso de mantenimiento de piezas de aviones en Galvatec S.L. implica una serie de

pasos que comienzan con la programación del mantenimiento por parte del cliente, seguido

de la inspección inicial por el equipo de Galvatec. Aquí se verifican defectos graves y

menores. Los defectos graves se notifica a Satair Group para su reparación, seguido por

pruebas en tierra y vuelos de prueba, y finalmente la certificación y registro de las

actividades realizadas. Todo el proceso se documenta y se registra en un archivo Excel.

Actualmente, este proceso presenta algunas desventajas:

**Dependencia de Excel**: El uso extensivo de Excel para registrar y gestionar la información

puede resultar en limitaciones, como la dificultad para realizar un seguimiento preciso de los

cambios, la posibilidad de errores humanos en la entrada de datos y la falta de accesibilidad

en tiempo real para todas las partes involucradas.

**Coordinación y Comunicación**: La comunicación entre las diferentes entidades

involucradas (Galvatec, Satair Group, Satair Group) puede ser un desafío. La optimización

en la coordinación y la agilidad en la resolución de defectos y reparaciones podrían no ser

óptimas, lo que puede ralentizar el proceso y generar retrasos innecesarios.



<a name="br5"></a> 

**Proceso Manual**: La mayor parte del proceso depende de acciones manuales y puede ser

propenso a errores, lo que podría impactar la eficiencia general del mantenimiento.

Para optimizar este proceso, se sugiere implementar un sistema de gestión dedicado que

permita una mejor coordinación, comunicación y seguimiento de todo el proceso. Este

sistema podría mejorar la eficiencia al proporcionar una plataforma centralizada para

registrar, monitorear y compartir información entre las partes involucradas. Además, la

automatización de ciertas tareas y la integración de sistemas podrían reducir errores

humanos y agilizar los procedimientos de mantenimiento.



<a name="br6"></a> 

**4.2.2 Modelos de procesos de negocio a implantar**

**4.2.2.1 Descripción de actores de negocio a implantar**

Los actores de negocio a implantar

-Cliente o Usuario inicial

Galvatec:

-Equipo de reparación

-Mecánicos y técnicos de Mantenimiento

Satair Group:

-Gestores de reparación

-Suministro de repuestos

-Reparación de componentes

-Inspector final

-Gestor de pruebas

-Piloto de prueba

-Certificador

**En Galvatec:**

Act-007: Cliente o Usuario Inicial

● *Descripción:* Cliente que inicia el proceso de mantenimiento al programar y

coordinar las actividades de reparación de piezas de aeronaves.

● *Comentario:* Rol clave para la iniciación del proceso, proporcionando la

información necesaria desde el inicio.

Act-008: Equipo de Reparación

● *Descripción:* Nuevo equipo en Galvatec encargado especíﬁcamente de llevar a

cabo las reparaciones de las piezas de aeronaves.

● *Comentario:* Rol fundamental para ejecutar eﬁcientemente las reparaciones,

introducido para fortalecer el proceso de mantenimiento.

Act-009: Mecánicos y Técnicos de Mantenimiento

● *Descripción:* Personal adicional involucrado en la inspección, reparación y

pruebas de las piezas de aeronaves.

● *Comentario:* Roles técnicos esenciales para garantizar la calidad y precisión

en las fases de inspección y reparación.



<a name="br7"></a> 

**En Satair Group:**

Act-010: Gestores de Reparación

● *Descripción:* Responsables de gestionar el proceso de reparación de

componentes en colaboración con el equipo de mantenimiento.

● *Comentario:* Rol de gestión introducido para coordinar eﬁcientemente las

actividades de reparación en Satair Group.

Act-011: Suministro de Repuestos

● *Descripción:* Encargados de garantizar la disponibilidad de repuestos

necesarios para el proceso de mantenimiento.

● *Comentario:* Rol crucial para asegurar la continuidad y eﬁciencia del proceso

mediante la gestión de repuestos.

Act-012: Reparación de Componentes

● *Descripción:* Realiza las reparaciones necesarias en los componentes de las

aeronaves, especialmente aquellos con defectos graves.

● *Comentario:* Rol técnico especializado en la fase de reparación de

componentes.

Act-013: Inspector Final

● *Descripción:* Lleva a cabo la inspección ﬁnal para veriﬁcar que las

reparaciones se realizaron según los estándares y que la aeronave está en

condiciones adecuadas.

● *Comentario:* Rol de control de calidad para asegurar que las reparaciones

cumplen con los requisitos.

Act-014: Gestor de Pruebas

● *Descripción:* Coordina y supervisa las pruebas en tierra y los vuelos de prueba

para garantizar el correcto funcionamiento de los componentes reparados.

● *Comentario:* Rol de coordinación para asegurar pruebas efectivas y

evaluación del rendimiento.

Act-015: Piloto de Prueba

● *Descripción:* Realiza vuelos de prueba para evaluar el rendimiento de las

aeronaves después de las reparaciones.



<a name="br8"></a> 

● *Comentario:* Rol técnico para la validación práctica del rendimiento de las

aeronaves reparadas.

Act-016: Certiﬁcador

● *Descripción:* Certiﬁca que la aeronave está en condiciones de vuelo y que se

han completado adecuadamente las actividades de mantenimiento.

● *Comentario:* Rol ﬁnal para validar y garantizar que las aeronaves estén listas

para su utilización.

**4.2.2.2 Descripción de procesos de negocio a implantar**

La evolución del proceso TO BE presenta notables mejoras con respecto al enfoque AS IS

en el mantenimiento de las piezas de aeronaves.

En primer lugar, la introducción de una solicitud vía correo electrónico en el proceso TO BE

establece una ruta de comunicación más clara y directa para coordinar el mantenimiento.

Esto facilita una comunicación más eficiente y precisa desde el inicio del proceso.

Además, la implementación del TO BE implica la participación de un equipo especializado

en reparaciones y técnicos adicionales, lo que asegura una inspección más exhaustiva de

las piezas y una evaluación más detallada de los defectos. Este enfoque mejora

significativamente la precisión en la identificación y solución de problemas.



<a name="br9"></a> 

Un componente esencial del proceso TO BE es la adopción de un sistema de registro por

estados para las piezas. Este sistema permite que las piezas atraviesen diferentes etapas

claramente definidas, las cuales son registradas en una base de datos. Esto mejora la

trazabilidad y proporciona un seguimiento detallado de cada componente durante todo el

proceso de mantenimiento.

Estados = {

"PROGRAMACION\_COORDINACION\_INICIAL": "Cliente-usuario inicia el mantenimiento

y coordina fechas",

"PAGO\_INICIAL\_SOLICITUD\_MANTENIMIENTO": "Realización del pago inicial y envío

de solicitud por correo electrónico",

"RECEPCION\_ALMACENAMIENTO": "Llegada de solicitud a Galvatec y almacenamiento

en área designada",

"INSPECCION\_INICIAL": "Desconexión de fuentes de energía, inspección y pruebas del

sistema",

"NOTIFICACION\_PRIORIZACION": "Notificación y priorización de defectos graves a

Satair Group"

}

Una ventaja crucial del enfoque TO BE es la introducción de un proceso de priorización de

reparaciones en Satair Group. Esto optimiza los recursos y permite una respuesta más

eficiente a problemas graves, evitando demoras innecesarias en las reparaciones.

El enfoque detallado en la gestión de repuestos y la verificación de su disponibilidad

garantiza un stock adecuado, contribuyendo a una mayor eficiencia en el proceso general y

evitando posibles interrupciones debido a la falta de componentes.

Por último, la certificación de defectos graves por parte de Satair Group añade una capa

adicional de garantía y credibilidad al proceso de mantenimiento, proporcionando una

validación externa y asegurando un estándar de calidad en las reparaciones.

En resumen, el enfoque TO BE sobresale al ofrecer una gestión más directa, una

inspección más detallada, una priorización efectiva de reparaciones, una mejor gestión de

repuestos, la implementación de un sistema de registro por estados para las piezas y una

certificación adicional por parte de una entidad especializada. Estas mejoras combinadas

contribuyen a un mantenimiento más eficiente y preciso de las piezas de aeronaves en

comparación con el proceso AS IS.



<a name="br10"></a> 

**6.2.1 Requisitos generales del sistema**

IRQ-0008 Identiﬁcación Temprana de Defectos Graves

**●** Versión: 1.0 (19/11/2023)

**●** Descripción: El sistema debe proporcionar un enfoque para la identiﬁcación

temprana de defectos graves. Deberá permitir abordar problemas críticos de

manera prioritaria.

**●** Datos especíﬁcos relacionados con la identiﬁcación temprana de defectos

graves.

**●** Comentarios: Coincide con el requisito FOR-01 del proceso de Gestión de

Defectos Mayores.

IRQ-0009 Colaboración con Especialistas Externos (Satair Group)

**●** Versión: 1.0 (19/11/2023)

**●** Descripción: El sistema debe facilitar la colaboración con un especialista

externo (Satair Group) para abordar y solucionar problemas en componentes

con defectos graves. Deberá aprovechar la experiencia y recursos

especializados de Satair Group.

**●** Datos especíﬁcos relacionados con la colaboración con Satair Group.

**●** Comentarios: Coincide con el requisito FOR-02 del proceso de Gestión de

Defectos Mayores.

IRQ-0010 Pruebas en Tierra y Vuelos de Prueba

**●** Versión: 1.0 (19/11/2023)

**●** Descripción: El sistema debe admitir la realización de pruebas en tierra y

vuelos de prueba para evaluar el rendimiento de las aeronaves después de las

reparaciones. Deberá asegurar la funcionalidad y seguridad de los

componentes reparados en situaciones de vuelo real.

**●** Datos especíﬁcos relacionados con las pruebas en tierra y vuelos de prueba.

**●** Comentarios: Coincide con el requisito FOR-03 del proceso de Gestión de

Defectos Mayores.

IRQ-0011 Certiﬁcación Final del Proceso de Mantenimiento



<a name="br11"></a> 

**●** Versión: 1.0 (19/11/2023)

**●** Descripción: El sistema debe permitir la certiﬁcación ﬁnal que valida y

documenta la conclusión exitosa del proceso de mantenimiento. Deberá

proporcionar una capa adicional de garantía y credibilidad al proceso de

mantenimiento.

● Datos especíﬁcos relacionados con la certiﬁcación ﬁnal del proceso de

mantenimiento.

**●** Comentarios: Coincide con el requisito FOR-04 del proceso de Gestión de

Defectos Mayores.

**6.3.2 Casos de uso del sistema**

**6.3.2.1 Diagrama de Casos de Uso del Proceso de gestión de defectos mayores**



<a name="br12"></a> 



<a name="br13"></a> 

**Código UML relativo al Diagrama de Casos de Uso del Proceso de gestión de**

**defectos mayores**

**En galvatec**

@startuml

left to right direction

actor "Cliente o Usuario\nInicial" as Cliente

actor "Equipo de Reparación Galvatec" as EquipoReparacionGalvatec

actor "Mecánicos y Técnicos de\nMantenimiento Galvatec" as TecnicosGalvatec

actor "Sistema Galvatec" as SistemaGalvatec

rectangle "Proceso de Mantenimiento Galvatec" <<S.L.>> #ffff99 {

Cliente -- (Iniciar Mantenimiento)

Cliente -- (Consultar Estado de Mantenimiento)

Cliente -- (Actualizar Información de Contacto)

Cliente -- (Cancelar Mantenimiento)

EquipoReparacionGalvatec -- (Recopilar Información)

EquipoReparacionGalvatec -- (Desmontar Aeronave)

TecnicosGalvatec -- (Realizar Inspección Inicial)

TecnicosGalvatec -- (Reparar Defectos Menores)

TecnicosGalvatec -- (Notificar Defectos Graves a Satair Group)

SistemaGalvatec -- (Generar Informes de Mantenimiento)

SistemaGalvatec -- (Enviar Recordatorios de Mantenimiento)

Cliente -- (Solicitar Asesoramiento Técnico)

TecnicosGalvatec -- (Brindar Asesoramiento Técnico)

TecnicosGalvatec -- (Registrar Historial de Reparaciones)

Cliente -- (Verificar Garantía de Reparación)

TecnicosGalvatec -- (Generar Certificados de Garantía)

TecnicosGalvatec -- (Realizar Pruebas de Validación)

SistemaGalvatec -- (Monitorizar Procesos de Mantenimiento)

SistemaGalvatec -- (Generar Estadísticas de Desempeño)

SistemaGalvatec -- (Configurar Preferencias de Usuario)

}

' Estilo de fondo blanco para los casos de uso

skinparam usecase {

BackgroundColor #white

}

@enduml



<a name="br14"></a> 

**En Satair Group**

@startuml

left to right direction

actor "Gestores de Reparación\nSatair Group" as GestoresReparacionSatair

actor "Suministro de Repuestos\nSatair Group" as SuministroRepuestosSatair

actor "Reparación de Componentes\nSatair Group" as ReparacionComponentesSatair

actor "Inspector Final Satair Group" as InspectorFinalSatair

actor "Gestor de Pruebas\nSatair Group" as GestorPruebasSatair

actor "Piloto de Prueba Satair Group" as PilotoPruebaSatair

actor "Certificador Satair Group" as CertificadorSatair

actor "Sistema Satair Group" as SistemaSatair

rectangle "Proceso de Mantenimiento\nSatair Group" <<S/A>> #ffff99 {

GestoresReparacionSatair -- (Gestionar Reparación)

GestoresReparacionSatair -- (Priorizar Reparaciones)

GestoresReparacionSatair -- (Generar Informes de Reparación)

ReparacionComponentesSatair -- (Realizar Reparaciones)

SuministroRepuestosSatair -- (Gestionar Repuestos)

SuministroRepuestosSatair -- (Verificar Disponibilidad de Repuestos)

InspectorFinalSatair -- (Inspeccionar Componentes)

GestorPruebasSatair -- (Coordinar Pruebas en Tierra)

PilotoPruebaSatair -- (Realizar Vuelos de Prueba)

CertificadorSatair -- (Certificar Aeronave)

SistemaSatair -- (Registrar Estado del Defecto)

SistemaSatair -- (Notificar Resultados de Pruebas)

SistemaSatair -- (Actualizar Base de Datos de Repuestos)

InspectorFinalSatair -- (Generar Informes de Inspección)

PilotoPruebaSatair -- (Registrar Resultados de Vuelos)

CertificadorSatair -- (Auditar Procesos de Certificación)

SuministroRepuestosSatair -- (Gestionar Proveedores de Repuestos)

InspectorFinalSatair -- (Realizar Inspecciones de Calidad)

CertificadorSatair -- (Participar en Auditorías Externas)

GestoresReparacionSatair -- (Notificar Defectos Graves a Galvatec)

SistemaSatair -- (Registrar Estado del Proceso)

SistemaSatair -- (Generar Informes de Desempeño)

SistemaSatair -- (Configurar Preferencias de Usuario)

}

' Estilo de fondo blanco para los casos de uso

skinparam usecase {

BackgroundColor #white

}

@enduml



<a name="br15"></a> 

**6.3.2.2 Especificación de actores del sistema**

**En Galvatec:**

Act-007: Cliente o Usuario Inicial

● *Descripción:* Cliente que inicia el proceso de mantenimiento al programar y

coordinar las actividades de reparación de piezas de aeronaves.

● *Comentario:* Rol clave para la iniciación del proceso, proporcionando la

información necesaria desde el inicio.

Act-008: Equipo de Reparación

● *Descripción:* Nuevo equipo en Galvatec encargado especíﬁcamente de llevar a

cabo las reparaciones de las piezas de aeronaves.

● *Comentario:* Rol fundamental para ejecutar eﬁcientemente las reparaciones,

introducido para fortalecer el proceso de mantenimiento.

Act-009: Mecánicos y Técnicos de Mantenimiento

● *Descripción:* Personal adicional involucrado en la inspección, reparación y

pruebas de las piezas de aeronaves.

● *Comentario:* Roles técnicos esenciales para garantizar la calidad y precisión

en las fases de inspección y reparación.

**En Satair Group:**

Act-010: Gestores de Reparación

● *Descripción:* Responsables de gestionar el proceso de reparación de

componentes en colaboración con el equipo de mantenimiento.

● *Comentario:* Rol de gestión introducido para coordinar eﬁcientemente las

actividades de reparación en Satair Group.

Act-011: Suministro de Repuestos

● *Descripción:* Encargados de garantizar la disponibilidad de repuestos

necesarios para el proceso de mantenimiento.



<a name="br16"></a> 

● *Comentario:* Rol crucial para asegurar la continuidad y eﬁciencia del proceso

mediante la gestión de repuestos.

Act-012: Reparación de Componentes

● *Descripción:* Realiza las reparaciones necesarias en los componentes de las

aeronaves, especialmente aquellos con defectos graves.

● *Comentario:* Rol técnico especializado en la fase de reparación de

componentes.

Act-013: Inspector Final

● *Descripción:* Lleva a cabo la inspección ﬁnal para veriﬁcar que las

reparaciones se realizaron según los estándares y que la aeronave está en

condiciones adecuadas.

● *Comentario:* Rol de control de calidad para asegurar que las reparaciones

cumplen con los requisitos.

Act-014: Gestor de Pruebas

● *Descripción:* Coordina y supervisa las pruebas en tierra y los vuelos de prueba

para garantizar el correcto funcionamiento de los componentes reparados.

● *Comentario:* Rol de coordinación para asegurar pruebas efectivas y

evaluación del rendimiento.

Act-015: Piloto de Prueba

● *Descripción:* Realiza vuelos de prueba para evaluar el rendimiento de las

aeronaves después de las reparaciones.

● *Comentario:* Rol técnico para la validación práctica del rendimiento de las

aeronaves reparadas.

Act-016: Certiﬁcador

● *Descripción:* Certiﬁca que la aeronave está en condiciones de vuelo y que se

han completado adecuadamente las actividades de mantenimiento.

● *Comentario:* Rol ﬁnal para validar y garantizar que las aeronaves estén listas

para su utilización.

**6.3.2.3 Especificación de casos de uso del sistema**



<a name="br17"></a> 

**Especiﬁcación de Casos de Uso del Sistema - Proceso de**

**Mantenimiento en Galvatec S.L.**

UC-0001 Iniciar Proceso de Mantenimiento

*Versión 1.0 (19/11/2023)*

Descripción: El sistema debe comportarse según se describe en el siguiente caso de

uso cuando un cliente decide iniciar un proceso de mantenimiento.

SECUENCIA NORMAL

(1) El actor Cliente solicita al sistema iniciar un proceso de mantenimiento para que

este cargue todas las aeronaves asociadas al cliente.

(2) El actor Cliente selecciona una aeronave especíﬁca entre todas las existentes.

(3) El actor Cliente requiere al sistema poder ver el historial de mantenimiento de

una aeronave, por si esta tiene antecedentes.

(4) El actor Cliente pide al sistema programar una nueva fecha, para que este le

proporcione un calendario y así especiﬁcar una fecha.

(5) El sistema informa al usuario de que la solicitud de mantenimiento ha quedado

registrada correctamente, tras que este último haya conﬁrmado e iniciado el proceso

de mantenimiento.

Precondición: El Cliente se ha identiﬁcado correctamente y su sesión está abierta.

Postcondición: El sistema registra una nueva solicitud de mantenimiento y el Equipo

de Reparación deberá continuar el proceso de mantenimiento.

Comentarios: Si el Cliente intenta abrir una solicitud de mantenimiento sobre una

aeronave que ya está en proceso de mantenimiento, debería salir un error.

Igualmente, si intenta programar una fecha y esta es inferior al día de hoy, debería

dar lugar a un error.

UC-0002 Consultar Estado de Mantenimiento

*Versión 1.0 (19/11/2023)*



<a name="br18"></a> 

Descripción: El sistema debe comportarse según se describe en el siguiente caso de

uso cuando un cliente desea veriﬁcar el estado actual de un proceso de

mantenimiento.

SECUENCIA NORMAL

(1) El actor Cliente solicita al sistema consultar el estado de un mantenimiento en

curso.

(2) El sistema muestra al Cliente la información actualizada del estado del

mantenimiento.

Precondición: El Cliente se ha identiﬁcado correctamente y su sesión está abierta.

Postcondición: No aplica.

Comentarios: No se esperan errores en esta consulta, ya que el propósito es solo

visualizar información.

UC-0003 Actualizar Información de Contacto

*Versión 1.0 (19/11/2023)*

Descripción: El sistema debe comportarse según se describe en el siguiente caso de

uso cuando un cliente desea actualizar su información de contacto.

SECUENCIA NORMAL

(1) El actor Cliente solicita al sistema actualizar su información de contacto.

(2) El sistema permite al Cliente modiﬁcar y guardar la información de contacto.

Precondición: El Cliente se ha identiﬁcado correctamente y su sesión está abierta.

Postcondición: La información de contacto del Cliente queda actualizada en el

sistema.

Comentarios: No se esperan errores en esta operación.

UC-0004 Cancelar Mantenimiento

*Versión 1.0 (19/11/2023)*



<a name="br19"></a> 

Descripción: El sistema debe comportarse según se describe en el siguiente caso de

uso cuando un cliente decide cancelar un proceso de mantenimiento en curso.

SECUENCIA NORMAL

(1) El actor Cliente solicita al sistema cancelar un proceso de mantenimiento en

curso.

(2) El sistema conﬁrma la cancelación y actualiza el estado del mantenimiento.

Precondición: El Cliente se ha identiﬁcado correctamente y su sesión está abierta.

Postcondición: El sistema registra la cancelación del mantenimiento y actualiza el

estado correspondiente.

Comentarios: No se esperan errores en esta operación.

UC-0005 Recopilar Información

*Versión 1.0 (19/11/2023)*

Descripción: El sistema debe comportarse según se describe en el siguiente caso de

uso cuando el Equipo de Reparación recopila información del cliente y realiza la

inspección inicial.

SECUENCIA NORMAL

(1) El equipo de Reparación Galvatec solicita al sistema recopilar información del

cliente y de la aeronave.

(2) El sistema permite al equipo de Reparación ingresar y almacenar la información

recopilada.

Precondición: No aplica.

Postcondición: La información recopilada queda registrada en el sistema.

Comentarios: No se esperan errores en esta operación.

UC-0006 Realizar Inspección Inicial

*Versión 1.0 (19/11/2023)*



<a name="br20"></a> 

Descripción: El sistema debe comportarse según se describe en el siguiente caso de

uso cuando los mecánicos y técnicos de mantenimiento realizan la inspección inicial

de la aeronave.

SECUENCIA NORMAL

(1) El equipo de Reparación Galvatec solicita al sistema realizar la inspección inicial

de la aeronave.

(2) El sistema proporciona una interfaz para que los mecánicos y técnicos ingresen

los resultados de la inspección.

Precondición: La información del cliente y de la aeronave ha sido recopilada

correctamente.

Postcondición: Los resultados de la inspección quedan registrados en el sistema.

Comentarios: No se esperan errores en esta operación.

UC-0007 Notiﬁcar Defectos Graves a Satair Group

*Versión 1.0 (19/11/2023)*

Descripción: El sistema debe comportarse según se describe en el siguiente caso de

uso cuando los mecánicos y técnicos de mantenimiento identiﬁcan defectos graves

y notiﬁcan a Satair Group para su reparación.

SECUENCIA NORMAL

(1) El equipo de Reparación Galvatec solicita al sistema notiﬁcar los defectos graves

a Satair Group.

(2) El sistema genera un informe detallado de los defectos y lo envía a Satair Group.

Precondición: Se han identiﬁcado defectos graves durante la inspección inicial.

Postcondición: Satair Group recibe la notiﬁcación de los defectos graves.

Comentarios: No se esperan errores en esta operación.

UC-0008 Coordinar Pruebas en Tierra con Satair Group

*Versión 1.0 (19/11/2023)*



<a name="br21"></a> 

Descripción: El sistema debe comportarse según se describe en el siguiente caso de

uso cuando se coordinan y supervisan las pruebas en tierra con Satair Group.

SECUENCIA NORMAL

(1) El equipo de Reparación Galvatec solicita al sistema coordinar pruebas en tierra

con Satair Group.

(2) El sistema notiﬁca a Satair Group y coordina la realización de las pruebas en

tierra.

Precondición: Satair Group ha sido notiﬁcado de los defectos graves y ha aceptado

coordinar las pruebas en tierra.

Postcondición: Satair Group realiza las pruebas en tierra según lo coordinado.

Comentarios: No se esperan errores en esta operación.

Estos son algunos ejemplos de casos de uso en el sistema para el Proceso de

Mantenimiento en Galvatec S.L. Puedes seguir este formato para especiﬁcar otros

casos de uso especíﬁcos para el sistema.

**Especiﬁcación de Casos de Uso del Sistema - Proceso de**

**Reparación en Satair Group**

UC-0001 Recibir Notiﬁcación de Defectos Graves

*Versión 1.0 (19/11/2023)*

Descripción: El sistema debe comportarse según se describe en el siguiente caso de

uso cuando Satair Group recibe una notiﬁcación de Galvatec sobre defectos graves

en una aeronave.

SECUENCIA NORMAL

(1) El sistema de Satair Group recibe una notiﬁcación electrónica de Galvatec sobre

defectos graves en una aeronave.

(2) El sistema de Satair Group procesa la notiﬁcación y la clasiﬁca según la gravedad

de los defectos.



<a name="br22"></a> 

Precondición: Satair Group ha establecido una conexión electrónica con Galvatec

para recibir notiﬁcaciones.

Postcondición: Satair Group tiene registrada la notiﬁcación de defectos graves y

clasiﬁcada según su gravedad.

Comentarios: No se esperan errores en esta operación.

UC-0002 Evaluar Defectos Graves y Proveer Soluciones

*Versión 1.0 (19/11/2023)*

Descripción: El sistema debe comportarse según se describe en el siguiente caso de

uso cuando Satair Group evalúa los defectos graves notiﬁcados por Galvatec y

propone soluciones.

SECUENCIA NORMAL

(1) El personal técnico de Satair Group analiza los informes de defectos graves

proporcionados por Galvatec.

(2) El sistema de Satair Group presenta opciones de solución para cada defecto

grave.

(3) Satair Group selecciona las soluciones apropiadas y las comunica a Galvatec.

Precondición: Satair Group ha recibido notiﬁcaciones de defectos graves.

Postcondición: Satair Group ha proporcionado soluciones propuestas a Galvatec.

Comentarios: No se esperan errores en esta operación.

UC-0003 Coordinar Envío de Repuestos y Componentes

*Versión 1.0 (19/11/2023)*

Descripción: El sistema debe comportarse según se describe en el siguiente caso de

uso cuando Satair Group coordina el envío de repuestos y componentes necesarios

para la reparación.

SECUENCIA NORMAL

(1) Satair Group recibe la conﬁrmación de Galvatec sobre las soluciones propuestas.

(2) El sistema de Satair Group veriﬁca la disponibilidad de repuestos y componentes



<a name="br23"></a> 

necesarios para la reparación.

(3) Satair Group coordina con proveedores y servicios de envío para garantizar la

entrega oportuna de los repuestos y componentes.

Precondición: Satair Group ha recibido las soluciones propuestas y conﬁrmación de

Galvatec.

Postcondición: Se ha coordinado el envío de repuestos y componentes necesarios

para la reparación.

Comentarios: No se esperan errores en esta operación.

UC-0004 Registrar Avance en el Sistema de Seguimiento de Reparaciones

*Versión 1.0 (19/11/2023)*

Descripción: El sistema debe comportarse según se describe en el siguiente caso de

uso cuando Satair Group registra el avance y estado de las reparaciones en el

sistema de seguimiento.

SECUENCIA NORMAL

(1) Satair Group recibe conﬁrmación de la recepción de repuestos y componentes

por parte de Galvatec.

(2) El sistema de Satair Group actualiza el estado de la reparación en el sistema de

seguimiento, indicando el inicio de las actividades de reparación.

Precondición: Se ha coordinado y recibido los repuestos y componentes necesarios

para la reparación.

Postcondición: El sistema de seguimiento de Satair Group reﬂeja el avance y estado

actualizado de la reparación.

Comentarios: No se esperan errores en esta operación.

UC-0005 Realizar Pruebas y Veriﬁcaciones Post-Reparación

*Versión 1.0 (19/11/2023)*

Descripción: El sistema debe comportarse según se describe en el siguiente caso de

uso cuando Satair Group realiza pruebas y veriﬁcaciones posteriores a la reparación.



<a name="br24"></a> 

SECUENCIA NORMAL

(1) El personal técnico de Satair Group realiza pruebas y veriﬁcaciones en la

aeronave reparada.

(2) El sistema de Satair Group registra los resultados de las pruebas y veriﬁca que la

aeronave cumple con los estándares de seguridad y rendimiento.

Precondición: Se ha completado la reparación de la aeronave.

Postcondición: Se han registrado los resultados de las pruebas y veriﬁcaciones

post-reparación.

Comentarios: No se esperan errores en esta operación.

UC-0006 Comunicar Finalización de Reparación a Galvatec

*Versión 1.0 (19/11/2023)*

Descripción: El sistema debe comportarse según se describe en el siguiente caso de

uso cuando Satair Group comunica a Galvatec la ﬁnalización exitosa de la

reparación.

SECUENCIA NORMAL

(1) Satair Group veriﬁca que todas las pruebas y veriﬁcaciones post-reparación han

sido exitosas.

(2) El sistema de Satair Group notiﬁca a Galvatec la ﬁnalización exitosa de la

reparación y proporciona detalles sobre las acciones realizadas.

Precondición: Se han completado con éxito las pruebas y veriﬁcaciones

post-reparación.

Postcondición: Galvatec recibe la notiﬁcación de la ﬁnalización exitosa de la

reparación.

Comentarios: No se esperan errores en esta operación.

UC-0007 Facturación por Servicios de Reparación

*Versión 1.0 (19/11/2023)*



<a name="br25"></a> 

Descripción: El sistema debe comportarse según se describe en el siguiente caso de

uso cuando Satair Group emite la factura por los servicios de reparación prestados a

Galvatec.

SECUENCIA NORMAL

(1) Satair Group conﬁrma con Galvatec que la reparación ha sido completada

satisfactoriamente.

(2) El sistema de Satair Group genera la factura correspondiente por los servicios de

reparación prestados.

(3) Satair Group envía la factura a Galvatec.

Precondición: Galvatec ha sido notiﬁcado de la ﬁnalización exitosa de la reparación.

Postcondición: Galvatec recibe la factura correspondiente por los servicios de

reparación.

Comentarios: No se esperan errores en esta operación.

UC-008 Certiﬁcar Reparación Exitosa de Pieza

Versión 1.0 (Fecha)

Descripción: El sistema debe comportarse según se describe en el siguiente caso de

uso cuando el Certiﬁcador veriﬁca y certiﬁca la reparación exitosa de una pieza

después de la evaluación de vuelo.

SECUENCIA NORMAL

(1) El Certiﬁcador accede al sistema y selecciona la opción para certiﬁcar la

reparación de una pieza.

(2) El sistema presenta un resumen ejecutivo de la evaluación de vuelo asociada a la

reparación de la pieza.

(3) El Certiﬁcador revisa los informes detallados de la evaluación de vuelo

disponibles en el sistema.

(4) El Certiﬁcador notiﬁca al sistema si se identiﬁcan problemas durante la revisión.

(5) El sistema informa al Equipo de Reparación Galvatec sobre los problemas

identiﬁcados y las correcciones requeridas.

(6) El Certiﬁcador, después de la revisión y sin problemas pendientes, certiﬁca la

reparación como exitosa.



<a name="br26"></a> 

(7) El sistema genera un certiﬁcado de reparación asociado a la pieza.

(8) El sistema actualiza la base de datos, marcando la pieza como certiﬁcada.

Precondición: La pieza ha pasado por el proceso de reparación y evaluación de

vuelo.

Postcondición: La pieza queda certiﬁcada como reparación exitosa en el sistema.

Comentarios: No se esperan errores en esta operación.

**6.3.3 Requisitos funcionales del sistema**

**6.3.3.1 Requisitos de información del sistema**

● NFR-0001 Identiﬁcación Única de cada Defecto Grave

● Versión 1.0 (19/11/2023)

● Descripción: El sistema debe permitir la generación de un código de

identiﬁcación único para cada defecto grave registrado en el proceso de

gestión de defectos mayores. Esto facilitará un seguimiento preciso de los

defectos, asegurará su identiﬁcación y trazabilidad, y permitirá priorizar y

abordar eﬁcientemente los problemas críticos.

● Comentarios: Coincide con el requisito IRQ-0008 del sistema.

● NFR-0002 Colaboración con Especialistas Externos (Satair Group)

● Versión 1.0 (19/11/2023)

● Descripción: El sistema debe facilitar la colaboración con especialistas

externos, en este caso, Satair Group, para abordar y solucionar problemas en

componentes con defectos graves. Esto implica aprovechar la experiencia y

recursos especializados de Satair Group durante el proceso de gestión de

defectos mayores.

● Comentarios: Coincide con el requisito IRQ-0009 del sistema.

● NFR-0003 Pruebas en Tierra y Vuelos de Prueba

● Versión 1.0 (19/11/2023)

● Descripción: El sistema debe admitir la realización de pruebas en tierra y

vuelos de prueba para evaluar el rendimiento de las aeronaves después de las

reparaciones. Esto garantizará la funcionalidad y seguridad de los

componentes reparados en situaciones de vuelo real durante el proceso de

gestión de defectos mayores.

● Comentarios: Coincide con el requisito IRQ-0010 del sistema.

● NFR-0004 Certiﬁcación Final del Proceso de Mantenimiento

● Versión 1.0 (19/11/2023)

● Descripción: El sistema debe permitir la certiﬁcación ﬁnal que valida y

documenta la conclusión exitosa del proceso de mantenimiento en el



<a name="br27"></a> 

contexto de la gestión de defectos mayores. Esto proporcionará una capa

adicional de garantía y credibilidad al proceso de mantenimiento.

● Comentarios: Coincide con el requisito IRQ-0011 del sistema.

● NFR-0005 Gestión de Documentación Técnica Asociada

● Versión 1.0 (19/11/2023)

● Descripción: El sistema deberá proporcionar una funcionalidad para gestionar

la documentación técnica asociada a cada defecto grave registrado. Esto

incluye manuales de reparación, informes de pruebas, certiﬁcados de

cumplimiento y cualquier otro documento relevante. La gestión efectiva de la

documentación contribuirá a la transparencia y cumplimiento normativo del

proceso de gestión de defectos mayores.

● Comentarios:Coincide con el requisito IRQ-0012 del sistema.

**6.3.3.2 Requisitos de reglas de negocio del sistema**

● NFR-0014 Priorización Efectiva de Reparaciones

● Versión 1.0 (19/11/2023)

● Descripción: El sistema debe implementar un proceso de priorización efectiva

de reparaciones en colaboración con Satair Group. Esto permitirá optimizar

los recursos y abordar de manera eﬁciente los problemas graves, evitando

demoras innecesarias.

● Comentarios: Coincide con la necesidad de priorización temprana de

defectos graves (IRQ-0008).

● NFR-0015 Gestión Efectiva de Repuestos

● Versión 1.0 (19/11/2023)

● Descripción: El sistema debe garantizar la gestión efectiva de repuestos,

veriﬁcando continuamente su disponibilidad y contribuyendo a mantener un

stock adecuado. Esto evitará interrupciones en el proceso debido a la falta de

componentes.

● Comentarios: Coincide con la importancia de la gestión de repuestos en el

enfoque TO BE.

● NFR-0016 Certiﬁcación Adicional de Defectos Graves por Satair Group

● Versión 1.0 (19/11/2023)

● Descripción: El sistema deberá permitir que Satair Group certiﬁque los

defectos graves una vez reparados, añadiendo una capa adicional de garantía

y credibilidad al proceso de mantenimiento. Esta certiﬁcación proporcionará

validación externa y asegurará estándares de calidad.

● NFR-0017 Colaboración Eﬁciente con Satair Group

● Versión 1.0 (19/11/2023)

● Descripción: El sistema debe facilitar una colaboración eﬁciente con Satair

Group en todas las fases del proceso, permitiendo una comunicación ﬂuida,

intercambio de información y coordinación efectiva. Esto garantizará una

respuesta rápida y coordinada ante defectos graves.



<a name="br28"></a> 

● Comentarios: Refuerza la importancia de una colaboración estrecha con

especialistas externos (IRQ-0009).

● NFR-0018 Registro Detallado de Pruebas en Tierra y Vuelos

● Versión 1.0 (19/11/2023)

● Descripción: El sistema debe registrar de manera detallada todas las pruebas

en tierra y vuelos de prueba realizados en el proceso de gestión de defectos

graves. Esto incluirá resultados, observaciones y cualquier otra información

relevante para evaluar el rendimiento de los componentes reparados.

● Comentarios: Contribuye a la trazabilidad y evaluación del rendimiento

(IRQ-0010 y 0011).

● NFR-0019 Certiﬁcación y Auditoría Automatizadas

● Versión 1.0 (19/11/2023)

● Descripción: El sistema deberá automatizar el proceso de certiﬁcación ﬁnal y

auditoría de los procesos de mantenimiento. Esto agilizará la validación y

garantizará que se sigan los estándares establecidos de manera consistente.

● Comentarios: Refuerza la necesidad de certiﬁcación ﬁnal (IRQ-0011) y

auditorías externas (CertiﬁcadorSatair - Act-016).

● NFR-0020 Gestión Centralizada de Proveedores de Repuestos

● Versión 1.0 (19/11/2023)

● Descripción: El sistema debe permitir la gestión centralizada de proveedores

de repuestos, asegurando una colaboración eﬁciente con múltiples

proveedores. Esto garantizará la disponibilidad oportuna de repuestos y

contribuirá a una gestión efectiva del inventario.

● Comentarios: Refuerza la importancia de la gestión de repuestos y

proveedores (NFR-0015 y SuministroRepuestosSatair - Act-011).

● NFR-0021 Conﬁguración de Preferencias de Usuario

● Versión 1.0 (19/11/2023)

● Descripción: El sistema debe permitir que los usuarios, tanto en Galvatec

como en Satair Group, conﬁguren sus preferencias individuales en la interfaz

del sistema. Esto incluirá opciones de visualización, notiﬁcaciones y otras

conﬁguraciones personalizadas.

● Comentarios: Contribuye a la experiencia del usuario y su adaptabilidad al

sistema (Cliente - Act-007, SistemaGalvatec - Act-009, y otros).

**6.3.3.3 Requisitos de conducta del sistema**

● NFR-0022 Respuesta Rápida a Notiﬁcaciones Críticas

● Versión 1.0 (19/11/2023)

● Descripción: El sistema debe garantizar una respuesta rápida a

notiﬁcaciones críticas, especialmente aquellas relacionadas con

defectos graves. Esto implica una notiﬁcación inmediata a los usuarios

relevantes, asegurando una acción rápida y coordinada para abordar

problemas urgentes.



<a name="br29"></a> 

● Comentarios: Contribuye a la eﬁciencia y efectividad en la gestión de

defectos graves, cumpliendo con IRQ-0008 y NFR-0017.

● NFR-0023 Interfaz Intuitiva y de Fácil Navegación

● Versión 1.0 (19/11/2023)

● Descripción: La interfaz del sistema debe ser intuitiva y de fácil

navegación para todos los usuarios, desde el personal en Galvatec

hasta los especialistas en Satair Group. Esto asegurará una adopción

rápida y eﬁciente del sistema, reduciendo la curva de aprendizaje.

● Comentarios: Contribuye a la usabilidad y aceptación del sistema por

parte de los diferentes actores en ambos entornos (Galvatec y Satair

Group).

● NFR-0024 Información Clara y Detallada en Informes

● Versión 1.0 (19/11/2023)

● Descripción: Los informes generados por el sistema deben

proporcionar información clara y detallada sobre el estado de los

componentes, reparaciones realizadas, resultados de pruebas y

cualquier otro aspecto relevante. Esto asegurará una toma de

decisiones informada y precisa.

● Comentarios: Contribuye a la transparencia y trazabilidad en el proceso

de gestión de defectos graves, cumpliendo con NFR-0002, NFR-0018 y

otros.

● NFR-0025 Mantenimiento de la Privacidad de Datos Sensibles

● Versión 1.0 (19/11/2023)

● Descripción: El sistema debe garantizar la máxima seguridad y

conﬁdencialidad de los datos sensibles, como información del cliente,

detalles de reparaciones y resultados de pruebas. Esto cumplirá con

los estándares de privacidad y protección de datos.

● Comentarios: Garantiza el cumplimiento de normativas de privacidad y

protección de datos en el manejo de información sensible.

● NFR-0026 Registro de Actividades y Auditoría

● Versión 1.0 (19/11/2023)

● Descripción: El sistema debe mantener un registro detallado de todas

las actividades realizadas por los usuarios, cambios en el estado de

los componentes y cualquier modiﬁcación en la información crítica.

Esto facilitará auditorías internas y externas, garantizando la integridad

y trazabilidad del sistema.

● Comentarios: Contribuye a la transparencia y rendición de cuentas,

cumpliendo con NFR-0019 y NFR-0020.

● NFR-0027 Tolerancia a Fallos y Continuidad del Servicio

● Versión 1.0 (19/11/2023)

● Descripción: El sistema debe ser tolerante a fallos y garantizar la

continuidad del servicio incluso en situaciones adversas, como



<a name="br30"></a> 

interrupciones de red o caídas del servidor. Esto asegurará la

disponibilidad constante del sistema.

● Comentarios: Mejora la conﬁabilidad del sistema, asegurando que esté

siempre disponible para los usuarios.

**6.3.4 Requisitos No Funcionales del Sistema**

6\.3.4.1 Requisitos de Fiabilidad del Sistema

● NFR-0050 Copias de Seguridad Automáticas de Datos Críticos

● Descripción: El sistema debe realizar copias de seguridad automáticas

de los datos críticos relacionados con el proceso de defectos mayores,

garantizando la disponibilidad y recuperación de la información en

caso de fallas.

● Comentarios: Mejora la ﬁabilidad al asegurar la integridad de los datos

ante posibles contingencias.

● NFR-0051 Sistema de Registro de Actividades

● Descripción: El sistema debe mantener un registro detallado de todas

las actividades realizadas en el proceso de defectos mayores,

incluyendo notiﬁcaciones, reparaciones y certiﬁcaciones.

● Comentarios: Facilita la auditoría y análisis posterior, mejorando la

ﬁabilidad y transparencia del proceso.

● NFR-0052 Mecanismos de Detección y Corrección de Errores

● Descripción: El sistema debe incorporar mecanismos automáticos de

detección y corrección de errores en tiempo real, minimizando la

posibilidad de fallos y asegurando la consistencia de los datos.

● Comentarios: Aumenta la ﬁabilidad al prevenir y corregir posibles

errores de manera proactiva.

● NFR-0053 Tiempo Máximo de Inactividad Permitido

● Descripción: El sistema debe cumplir con un tiempo máximo de

inactividad permitido durante el proceso de defectos mayores,

garantizando la disponibilidad continua y la eﬁciencia del sistema.

● Comentarios: Establece estándares de ﬁabilidad al minimizar

interrupciones en el proceso.

● NFR-0054 Protocolos de Seguridad para Colaboración Externa

● Descripción: El sistema debe implementar protocolos de seguridad

robustos para la colaboración con entidades externas, especialmente

con Satair Group, asegurando la conﬁdencialidad e integridad de la

información compartida.

● Comentarios: Refuerza la ﬁabilidad en las interacciones con

especialistas externos.



<a name="br31"></a> 

6\.3.4.2 Requisitos de Usabilidad del Sistema

● NFR-0042 Navegación Jerarquizada de Defectos

● Descripción: El sistema debe proporcionar una navegación

jerarquizada de los defectos mayores, permitiendo a los usuarios

acceder fácilmente a información detallada sobre cada defecto y su

historial.

● Comentarios: Facilita la gestión eﬁciente al organizar la información de

manera estructurada.

● NFR-0043 Vista Rápida de Prioridades

● Descripción: El sistema debe incluir una vista rápida que muestre las

prioridades actuales de los defectos mayores, permitiendo a los

usuarios identiﬁcar y abordar rápidamente los problemas críticos.

● Comentarios: Agiliza la toma de decisiones al proporcionar una visión

general de la situación.

● NFR-0044 Seguimiento de Etapas de Reparación

● Descripción: El sistema debe permitir a los usuarios realizar un

seguimiento detallado de las etapas de reparación de cada defecto

grave, desde la notiﬁcación inicial hasta la certiﬁcación ﬁnal.

● Comentarios: Mejora la trazabilidad y transparencia en el proceso de

reparación.

● NFR-0045 Información Contextual de Satair Group

● Descripción: El sistema debe integrar información contextual sobre la

colaboración con Satair Group, brindando a los usuarios datos

relevantes sobre las interacciones con especialistas externos.

● Comentarios: Facilita la colaboración y coordinación con Satair Group

al tener información contextual disponible.

● NFR-0046 Interfaz Simpliﬁcada para Certiﬁcación Final

● Descripción: El sistema debe proporcionar una interfaz simpliﬁcada

para la certiﬁcación ﬁnal de los defectos mayores, asegurando un

proceso eﬁciente y sin complicaciones.

● Comentarios: Optimiza la etapa ﬁnal del proceso de mantenimiento.

6\.3.4.3 Requisitos de Mantenibilidad del Sistema

● NFR-0060 Modularidad en la Gestión de Componentes

● Descripción: El sistema debe ser modular en la gestión de

componentes, permitiendo la fácil incorporación de nuevas

funcionalidades o actualizaciones relacionadas con el proceso de

defectos mayores sin afectar el funcionamiento general.

● Comentarios: Mejora la mantenibilidad al facilitar la evolución y

adaptación del sistema a cambios en el proceso.

● NFR-0061 Documentación Exhaustiva del Código



<a name="br32"></a> 

● Descripción: El código fuente del sistema debe estar acompañado de

documentación exhaustiva que explique la lógica, funcionalidades y

relaciones entre los módulos especíﬁcos para el proceso de defectos

mayores.

● Comentarios: Facilita la comprensión y mantenimiento del sistema,

permitiendo una gestión más eﬁciente.

● NFR-0062 Herramientas de Depuración y Monitoreo

● Descripción: El sistema debe integrar herramientas de depuración y

monitoreo especíﬁcas para el proceso de defectos mayores,

permitiendo identiﬁcar y solucionar problemas de manera eﬁciente.

● Comentarios: Contribuye a la rápida identiﬁcación y resolución de

problemas, mejorando la mantenibilidad.

● NFR-0063 Actualizaciones Remotas del Sistema

● Descripción: El sistema debe ser capaz de recibir actualizaciones

remotas de manera segura, permitiendo la implementación de mejoras

o correcciones sin interrupciones signiﬁcativas en el proceso de

defectos mayores.

● Comentarios: Facilita la actualización continua del sistema para

adaptarse a nuevas necesidades y corregir posibles problemas.

● NFR-0064 Registro Detallado de Cambios

● Descripción: El sistema debe mantener un registro detallado de todos

los cambios realizados, incluyendo actualizaciones, parches o

modiﬁcaciones especíﬁcas para el proceso de defectos mayores.

● Comentarios: Facilita la trazabilidad de cambios, apoyando la gestión y

mantenimiento efectivos del sistema.

6\.3.4.4 Requisitos de Eﬁciencia del Sistema

● NFR-0070 Optimización en la Coordinación de Reparaciones

● Descripción: El sistema debe optimizar la coordinación de

reparaciones, asignando eﬁcientemente los recursos disponibles,

minimizando tiempos de inactividad y asegurando una respuesta ágil a

defectos graves.

● Comentarios: Contribuye a la eﬁciencia operativa al mejorar la

planiﬁcación y ejecución de reparaciones críticas.

● NFR-0071 Gestión Eﬁciente de Recursos de Satair Group

● Descripción: El sistema debe optimizar la gestión de recursos de Satair

Group, asegurando una asignación eﬁciente de especialistas y equipos

para abordar los defectos graves de manera oportuna.

● Comentarios: Mejora la eﬁciencia al utilizar de manera óptima los

recursos especializados de Satair Group.

● NFR-0072 Reducción de Tiempos en Pruebas y Validación



<a name="br33"></a> 

● Descripción: El sistema debe reducir los tiempos en las fases de

pruebas y validación, garantizando la seguridad y funcionalidad de las

aeronaves reparadas sin comprometer la calidad del proceso.

● Comentarios: Contribuye a la eﬁciencia al acelerar la validación de

componentes reparados.

● NFR-0073 Minimización de Retrasos en la Certiﬁcación Final

● Descripción: El sistema debe minimizar los retrasos en la certiﬁcación

ﬁnal, optimizando los procesos involucrados y asegurando la emisión

oportuna de certiﬁcaciones.

● Comentarios: Contribuye a la eﬁciencia al evitar demoras innecesarias

en la conclusión del proceso de mantenimiento.

● NFR-0074 Gestión Eﬁciente del Inventario de Repuestos

● Descripción: El sistema debe optimizar la gestión del inventario de

repuestos, asegurando disponibilidad inmediata y evitando

interrupciones en el proceso de defectos mayores.

● Comentarios: Contribuye a la eﬁciencia al mantener un suministro

adecuado de repuestos para las reparaciones.

6\.3.4.5 Requisitos de Portabilidad del Sistema

● NFR-0075 Acceso Remoto a la Plataforma de Coordinación

● Descripción: El sistema debe permitir el acceso remoto a la plataforma

de coordinación del proceso de defectos mayores, facilitando la

gestión y supervisión desde ubicaciones externas.

● Comentarios: Contribuye a la portabilidad al permitir el monitoreo y

control del proceso de manera remota.

● NFR-0076 Compatibilidad con Dispositivos Móviles para Inspecciones

Iniciales

● Descripción: El sistema debe ser compatible con dispositivos móviles

para realizar inspecciones iniciales de componentes, permitiendo a los

técnicos llevar a cabo evaluaciones in situ de manera eﬁciente.

● Comentarios: Mejora la portabilidad al facilitar la movilidad durante la

fase de inspección.

● NFR-0077 Integración con Plataformas de Comunicación Externa

● Descripción: El sistema debe integrarse con plataformas de

comunicación externa utilizadas por Satair Group y otros

colaboradores, asegurando una comunicación ﬂuida y eﬁcaz durante el

proceso de defectos mayores.

● Comentarios: Mejora la portabilidad al facilitar la interconexión con

sistemas externos.

● NFR-0078 Visualización Optimizada en Diferentes Dispositivos



<a name="br34"></a> 

● Descripción: El sistema debe ofrecer una visualización optimizada en

diferentes dispositivos, incluyendo computadoras de escritorio,

tabletas y dispositivos móviles, para garantizar una experiencia de

usuario consistente.

● Comentarios: Contribuye a la portabilidad al adaptarse a diferentes

tipos de dispositivos.

6\.3.4.6 Requisitos de Seguridad del Sistema

● NFR-0079 Control de Acceso Diferenciado para Roles Sensibles

● Descripción: El sistema debe implementar un control de acceso

diferenciado para roles sensibles dentro del proceso de defectos

mayores, como gestores de reparación y certiﬁcadores, garantizando la

conﬁdencialidad y seguridad de la información crítica.

● Comentarios: Mejora la seguridad al limitar el acceso a funciones

críticas a roles especíﬁcos.

● NFR-0080 Registro Detallado de Acciones Sensibles

● Descripción: El sistema debe mantener un registro detallado de las

acciones realizadas por roles sensibles, como certiﬁcadores y gestores

de reparación, proporcionando una trazabilidad completa y auditable

de las actividades críticas.

● Comentarios: Aumenta la seguridad al permitir una auditoría detallada

de acciones clave.

● NFR-0081 Encriptación de Comunicaciones Sensibles con Satair Group

● Descripción: El sistema debe implementar encriptación para todas las

comunicaciones sensibles con Satair Group, asegurando la

conﬁdencialidad de la información transmitida entre las entidades.

● Comentarios: Refuerza la seguridad al proteger la integridad de la

comunicación con colaboradores externos.

● NFR-0082 Veriﬁcación de Identidad para Colaboradores Externos

● Descripción: El sistema debe incorporar un mecanismo de veriﬁcación

de identidad robusto para colaboradores externos, como inspectores

ﬁnales y pilotos de prueba, garantizando la autenticidad de las

personas involucradas en el proceso.

● Comentarios: Aumenta la seguridad al prevenir accesos no autorizados

y suplantación de identidad.

● NFR-0083 Respaldo Seguro de Datos Críticos del Proceso

● Descripción: El sistema debe realizar respaldos periódicos y seguros

de los datos críticos del proceso de defectos mayores, garantizando la

disponibilidad y recuperación eﬁciente en caso de eventos adversos.

● Comentarios: Contribuye a la seguridad al asegurar la continuidad

operativa y la protección contra pérdida de datos.



<a name="br35"></a> 

6\.3.4.7 Otros Requisitos No Funcionales del Sistema

● NFR-0084 Integración con Sistemas de Monitoreo de la Industria Aeronáutica

● Descripción: El sistema debe ser capaz de integrarse de manera

eﬁciente con los sistemas de monitoreo de la industria aeronáutica

para recibir y compartir información relevante sobre estándares,

regulaciones y mejores prácticas.

● Comentarios: Facilita la adaptación del proceso a los estándares de la

industria y garantiza la conformidad con las regulaciones.

● NFR-0085 Interfaz de Usuario Intuitiva y Adaptativa

● Descripción: La interfaz de usuario del sistema debe ser intuitiva y

adaptativa, proporcionando una experiencia amigable para usuarios de

diferentes roles, desde mecánicos hasta gestores de reparación.

● Comentarios: Mejora la usabilidad y eﬁciencia al facilitar la interacción

de usuarios con diferentes niveles de experiencia.

● NFR-0087 Documentación Exhaustiva del Sistema

● Versión 1.0 (19/11/2023)

● Descripción: Se debe proporcionar una documentación exhaustiva del

sistema, incluyendo manuales de usuario, guías de administración y

descripciones técnicas, para facilitar la comprensión y gestión del

sistema.

● Comentarios: Contribuye a la mantenibilidad y facilita la capacitación

de usuarios y administradores.

● NFR-0088 Actualizaciones y Parches Automatizados

● Versión 1.0 (19/11/2023)

● Descripción: El sistema debe admitir actualizaciones y parches

automáticos para garantizar la aplicación rápida y eﬁciente de mejoras,

correcciones y nuevas funcionalidades.

● Comentarios: Mejora la mantenibilidad y la seguridad al garantizar que

el sistema esté siempre actualizado.

● NFR-0089 Cumplimiento de Normativas de Seguridad Aeronáutica

● Versión 1.0 (19/11/2023)

● Descripción: El sistema debe cumplir con las normativas y estándares

de seguridad aeronáutica establecidos por autoridades competentes,

garantizando la seguridad y conﬁabilidad en el mantenimiento de

componentes aeronáuticos.

● Comentarios: Esencial para cumplir con regulaciones y asegurar la

seguridad en la industria aeronáutica



<a name="br36"></a> 

**Proceso de Mantenimiento en Galvatec S.L.:**

**1. UC-0001 Iniciar Proceso de Mantenimiento**

**Código**

@startuml

actor Cliente

participant Sistema

participant "Equipo de Reparación" as EquipoReparacion

== Iniciar Proceso de Mantenimiento ==



<a name="br37"></a> 

Cliente -> Sistema: Solicitar inicio de mantenimiento

activate Sistema

Sistema -> Sistema: Cargar aeronaves del cliente

Sistema -> Cliente: Mostrar lista de aeronaves

Cliente -> Sistema: Seleccionar aeronave específica

Sistema -> Sistema: Cargar historial de mantenimiento

Cliente -> Sistema: Ver historial de mantenimiento

Cliente -> Sistema: Solicitar programación de fecha

Sistema -> Sistema: Mostrar calendario

Cliente -> Sistema: Seleccionar fecha

Sistema -> Sistema: Registrar solicitud de mantenimiento

Sistema -> Cliente: Informar solicitud registrada

deactivate Sistema

Cliente -> EquipoReparacion: Continuar con el proceso de mantenimiento

@enduml

**2. UC-0002 Consultar Estado de Mantenimiento**

**Código**

@startuml



<a name="br38"></a> 

actor Cliente

participant Sistema

database BaseDeDatos

== Consultar Estado de Mantenimiento ==

alt Cliente autenticado

Cliente -> Sistema: Solicitar consulta de estado de mantenimiento

activate Sistema

Sistema -> BaseDeDatos: Consultar estado actual de mantenimiento

BaseDeDatos --> Sistema: Devolver información del estado

Sistema -> Cliente: Mostrar información actual del estado

Cliente --> Sistema: Realizar acciones según la información mostrada

deactivate Sistema

else Cliente no autenticado

Cliente -> Sistema: Solicitar consulta de estado de mantenimiento (sin autenticación)

Sistema --> Cliente: Mostrar mensaje de error (autenticación requerida)

end

@enduml

**3. UC-0003 Actualizar Información de Contacto**



<a name="br39"></a> 

**Código**

@startuml

actor Cliente

participant Sistema

database BaseDeDatos

== Actualizar Información de Contacto ==

alt Cliente autenticado

Cliente -> Sistema: Solicitar actualización de información de contacto

activate Sistema

Sistema -> BaseDeDatos: Consultar información actual de contacto

BaseDeDatos --> Sistema: Devolver información actual

Sistema -> Cliente: Mostrar información actual

Cliente --> Sistema: Ingresar nueva información de contacto

Sistema -> BaseDeDatos: Actualizar información de contacto

BaseDeDatos --> Sistema: Confirmar actualización exitosa

Sistema -> Cliente: Confirmar actualización exitosa

Cliente --> Sistema: Fin de la operación

deactivate Sistema

else Cliente no autenticado

Cliente -> Sistema: Solicitar actualización de información de contacto (sin autenticación)

Sistema --> Cliente: Mostrar mensaje de error (autenticación requerida)

end

@enduml

**4. UC-0004 Cancelar Mantenimiento**

**Código**

@startuml

actor Cliente

participant Sistema

database BaseDeDatos

participant "Equipo de Reparación"

== Cancelar Mantenimiento ==



<a name="br40"></a> 

alt Cliente autenticado

Cliente -> Sistema: Solicitar cancelación de mantenimiento

activate Sistema

Sistema -> BaseDeDatos: Verificar estado del mantenimiento y obtener

detalles

BaseDeDatos --> Sistema: Devolver detalles del mantenimiento

Sistema -> Cliente: Mostrar detalles del mantenimiento y confirmar

cancelación

Cliente --> Sistema: Confirmar cancelación

Sistema -> BaseDeDatos: Actualizar estado del mantenimiento (cancelado)

BaseDeDatos --> Sistema: Confirmación de actualización

Sistema -> "Equipo de Reparación": Notificar cancelación de

mantenimiento

"Equipo de Reparación" --> Sistema: Confirmar recepción de notificación

Sistema --> Cliente: Mostrar mensaje de confirmación de cancelación

deactivate Sistema

else Cliente no autenticado

Cliente -> Sistema: Solicitar cancelación de mantenimiento (sin

autenticación)

Sistema --> Cliente: Mostrar mensaje de error (autenticación requerida)

end

@enduml



<a name="br41"></a> 

**5. UC-0005 Recopilar Información**

**Código**

@startuml

actor "Equipo de Reparación" as EquipoReparacion

participant Sistema

database BaseDeDatos

actor Cliente

== Recopilar Información ==

EquipoReparacion -> Sistema: Solicitar recopilación de información

activate Sistema

Sistema --> BaseDeDatos: Consultar información del cliente y la aeronave

BaseDeDatos --> Sistema: Devolver detalles del cliente y la aeronave

Sistema -> EquipoReparacion: Mostrar interfaz para recopilar información

activate EquipoReparacion

EquipoReparacion -> Sistema: Ingresar información recopilada

deactivate EquipoReparacion

Sistema -> BaseDeDatos: Almacenar información recopilada



<a name="br42"></a> 

BaseDeDatos --> Sistema: Confirmación de almacenamiento

Sistema --> EquipoReparacion: Mostrar mensaje de éxito

deactivate Sistema

@enduml

**6. UC-0006 Realizar Inspección Inicial**

**Código**

@startuml

actor "Equipo de Reparación" as EquipoReparacion

participant Sistema

database BaseDeDatos

actor "Mecánicos y Técnicos" as Tecnicos

== Realizar Inspección Inicial ==

EquipoReparacion -> Sistema: Solicitar inspección inicial de la aeronave

activate Sistema

Sistema -> BaseDeDatos: Consultar información del cliente y la aeronave

activate BaseDeDatos



<a name="br43"></a> 

BaseDeDatos --> Sistema: Devolver detalles del cliente y la aeronave

deactivate BaseDeDatos

Sistema -> Tecnicos: Proporcionar interfaz para ingresar resultados de

inspección

activate Tecnicos

Tecnicos -> Sistema: Ingresar resultados de la inspección

deactivate Tecnicos

Sistema -> BaseDeDatos: Almacenar resultados de la inspección

activate BaseDeDatos

BaseDeDatos --> Sistema: Confirmación de almacenamiento

deactivate BaseDeDatos

Sistema -> EquipoReparacion: Notificar que la inspección ha sido realizada

deactivate Sistema

EquipoReparacion --> Sistema: Consultar detalles de la inspección realizada

activate Sistema

Sistema --> BaseDeDatos: Consultar resultados almacenados de la

inspección

activate BaseDeDatos

BaseDeDatos --> Sistema: Devolver detalles de la inspección

deactivate BaseDeDatos

Sistema --> EquipoReparacion: Mostrar resultados de la inspección

deactivate Sistema

@enduml



<a name="br44"></a> 

**7. UC-0007 Notificar Defectos Graves a Satair Group**

**Código**

@startuml

actor "Equipo de Reparación" as EquipoReparacion

participant Sistema

actor "Satair Group" as SatairGroup

database BaseDeDatos

== Notificar Defectos Graves a Satair Group ==

EquipoReparacion -> Sistema: Solicitar notificación de defectos graves a

Satair Group

activate Sistema

Sistema -> BaseDeDatos: Consultar información de defectos graves

activate BaseDeDatos

Sistema -> SatairGroup: Enviar lista de defectos graves pendientes

deactivate BaseDeDatos

SatairGroup --> Sistema: Confirmar recepción de la lista

activate BaseDeDatos

Sistema -> BaseDeDatos: Marcar defectos como notificados

deactivate BaseDeDatos



<a name="br45"></a> 

loop Revisar y Evaluar Defectos

SatairGroup -> SatairGroup: Revisar y evaluar la gravedad de los defectos

end loop

SatairGroup --> Sistema: Enviar soluciones propuestas para los defectos

activate BaseDeDatos

Sistema -> BaseDeDatos: Registrar soluciones propuestas

deactivate BaseDeDatos

Sistema --> EquipoReparacion: Notificar a Equipo de Reparación sobre las

soluciones propuestas

@enduml

**Proceso de Reparación en Satair Group:**

**1. UC-0001 Recibir Notificación de Defectos Graves**



<a name="br46"></a> 

**Código**

@startuml

actor "Satair Group" as SatairGroup

participant "Sistema" as Sistema

database "Base de Datos" as BaseDeDatos

participant "Personal Técnico" as PersonalTecnico

== Recibir Notificación de Defectos Graves ==

SatairGroup -> Sistema: Recibir notificación de defectos graves

activate Sistema

Sistema -> BaseDeDatos: Procesar notificación y clasificar defectos

activate BaseDeDatos

BaseDeDatos --> Sistema: Confirmar procesamiento

deactivate BaseDeDatos

alt Notificación Grave

Sistema -> PersonalTecnico: Notificar al personal técnico sobre defecto

grave

activate PersonalTecnico

PersonalTecnico -> Sistema: Confirmar recepción de notificación

deactivate PersonalTecnico

else Notificación No Grave



<a name="br47"></a> 

Sistema --> SatairGroup: Confirmar recepción y clasificación

deactivate Sistema

end

@enduml

**2. UC-0002 Evaluar Defectos Graves y Proveer Soluciones**

**Código**

@startuml

actor "Personal Técnico" as PersonalTecnico

participant "Sistema" as Sistema

database "Base de Datos" as BaseDeDatos

participant "Proveedor de Soluciones" as ProveedorSoluciones

== Evaluar Defectos Graves y Proveer Soluciones ==

PersonalTecnico -> Sistema: Analizar informes de defectos graves

activate Sistema

Sistema -> BaseDeDatos: Obtener información detallada de los defectos

activate BaseDeDatos



<a name="br48"></a> 

BaseDeDatos --> Sistema: Devolver información detallada de los defectos

deactivate BaseDeDatos

Sistema -> ProveedorSoluciones: Solicitar opciones de solución

activate ProveedorSoluciones

ProveedorSoluciones --> Sistema: Devolver opciones de solución

deactivate ProveedorSoluciones

Sistema -> PersonalTecnico: Presentar opciones de solución al personal

técnico

activate PersonalTecnico

PersonalTecnico -> Sistema: Seleccionar soluciones apropiadas

deactivate PersonalTecnico

alt Soluciones Seleccionadas

Sistema -> ProveedorSoluciones: Comunicar soluciones seleccionadas

activate ProveedorSoluciones

ProveedorSoluciones -> Sistema: Confirmar soluciones y detalles

adicionales

deactivate ProveedorSoluciones

Sistema --> PersonalTecnico: Confirmar soluciones y proporcionar detalles

deactivate Sistema

else Sin Soluciones Seleccionadas

Sistema --> PersonalTecnico: Informar que no se han seleccionado

soluciones

deactivate Sistema

end

@enduml

**3. UC-0003 Coordinar Envío de Repuestos y Componentes**



<a name="br49"></a> 

**Código**

@startuml

actor "Satair Group" as SatairGroup

participant "Sistema" as Sistema

database "Base de Datos" as BaseDeDatos

participant "Proveedores" as Proveedores

participant "Servicios de Envío" as ServiciosEnvio

== Coordinar Envío de Repuestos y Componentes ==

SatairGroup -> Sistema: Recibir confirmación de soluciones por parte de

Galvatec

activate Sistema

Sistema -> BaseDeDatos: Verificar disponibilidad de repuestos y

componentes

activate BaseDeDatos

BaseDeDatos --> Sistema: Información sobre disponibilidad de repuestos y

componentes

deactivate BaseDeDatos

Sistema -> Proveedores: Coordinar la entrega de repuestos y componentes

activate Proveedores

Proveedores -> Sistema: Confirmar disponibilidad y coordinar la entrega

deactivate Proveedores

Sistema -> ServiciosEnvio: Coordinar servicios de envío para entrega

oportuna



<a name="br50"></a> 

activate ServiciosEnvio

ServiciosEnvio --> Sistema: Confirmar coordinación de entrega

deactivate ServiciosEnvio

Sistema --> SatairGroup: Confirmar coordinación de envío de repuestos y

componentes

deactivate Sistema

@enduml

**4. UC-0004 Registrar Avance en el Sistema de Seguimiento de**

**Reparaciones**

**Código**

@startuml

actor "Satair Group" as SatairGroup

participant "Sistema" as Sistema

database "Base de Datos" as BaseDeDatos

actor "Equipo de Reparación" as EquipoReparacion

== Registrar Avance en el Sistema de Seguimiento de Reparaciones ==

SatairGroup -> Sistema: Recibir confirmación de recepción de repuestos y

componentes

activate Sistema

Sistema -> BaseDeDatos: Actualizar estado de la reparación en el sistema de

seguimiento

activate BaseDeDatos



<a name="br51"></a> 

BaseDeDatos --> Sistema: Confirmar actualización del estado

deactivate BaseDeDatos

Sistema --> SatairGroup: Notificar que el avance ha sido registrado en el

sistema de seguimiento

deactivate Sistema

SatairGroup -> EquipoReparacion: Solicitar información adicional sobre el

avance

activate EquipoReparacion

EquipoReparacion --> SatairGroup: Proporcionar detalles adicionales sobre el

avance

deactivate EquipoReparacion

@enduml

**5. UC-0005 Realizar Pruebas y Verificaciones Post-Reparación**

**Código**

@startuml

actor "Personal Técnico de Satair Group" as TecnicoSatairGroup

participant "Sistema" as Sistema



<a name="br52"></a> 

database "Base de Datos" as BaseDeDatos

== Realizar Pruebas y Verificaciones Post-Reparación ==

TecnicoSatairGroup -> Sistema: Iniciar pruebas y verificaciones

post-reparación

activate Sistema

Sistema -> Sistema: Coordinar y preparar recursos para las pruebas

activate Sistema

Sistema -> BaseDeDatos: Consultar información relevante sobre la

reparación

activate BaseDeDatos

BaseDeDatos --> Sistema: Devolver detalles de la reparación

deactivate BaseDeDatos

Sistema -> TecnicoSatairGroup: Proporcionar detalles y recursos para las

pruebas

deactivate Sistema

TecnicoSatairGroup -> Sistema: Confirmar recepción de detalles y recursos

activate Sistema

Sistema -> Sistema: Realizar pruebas y verificaciones según los estándares

activate Sistema

Sistema --> TecnicoSatairGroup: Notificar resultados de las pruebas

deactivate Sistema

@enduml

**6. UC-0006 Comunicar Finalización de Reparación a Galvatec**



<a name="br53"></a> 

**Código**

@startuml

actor "Personal Técnico de Satair Group" as TecnicoSatairGroup

participant "Sistema" as Sistema

actor "Galvatec" as Galvatec

database "Base de Datos" as BaseDeDatos

== Comunicar Finalización de Reparación a Galvatec ==

TecnicoSatairGroup -> Sistema: Verificar éxito de pruebas y verificaciones

post-reparación

activate Sistema

Sistema -> Sistema: Confirmar éxito de pruebas y verificaciones

activate Sistema

Sistema -> BaseDeDatos: Registrar éxito de pruebas y verificaciones

activate BaseDeDatos

BaseDeDatos --> Sistema: Confirmar registro exitoso

deactivate BaseDeDatos

Sistema -> TecnicoSatairGroup: Autorizar comunicación de finalización

deactivate Sistema

TecnicoSatairGroup -> Galvatec: Comunicar finalización exitosa de la

reparación

activate Galvatec



<a name="br54"></a> 

Galvatec -> Sistema: Confirmar recepción de comunicación

deactivate Galvatec

@enduml

**7. UC-0007 Facturación por Servicios de Reparación**

**Código**

@startuml

actor "Satair Group" as SatairGroup

participant "Sistema" as Sistema

database "Base de Datos" as BaseDeDatos

== Facturación por Servicios de Reparación ==

SatairGroup -> Sistema: Confirmar finalización satisfactoria de la reparación

activate Sistema

Sistema -> Sistema: Generar factura por los servicios de reparación

activate Sistema

Sistema -> BaseDeDatos: Consultar detalles de la reparación y tarifas

aplicables



<a name="br55"></a> 

activate BaseDeDatos

BaseDeDatos --> Sistema: Devolver detalles y tarifas

deactivate BaseDeDatos

Sistema --> SatairGroup: Enviar la factura generada

deactivate Sistema

@enduml

**8. UC-0010 Certificar Reparación Exitosa de Pieza**

**Código**

@startuml

actor "Certificador" as Certificador

participant "Sistema" as Sistema

database "Base de Datos" as BaseDeDatos

actor "Equipo de Reparación Galvatec" as EquipoReparacion

== Certificar Reparación Exitosa de Pieza ==



<a name="br56"></a> 

Certificador -> Sistema: Acceder al sistema y seleccionar opción de

certificación

activate Sistema

Sistema -> Sistema: Presentar resumen ejecutivo de la evaluación de vuelo

Sistema -> Certificador: Mostrar resumen ejecutivo

Certificador -> Sistema: Revisar informes de evaluación de vuelo

Sistema -> BaseDeDatos: Obtener informes de evaluación

activate BaseDeDatos

BaseDeDatos --> Sistema: Devolver informes de evaluación

deactivate BaseDeDatos

Certificador -> Sistema: Notificar problemas identificados (si los hay)

Sistema -> EquipoReparacion: Enviar notificación de problemas y

correcciones requeridas

activate EquipoReparacion

EquipoReparacion --> Sistema: Confirmar recepción de notificación

deactivate EquipoReparacion

Certificador -> Sistema: Certificar reparación como exitosa

Sistema -> Sistema: Generar certificado de reparación

Sistema -> BaseDeDatos: Actualizar estado de la pieza a certificada

activate BaseDeDatos

BaseDeDatos --> Sistema: Confirmar actualización

deactivate BaseDeDatos

@enduml

**9. UC-0011 Coordinar Pruebas en Tierra con Satair Group**

**Código**

@startuml

actor "Inspector Final" as InspectorFinal

participant "Sistema" as Sistema



<a name="br57"></a> 

participant "Satair Group" as SatairGroup

database "Base de Datos" as BaseDeDatos

== Coordinar Pruebas en Tierra con Satair Group ==

InspectorFinal -> Sistema: Solicitar coordinación de pruebas en tierra con

Satair Group

activate Sistema

Sistema -> SatairGroup: Notificar solicitud de coordinación de pruebas en

tierra

activate SatairGroup

SatairGroup -> Sistema: Confirmar disponibilidad y aceptar coordinación

activate Sistema

Sistema -> BaseDeDatos: Consultar información relevante para las pruebas

en tierra

activate BaseDeDatos

BaseDeDatos --> Sistema: Devolver información relevante

deactivate BaseDeDatos

Sistema -> SatairGroup: Enviar detalles de la aeronave y coordinar fechas

para las pruebas

activate SatairGroup

SatairGroup --> Sistema: Confirmar fechas y detalles para las pruebas en

tierra

deactivate SatairGroup

Sistema -> Sistema: Generar plan detallado para las pruebas en tierra

note right: Esto puede incluir listas de verificación,\nrecursos necesarios, y

procedimientos específicos.

Sistema -> InspectorFinal: Notificar detalles y fechas de las pruebas en tierra

activate InspectorFinal

InspectorFinal -> Sistema: Confirmar recepción de la información

deactivate InspectorFinal



<a name="br58"></a> 

Sistema -> Sistema: Notificar al Gestor de Pruebas en Satair Group

activate SatairGroup

note right: Se notifica al Gestor de Pruebas\nsobre la necesidad de realizar

las pruebas.

Sistema <-- SatairGroup: Confirmación de notificación al Gestor de Pruebas

deactivate SatairGroup

@enduml

**Diagramas de operaciones**

**Código:**

@startuml

!define TRANSACTION transaction -\n

!define DATABASE database -\n

class SistemaGalvatec {

\+ IniciarMantenimiento(clienteId: String, aeronaveId: String, detallesAeronave:

String): void

\+ guardarInspeccion(detallesInspeccion: String, resultadosInspeccion: String): void

\+ eliminarProceso(key: String): void



<a name="br59"></a> 

\+ obtenerProcesosMantenimiento(): Array<Object>

\+ notificarDefectosGraves(listaDefectosGraves: String, fecha: String,

numeroSolicitud: String): void

\+ guardarInformacion(equipoReparacion: String, detallesAeronave: String): void

\+ actualizarInformacionContacto(nuevaInformacion: String): void

}

class SatairGroup {

\+ registrarResultados(coordinarRecursos: boolean, detallesReparacion: String,

realizarPruebas: boolean, resultadosPruebas: String): void

\+ obtenerNotificacionesGalvatec(): Array<Object>

\+ registrarAvance(confirmacionRecepcion: boolean, detallesAvance: String): void

\+ generarFactura(confirmarFinalizacion: boolean, detallesFacturacion: String): void

\+ enviarEvaluacion(numeroSolicitud: String, informeEvaluacion: String,

opcionesSolucion: String): void

\+ coordinarPruebas(detallesAeronave: String, fechasPruebas: date, planDetallado:

String): void

\+ coordinarEnvio(confirmacionGalvatec: boolean, detallesAeronave: String,

fechasEnvio: date): void

\+ comunicarFinalizacion(verificarExitoPruebas: boolean, autorizarComunicacion:

boolean, detallesFinalizacion: String): void

\+ certificarReparacion(revisionVuelo: String, problemasIdentificados: String,

certificacionExitosa: boolean): void

}

@enduml



<a name="br60"></a> 

**Galvatec**

IniciarMantenimiento(clienteId: String, aeronaveId: String, detallesAeronave:

String): void

guardarInspeccion(

detallesInspeccion: String,

resultadosInspeccion: String

) : void

eliminarProceso(key: String): void

obtenerProcesosMantenimiento(): Array<Object>

notificarDefectosGraves(

listaDefectosGraves: String,

fecha: String,

numeroSolicitud: String

): void

guardarInformacion(

equipoReparacion: String,

detallesAeronave: String

): void

actualizarInformacionContacto(

nuevaInformacion: String

): void

**Satair Group**

registrarResultados

(

coordinarRecursos: boolean,

detallesReparacion: string,

realizarPruebas: boolean,

resultadosPruebas: string

):void



<a name="br61"></a> 

obtenerNotificacionesGalvatec(): Array<Object>

registrarAvance

(

confirmacionRecepcion:boolean,

detallesAvance:string

): void

generarFactura

(

confirmarFinalizacion:boolean,

detallesFacturacion:string

): void

enviarEvaluacion

(

numeroSolicitud: string,

informeEvaluacion: string,

opcionesSolucion: string

): void

coordinarPruebas

(

detallesAeronave: string,

fechasPruebas: date,

planDetallado: string

): void

coordinarEnvio

(

confirmacionGalvatec: boolean,

detallesAeronave: string,

fechasEnvio: date



<a name="br62"></a> 

): void

comunicarFinalizacion

(

verificarExitoPruebas: boolean,

autorizarComunicacion: boolean,

detallesFinalizacion: string

): void

certificarReparacion

(

revisionVuelo: string,

problemasIdentificados: string,

certificacionExitosa: boolean

): void



<a name="br63"></a> 

**Matriz de Trazabilidad Requisitos Funcionales vs. Actores**

● Act-007: Cliente o Usuario Inicial

● Act-008: Equipo de Reparación

● Act-009: Mecánicos y Técnicos de Mantenimiento

● Act-010: Gestores de Reparación (Satair Group)

● Act-011: Suministro de Repuestos

● Act-012: Reparación de Componentes

● Act-013: Inspector Final

● Act-014: Gestor de Pruebas

● Act-015: Piloto de Prueba

● Act-016: Certiﬁcador



<a name="br64"></a> 

Interfaces de usuario Galvatec

Incio Sesion Galvatec

Act-

007

Act-0 Act-

Act- Act-

Act- Act-

Act- Act-

014 015

Act-0

16

08

009

010

011

012

013

X

X

X

X

X

X

X

X

X

X

X

X

X

X

X

X

Inicio Sesión Satair Group

X

X

X

X

X

X

X

Actualizar Información de Contacto

X

Cancelar Mantenimiento

Consultar Estado de Mantenimiento

X

X

X

X

X

X

X

X

X

X

X

X

X

X

X

X

Iniciar Proceso de Mantenimiento

Realizar Inspección Inicial

X

X

X

X

X

X

X

X

Listado de Procesos de Mantenimiento

Notiﬁcar Defectos Graves

Recopilar Información

**Diagrama de Navegación**

**Diagrama de navegación - Galvatec**



<a name="br65"></a> 

**Diagrama de navegación - Satair Group**

**Código UML**

@startuml

!define RECTANGLE class

package "Galvatec - Proceso de Mantenimiento" {

RECTANGLE PáginaInicio {

ConsultarEstadoMantenimiento

ActualizarInfoContacto

CancelarMantenimiento

RecopilarInformacion

RealizarInspeccionInicial

NotificarDefectosSatairGroup

}

RECTANGLE IniciarProcesoMantenimiento {

\+ iniciarProceso()

}

RECTANGLE ConsultarEstadoMantenimiento {

\+ consultarEstado()

}

RECTANGLE ActualizarInfoContacto {

\+ actualizarInfoContacto()



<a name="br66"></a> 

}

RECTANGLE CancelarMantenimiento {

\+ cancelarMantenimiento()

}

RECTANGLE RecopilarInformacion {

\+ recopilarInformacion()

}

RECTANGLE RealizarInspeccionInicial {

\+ realizarInspeccion()

}

RECTANGLE NotificarDefectosSatairGroup {

\+ notificarDefectos()

}

RECTANGLE ListadoProcesosMantenimiento {

\+ verListadoProcesos()

}

RECTANGLE ListadoCancelarMantenimiento {

\+ verListadoCancelar()

}

}

package "Satair Group - Proceso de Reparación" {

RECTANGLE PáginaInicioSatairGroup {

RecibirNotificacionDefecto

EvaluarDefectosProveerSoluciones

CoordinarEnvioRepuestos

RegistrarAvance

RealizarPruebasVerificaciones

ComunicarFinalizacionGalvatec

FacturacionServiciosReparacion

CertificarReparacionExitosa

}

RECTANGLE RecibirNotificacionDefecto {



<a name="br67"></a> 

\+ recibirNotificacion()

}

RECTANGLE EvaluarDefectosProveerSoluciones {

\+ evaluarDefectos()

\+ proveerSoluciones()

}

RECTANGLE CoordinarEnvioRepuestos {

\+ coordinarEnvio()

}

RECTANGLE RegistrarAvance {

\+ registrarAvance()

}

RECTANGLE RealizarPruebasVerificaciones {

\+ realizarPruebas()

}

RECTANGLE ComunicarFinalizacionGalvatec {

\+ comunicarFinalizacion()

}

RECTANGLE FacturacionServiciosReparacion {

\+ generarFactura()

}

RECTANGLE CertificarReparacionExitosa {

\+ certificarReparacion()

}

}

PáginaInicio --> IniciarProcesoMantenimiento

PáginaInicio --> ConsultarEstadoMantenimiento

PáginaInicio --> ActualizarInfoContacto

PáginaInicio --> CancelarMantenimiento

PáginaInicio --> RecopilarInformacion

PáginaInicio --> RealizarInspeccionInicial

PáginaInicio --> NotificarDefectosSatairGroup



<a name="br68"></a> 

ConsultarEstadoMantenimiento --> ListadoProcesosMantenimiento

CancelarMantenimiento --> ListadoCancelarMantenimiento

NotificarDefectosSatairGroup -->RecibirNotificacionDefecto

PáginaInicioSatairGroup --> RecibirNotificacionDefecto

PáginaInicioSatairGroup --> EvaluarDefectosProveerSoluciones

PáginaInicioSatairGroup --> CoordinarEnvioRepuestos

PáginaInicioSatairGroup --> RegistrarAvance

PáginaInicioSatairGroup --> RealizarPruebasVerificaciones

PáginaInicioSatairGroup --> ComunicarFinalizacionGalvatec

PáginaInicioSatairGroup --> FacturacionServiciosReparacion

PáginaInicioSatairGroup --> CertificarReparacionExitosa

@enduml

\*\*Método ejemplo:\*\* listarSolicitudesMantenimiento(): ArrayList

\*\*Descripción:\*\*

Este método se encarga de recuperar y listar las solicitudes de mantenimiento almacenadas

en la base de datos.

Devuelve un ArrayList que contiene la información de las solicitudes recuperadas.

La operación principal es realizar una consulta \*\*GET\*\* a la base de datos para obtener la

lista de solicitudes.

La estructura de datos devuelta permite el manejo fácil de la información para su

presentación o procesamiento adicional en la interfaz del sistema.

\*\*Flujo General:\*\*

El sistema sigue un modelo de solicitud-respuesta, donde los formularios se crean utilizando

un enfoque de \*\*POST\*\* para enviar datos a la base de datos.

La recuperación de información se realiza por ejemplo mediante el método

listarSolicitudesMantenimiento, que utiliza un enfoque \*\*GET\*\* para obtener datos

almacenados en la base de datos. La conexión se haria a la base de datos Firebase

Realtime Database, la construcción consultas, y la manipulación de datos tanto para la

creación y eliminacion (\*\*DELETE\*\*) como para la recuperación.


# Matriz inicial de riesgos de sistemas

**Integrante:** Luis Fernando Restrepo Holguin

## 1. Caso y contexto actualizado

La organización seleccionada es un negocio familiar dedicado a la comercialización de productos cárnicos, principalmente carne de cerdo, pollo y chorizos. Sus actividades incluyen la recepción, el pesaje, el transporte y la distribución de la mercancía, así como el registro de clientes, ventas, pagos y deudas.

La empresa cuenta con un sistema de información para apoyar el registro y control de sus operaciones. Sin embargo, su uso es limitado: está instalado en un solo computador y a los propietarios se les dificulta acceder y utilizarlo. Por esta razón, parte de la información también puede continuar manejándose de forma manual. El sistema requiere cuentas y contraseñas, y está pendiente verificar cómo se administran los accesos y cómo se identifican las modificaciones realizadas.

También se debe comprobar si los respaldos permiten recuperar la información, qué mantenimiento recibe el sistema y cómo se atienden los errores. Al estar disponible únicamente desde un computador, el acceso desde otros dispositivos es limitado.

Para esta matriz se analizarán el uso y la disponibilidad del sistema, la conservación de la información comercial, el control de acceso y las modificaciones, el mantenimiento y la atención de errores, así como la verificación del peso de la mercancía y la continuidad del transporte y las entregas.

## 2. Activos y procesos evaluados

1. **Sistema de información y computador:** el sistema apoya el registro y control de las operaciones, pero está instalado en un solo equipo y su uso por parte de los propietarios es limitado.

2. **Registros comerciales manuales:** incluyen cuadernos con información relacionada con clientes, ventas, pagos y deudas. Son importantes para consultar y reconstruir las operaciones.

3. **Cuentas, contraseñas y trazabilidad:** mecanismos que regulan el acceso al sistema y permiten revisar quién consulta o modifica la información y cuándo lo hace.

4. **Respaldos y mantenimiento del sistema:** procesos necesarios para conservar y recuperar los datos, mantener el sistema operativo y atender errores.

5. **Recepción, pesaje, transporte y entrega de productos:** actividades de verificación de la mercancía y traslado de los pedidos hasta su entrega al cliente.

## 3. Supuestos y aspectos pendientes de verificar

* **S-01. Uso y disponibilidad del sistema:** el negocio cuenta con un sistema instalado en un solo computador, pero su uso es limitado debido a las dificultades de acceso y manejo de los propietarios. Está pendiente determinar qué información se registra en el sistema y cuál se lleva manualmente, y qué alternativas existen cuando el equipo no está disponible.

* **S-02. Conservación y recuperación de la información:** se utilizan dos cuadernos distribuidos entre dos personas y la información no siempre se copia en ambos. También falta verificar si se realizan respaldos del sistema, con qué frecuencia y si es posible recuperar los datos mediante una prueba.

* **S-03. Acceso y trazabilidad:** el sistema requiere cuentas y contraseñas. Está pendiente verificar quién tiene credenciales, cómo se protegen y si el sistema permite identificar quién consultó o modificó los registros y cuándo. También se debe revisar cómo se controlan las consultas y correcciones en los cuadernos.

* **S-04. Exactitud, mantenimiento y errores:** las deudas siempre se anotan, pero falta comprobar cómo se revisa la exactitud de las ventas, los pagos, los saldos y las correcciones. También se debe confirmar qué mantenimiento recibe el sistema y cómo se reportan y atienden los errores.

* **S-05. Control de mercancía y continuidad logística:** la mercancía se pesa al salir, al llegar y antes de entregarla al cliente, y los pesos se anotan en el cuaderno. Falta comprobar cómo se comparan los registros, cómo se investigan las diferencias y si existe un procedimiento para atender retrasos, ausencia de la persona encargada u otras interrupciones de las entregas.

## 4. Matriz inicial de riesgos

La probabilidad y el impacto se valoran provisionalmente en una escala de 1 a 5. El nivel se calcula multiplicando ambos valores. Para este ejercicio se propone la siguiente clasificación: de 1 a 4, bajo; de 5 a 9, moderado; de 10 a 16, alto; y de 17 a 25, crítico.

Estas valoraciones son iniciales y deben revisarse según la evidencia disponible; no representan incidentes confirmados.

| ID | Activo o proceso | Amenaza | Vulnerabilidad | Riesgo | Prob. | Impacto | Nivel | Control actual o evidencia | Control propuesto | Justificación |
| --- | --- | --- | --- | --- | ---: | ---: | --- | --- | --- | --- |
| R-01 | Sistema de información, computador y registro de operaciones | Indisponibilidad del equipo o uso incompleto del sistema. | El sistema está instalado en un solo computador y los propietarios tienen dificultades para utilizarlo. Parte de la información podría seguir registrándose manualmente y el acceso desde otros dispositivos es limitado. | Una falla del computador o el uso irregular del sistema podría impedir consultar o registrar oportunamente las operaciones y generar información incompleta o duplicada. | 4 | 5 | 20 (Crítico) | Se cuenta con el sistema instalado en un computador, pero su uso es limitado. Está pendiente identificar qué operaciones se registran en el sistema y cuáles por otros medios. | Documentar los pasos básicos de uso, orientar a los usuarios y definir cómo continuar el registro de operaciones cuando el sistema o el computador no estén disponibles. | La dependencia de un solo equipo y las dificultades de uso pueden afectar tanto la disponibilidad como la actualidad de la información. La valoración es provisional y debe revisarse con evidencia. |
| R-02 | Cuadernos, registros comerciales y respaldos del sistema | Pérdida, daño o imposibilidad de recuperar la información. | La información está distribuida entre cuadernos que no siempre contienen los mismos datos. No se ha comprobado la frecuencia ni la recuperación de los respaldos del sistema. | La pérdida o daño de un cuaderno, del computador o de los datos podría dejar incompletos los registros de ventas, pagos y deudas, dificultando la reconstrucción de las operaciones. | 4 | 5 | 20 (Crítico) | Se utilizan dos cuadernos distribuidos entre dos personas; no siempre contienen la misma información. La existencia y recuperación de respaldos digitales está pendiente de verificar. | Mantener una copia actualizada de los registros importantes, definir una rutina de respaldos en un medio separado del computador y probar periódicamente la recuperación de la información. | La falta de copias completas y verificadas puede dificultar la recuperación de operaciones y saldos. La valoración es provisional hasta revisar la evidencia disponible. |
| R-03 | Información de clientes y operaciones en el sistema y los cuadernos | Acceso o modificación no autorizada, o errores en los registros. | No se ha verificado quién tiene cuentas, cómo se protegen las contraseñas ni si el sistema registra accesos y cambios. Tampoco se ha confirmado cómo se documentan las correcciones en los cuadernos. | La información podría consultarse o modificarse sin autorización, o una venta, deuda o abono podría registrarse incorrectamente sin que el cambio se detecte oportunamente. | 3 | 5 | 15 (Alto) | El sistema requiere cuentas y contraseñas. Dos personas manejan los cuadernos y revisan la trazabilidad de los datos; falta confirmar el alcance de estos controles. | Definir usuarios autorizados y permisos, proteger las contraseñas, registrar las operaciones con sus datos básicos y documentar las correcciones sin eliminar la información original. | El control de acceso y la revisión de los registros ayudan a proteger la confidencialidad e integridad de la información comercial. La valoración es provisional. |
| R-04 | Sistema de información, computador y soporte | Errores técnicos o fallas prolongadas. | No se ha confirmado qué mantenimiento recibe el sistema ni cómo se reportan, documentan y corrigen los errores. | Un error no atendido o una falla del sistema podría interrumpir su uso o afectar la precisión y disponibilidad de los registros comerciales. | 3 | 4 | 12 (Alto) | Está pendiente revisar los registros de mantenimiento, errores y solicitudes de ayuda. | Registrar errores y mantenimientos, asignar responsables para su atención y conservar evidencia de las correcciones realizadas. | El seguimiento permite identificar fallas recurrentes y reducir el tiempo de interrupción. La probabilidad es provisional porque no se cuenta con un historial revisado. |
| R-05 | Recepción, pesaje, transporte y entrega de productos | Diferencias de peso, pérdida, deterioro o retrasos durante el transporte. | Aunque los pesos se anotan en el cuaderno en distintas etapas, falta comprobar cómo se comparan e investigan las diferencias. No se ha confirmado si hay un procedimiento para registrar incidentes o responder a interrupciones logísticas. | Una diferencia de peso, pérdida, deterioro o retraso podría generar pérdidas económicas y afectar la entrega de los productos si no se identifica y gestiona adecuadamente. | 3 | 4 | 12 (Alto) | Se pesa la mercancía al salir, al llegar al establecimiento y antes de entregarla al cliente. La empresa cuenta con una persona encargada del transporte; está pendiente verificar cómo se registran y gestionan los incidentes. | Comparar los pesos de cada etapa, documentar e investigar las diferencias y establecer cómo registrar incidentes y reorganizar las entregas afectadas. | El pesaje en varias etapas puede ayudar a detectar diferencias, mientras que un procedimiento de incidentes apoyaría la continuidad de las entregas. La valoración es provisional. |

## 5. Conclusión

La matriz identifica cinco riesgos principales relacionados con el uso y la disponibilidad del sistema, la conservación y recuperación de la información, el acceso y la exactitud de los registros, el mantenimiento y la atención de errores, y el control de la mercancía durante el transporte y la entrega.

Las valoraciones son iniciales y deben ajustarse si la revisión del sistema, los cuadernos, las entrevistas o la observación del trabajo aportan nueva evidencia. Los controles propuestos buscan reducir los riesgos identificados y fortalecer tanto el uso del sistema de información como los procedimientos actuales del negocio.

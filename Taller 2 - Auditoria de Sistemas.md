# Matriz inicial de riesgos de sistemas

**Integrante:** Luis Fernando Restrepo Holguin

## 1. Caso y contexto actualizado

La organización seleccionada es un negocio familiar dedicado a la comercialización de productos cárnicos, principalmente carne de cerdo, pollo y chorizos. Sus actividades incluyen la recepción, el pesaje, el transporte y la distribución de la mercancía, así como el registro de clientes, ventas, pagos y deudas.

La empresa cuenta con un sistema de información para apoyar el registro y control de sus operaciones. Sin embargo, su uso es limitado: está instalado en un solo computador y a los propietarios se les dificulta acceder y utilizarlo. Por esta razón, parte de la información también puede continuar manejándose de forma manual. El sistema requiere cuentas y contraseñas, y está pendiente verificar cómo se administran los accesos y cómo se identifican las modificaciones realizadas.

También se debe comprobar si los respaldos permiten recuperar la información, qué mantenimiento recibe el sistema y cómo se atienden los errores. Al estar disponible únicamente desde un computador, el acceso desde otros dispositivos es limitado.

Para esta matriz se analizarán los procesos de registro y conservación de la información comercial, control de ventas y deudas, protección de los datos de clientes, disponibilidad y uso del sistema, verificación del peso de la mercancía y continuidad del transporte y las entregas.

## 2. Activos y procesos evaluados

1. **Sistema de información y computador:** el sistema apoya el registro y control de las operaciones, pero está instalado en un solo equipo y su uso por parte de los propietarios es limitado.

2. **Registros comerciales manuales:** incluyen cuadernos con información relacionada con clientes, ventas, pagos y deudas. Son importantes para consultar y reconstruir las operaciones.

3. **Registro de ventas, pagos y deudas:** proceso mediante el cual se anotan las ventas, las obligaciones pendientes de los clientes y los abonos recibidos, tanto en el sistema como en los medios manuales que se utilicen.

4. **Cuentas, contraseñas y trazabilidad:** mecanismos que regulan el acceso al sistema y permiten revisar quién consulta o modifica la información y cuándo lo hace.

5. **Respaldos y mantenimiento del sistema:** procesos necesarios para conservar y recuperar los datos, mantener el sistema operativo y atender errores.

6. **Información de clientes y registros comerciales:** incluye los datos de los clientes y la información de sus compras y obligaciones, cuyo acceso y modificación deben manejarse adecuadamente.

7. **Recepción, pesaje y entrega de productos:** proceso de verificación de la mercancía mediante el pesaje en el punto de partida, al llegar al establecimiento y antes de entregarla al cliente.

8. **Transporte y entrega de pedidos:** servicio logístico necesario para trasladar los productos y atender los pedidos de los clientes.

## 3. Supuestos y aspectos pendientes de verificar

* **S-01. Uso del sistema:** el negocio cuenta con un sistema de información instalado en un solo computador, pero su uso es limitado debido a las dificultades de acceso y manejo de los propietarios. Está pendiente determinar qué información se registra en el sistema y cuál se lleva manualmente.

* **S-02. Conservación de los registros:** se utilizan dos cuadernos distribuidos entre dos personas. La información no siempre se copia en ambos, por lo que no se ha confirmado que exista una copia completa e independiente de todos los registros.

* **S-03. Verificación de las operaciones:** las deudas siempre se anotan; sin embargo, falta comprobar cómo se revisa la exactitud de las ventas, los pagos, los saldos y las correcciones, tanto en el sistema como en los cuadernos.

* **S-04. Acceso y modificaciones:** el sistema requiere cuentas y contraseñas. Está pendiente verificar quién tiene credenciales, cómo se protegen y si el sistema permite identificar quién consultó o modificó los registros y cuándo. Dos personas manejan los cuadernos y revisan la trazabilidad de los datos.

* **S-05. Respaldos y recuperación:** está pendiente verificar si se realizan copias de seguridad, con qué frecuencia y dónde se conservan. También se debe comprobar mediante una prueba si permiten recuperar la información.

* **S-06. Mantenimiento y errores:** falta confirmar qué mantenimiento recibe el sistema y el computador, qué errores se han presentado y cómo se reportan o solucionan.

* **S-07. Acceso desde otros dispositivos:** el sistema está instalado en un solo computador. Está pendiente confirmar si existe alguna forma autorizada de consultar o utilizar la información desde otros dispositivos.

* **S-08. Control de los pesos:** la mercancía se pesa al salir, al llegar y antes de entregarla al cliente, y los pesos se anotan en el cuaderno. Falta comprobar cómo se comparan los registros y cómo se documentan e investigan las diferencias.

* **S-09. Continuidad logística:** no se ha confirmado si existe un procedimiento para registrar incidentes de transporte, retrasos, ausencia de la persona encargada o interrupciones que puedan afectar las entregas.

## 4. Matriz inicial de riesgos

La probabilidad y el impacto se valoran provisionalmente en una escala de 1 a 5. El nivel se calcula multiplicando ambos valores. Para este ejercicio se propone la siguiente clasificación: de 1 a 4, bajo; de 5 a 9, moderado; de 10 a 16, alto; y de 17 a 25, crítico.

Estas valoraciones son iniciales y deben revisarse según la evidencia disponible; no representan incidentes confirmados.

| ID | Activo o proceso | Amenaza | Vulnerabilidad | Riesgo | Prob. | Impacto | Nivel | Control actual o evidencia | Control propuesto | Justificación |
| --- | --- | --- | --- | --- | ---: | ---: | --- | --- | --- | --- |
| R-01 | Cuadernos con registros comerciales | Pérdida, daño o extravío de los registros. | La información se distribuye entre dos cuadernos y no siempre se copia en ambos. No se ha identificado una copia completa e independiente. | Los registros de ventas, pagos y deudas podrían perderse o quedar incompletos si se extravía o deteriora el cuaderno que contiene información necesaria para reconstruir las operaciones. | 4 | 5 | 20 (Crítico) | Se utilizan dos cuadernos distribuidos entre dos personas; no siempre contienen la misma información. | Definir un procedimiento para conservar los registros y mantener una copia de respaldo actualizada de la información importante, verificando periódicamente que esté completa y legible. | La pérdida de registros únicos podría dificultar la reconstrucción de operaciones y saldos. La probabilidad es provisional porque no se dispone de datos sobre incidentes anteriores. |
| R-02 | Registro de ventas, pagos y deudas | Error humano al registrar o actualizar una operación. | Aunque las deudas siempre se anotan, no se ha verificado cómo se comprueba la exactitud de los registros ni cómo se documentan las correcciones en el sistema o en los cuadernos. | Una venta, deuda o abono podría registrarse incorrectamente o actualizarse de manera equivocada, generando diferencias en los saldos de los clientes. | 3 | 5 | 15 (Alto) | Las deudas se registran por escrito y dos personas manejan los cuadernos para revisar la trazabilidad de los datos. El sistema existe, pero su uso es limitado. | Registrar cada venta, deuda y abono con fecha, cliente, valor y saldo actualizado; documentar las correcciones sin eliminar la información original y realizar revisiones periódicas. | Los errores pueden afectar directamente las cuentas y generar desacuerdos con los clientes. La probabilidad deberá ajustarse después de revisar cómo se verifican actualmente las operaciones. |
| R-03 | Sistema de información y computador | Falla, daño o indisponibilidad del equipo. | El sistema está instalado en un solo computador y el acceso desde otros dispositivos es limitado. | Si el computador falla, se daña o no está disponible, los propietarios podrían perder temporalmente el acceso al sistema y a la información necesaria para operar. | 3 | 5 | 15 (Alto) | Se cuenta con el sistema instalado en un computador; falta verificar cómo se mantiene y qué alternativa existe ante la indisponibilidad del equipo. | Definir cómo continuar el registro de operaciones ante una falla y establecer medidas para mantener disponible una copia recuperable de la información. | La dependencia de un solo equipo concentra el acceso al sistema y puede afectar la continuidad del negocio. La valoración es provisional y debe revisarse con evidencia técnica. |
| R-04 | Uso del sistema por parte de los propietarios | Errores u omisiones por dificultades de acceso o manejo. | Los propietarios tienen dificultades para utilizar el sistema, por lo que su uso es limitado y algunos registros podrían llevarse manualmente. | Las operaciones podrían quedar incompletas, duplicarse o registrarse con retraso si el sistema no se utiliza de manera constante. | 4 | 4 | 16 (Alto) | Se conoce que el sistema existe, pero su uso es limitado; falta identificar qué operaciones se ingresan en él y cuáles se registran por otros medios. | Documentar los pasos básicos de uso, brindar orientación a los usuarios y definir qué registros deben mantenerse actualizados en el sistema. | Las dificultades de uso pueden afectar la integridad y actualidad de la información. La probabilidad debe confirmarse al comparar los registros del sistema y los manuales. |
| R-05 | Respaldos y recuperación del sistema | Pérdida de información ante daño, error o incidente. | No se ha verificado si los respaldos se realizan periódicamente ni si es posible restaurarlos correctamente. | La empresa podría no recuperar los registros del sistema después de una falla, pérdida o daño de la información. | 3 | 5 | 15 (Alto) | Está pendiente verificar la existencia, frecuencia y ubicación de los respaldos y comprobar su restauración. | Establecer una rutina de respaldos, conservar copias en un medio separado del computador y realizar pruebas periódicas de recuperación. | Un respaldo no comprobado podría no servir cuando se necesite recuperar la información. La valoración es provisional hasta revisar la evidencia. |
| R-06 | Cuentas, contraseñas y trazabilidad | Acceso o modificación no autorizada de la información. | No se ha verificado quién tiene cuentas, cómo se protegen las contraseñas ni si el sistema registra accesos y cambios. | Una persona podría consultar o alterar información comercial sin autorización o sin que sea posible identificar oportunamente lo ocurrido. | 3 | 4 | 12 (Alto) | El sistema requiere cuentas y contraseñas; falta confirmar cómo se administran y qué registros de actividad conserva. | Definir usuarios autorizados, proteger las contraseñas, limitar los permisos según las funciones y revisar los registros de cambios disponibles. | Los controles de acceso y la trazabilidad ayudan a proteger la confidencialidad e integridad de los datos. La valoración es provisional hasta comprobar las funciones del sistema. |
| R-07 | Mantenimiento y soporte del sistema | Errores técnicos o fallas prolongadas. | No se ha confirmado qué mantenimiento recibe el sistema ni cómo se reportan y corrigen sus errores. | Un error no atendido podría interrumpir el uso del sistema o afectar la precisión y disponibilidad de los registros. | 3 | 4 | 12 (Alto) | Está pendiente revisar los registros de mantenimiento, errores y solicitudes de ayuda. | Registrar los errores y mantenimientos, asignar responsables para su atención y conservar evidencia de las correcciones realizadas. | El seguimiento permite identificar fallas recurrentes y reducir el tiempo de interrupción. La probabilidad es provisional porque no se cuenta con un historial revisado. |
| R-08 | Información de clientes y registros comerciales | Consulta o modificación no autorizada de la información. | No se ha verificado qué restricciones existen para consultar los cuadernos ni cómo se identifican las modificaciones en ellos o en el sistema. | Una persona no autorizada podría consultar información comercial o modificar una anotación sin que el cambio se detecte oportunamente. | 3 | 3 | 9 (Moderado) | Los registros se distribuyen entre dos personas, que pueden revisar la trazabilidad de los datos. El control de acceso al sistema está pendiente de verificar. | Definir quién está autorizado para consultar y modificar los registros, conservarlos en un lugar adecuado e identificar y justificar las correcciones realizadas. | La información comercial debe conservar su confidencialidad e integridad. La valoración es provisional porque todavía no se conocen todas las restricciones actuales de acceso. |
| R-09 | Recepción, pesaje y entrega de productos | Diferencias de peso, pérdida o deterioro durante el transporte. | Aunque los pesos se anotan en el cuaderno, falta comprobar cómo se comparan los registros y cómo se investigan las diferencias. | Una diferencia de peso o un deterioro podría generar pérdidas económicas o desacuerdos si no se identifica y documenta adecuadamente lo sucedido. | 2 | 4 | 8 (Moderado) | Se pesa la mercancía al salir, al llegar al establecimiento y antes de entregarla al cliente; los pesos se anotan en el cuaderno. | Comparar los pesos registrados en cada etapa y documentar cualquier diferencia, pérdida o deterioro, incluyendo su revisión y resultado. | El pesaje en varias etapas es un control existente que puede ayudar a detectar diferencias. La probabilidad asignada es provisional y debe contrastarse con los registros disponibles. |
| R-10 | Transporte y entrega de pedidos | Retrasos u otros incidentes que afecten la distribución. | No se ha verificado si existe un procedimiento definido para registrar incidentes y mantener las entregas ante una interrupción. | Un retraso o la ausencia de la persona encargada podría afectar la entrega de los productos y dificultar la continuidad del servicio. | 3 | 4 | 12 (Alto) | La empresa cuenta con una persona encargada del transporte; está pendiente verificar cómo se registran y gestionan los incidentes logísticos. | Establecer un procedimiento para registrar incidentes, asignar responsables y determinar cómo continuar o reorganizar las entregas afectadas. | La interrupción del transporte puede afectar el cumplimiento de los pedidos y la atención a los clientes. La probabilidad es provisional porque no se ha revisado el historial de incidentes. |

## 5. Conclusión

La matriz identifica riesgos relacionados con la conservación de los registros comerciales, la exactitud de ventas y deudas, la protección de la información, la disponibilidad y el uso limitado del sistema, el acceso mediante cuentas y contraseñas, la verificación de respaldos, el mantenimiento y los errores, el control del peso de los productos y la continuidad de las entregas.

Las valoraciones son iniciales y deben ajustarse si la revisión del sistema, los cuadernos, las entrevistas o la observación del trabajo aportan nueva evidencia. Los controles propuestos buscan reducir los riesgos identificados y fortalecer tanto el uso del sistema de información como los procedimientos actuales del negocio.

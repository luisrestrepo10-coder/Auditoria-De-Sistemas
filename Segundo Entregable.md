# Taller: del riesgo priorizado al plan de auditoría

**Asignatura:** Auditoría de Sistemas (ET0114)  
**Auditor:** Luis Fernando Restrepo Holguin  

> **Nota sobre confidencialidad:** Este documento es una propuesta académica de auditoría. No incluye nombres, direcciones ni registros reales de clientes. La evidencia descrita es la que se solicitaría en una auditoría autorizada; no ha sido obtenida ni examinada para este taller.

## 1. Contexto y riesgo seleccionado

La organización del caso es un negocio familiar dedicado a la comercialización de productos cárnicos. Durante el periodo analizado utilizó un sistema de información instalado en un solo computador. El sistema registraba el nombre y la dirección del cliente, el pedido y su valor. Según la información disponible, se utilizó desde el 12 de mayo hasta el 30 de junio de 2026.

Se reporta que el último respaldo o exportación se realizó el 26 de junio de 2026 y que se cree que el archivo existe, aunque no se conoce su ubicación. También se informó que no hay un procedimiento escrito sobre respaldos y que no se ha corroborado la existencia de otra copia posterior. Estos datos son declaraciones del caso y están pendientes de verificación.

Se selecciona el **riesgo R-02** de la matriz vigente:

| Elemento | Descripción |
|---|---|
| **Activo o proceso** | Registros comerciales y respaldos del sistema de información. |
| **Amenaza** | Pérdida, daño o imposibilidad de recuperar la información. |
| **Vulnerabilidad** | No se ha corroborado la ubicación ni la recuperación del último respaldo. No se reporta un procedimiento escrito de respaldos. |
| **Consecuencia posible** | Pérdida o falta de disponibilidad de información de clientes y pedidos, lo que dificultaría reconstruir las operaciones. |
| **Valoración de la matriz** | Probabilidad 4; impacto 5; nivel 20 (crítico), valoración provisional de la matriz. |
| **Control reportado** | Se habría realizado una exportación o respaldo el 26 de junio. Su existencia, cobertura y recuperación están por comprobar. |

Se prioriza este riesgo porque la información respalda operaciones comerciales y contiene datos de clientes. Además, se cuenta con una fecha de respaldo reportada y un periodo de uso del sistema que permiten diseñar procedimientos concretos. El puntaje ayuda a priorizarlo, pero la relevancia para el negocio y la posibilidad de contrastar la evidencia también sustentan la elección.

## 2. Objetivo de auditoría

**Evaluar si el proceso de respaldo de la información del sistema está definido y opera de manera confiable para proteger y recuperar íntegramente los datos necesarios para las operaciones del negocio, considerando el volumen y crecimiento de la información, la frecuencia de las copias, su almacenamiento y conservación, el control de acceso y las pruebas de restauración; identificar brechas en los respaldos disponibles y posibles pérdidas de información.**

El objetivo plantea una condición que podría evaluarse con evidencia en una auditoría autorizada. No afirma que el respaldo exista, que esté completo o que pueda recuperarse.

## 3. Alcance funcional

- **Proceso:** gestión de respaldos de principio a fin: definición de necesidades, creación, frecuencia, cobertura, capacidad y ubicación del almacenamiento, conservación, control de acceso y recuperación de la información.

- **Sistema o componentes:** sistema de información de ventas, computador donde se encuentra instalado y medio o servicio utilizado para guardar las copias. El nombre del sistema y el medio de almacenamiento están por confirmar.

- **Información incluida:** registros de clientes y pedidos que el sistema maneja, como nombre, dirección, pedido y valor. En una auditoría real, se protegerían los datos personales; en el trabajo académico no se incluirán datos identificables.

- **Población:** respaldos, exportaciones, configuraciones y registros de ejecución relacionados con el sistema, además de los datos necesarios para evaluar la cobertura y el volumen de información. La cantidad de elementos se establecería al conocer el inventario disponible.

- **Periodo:** etapa de uso del sistema, del 12 de mayo al 30 de junio de 2026. Dentro de ese periodo se revisaría el respaldo reportado del 26 de junio y se evaluaría si la información del sistema hasta el último día de uso quedó cubierta. Este intervalo delimita el caso; el objetivo evalúa el proceso de respaldos en general.

- **Responsables o fuentes de información:** jefe o propietario del negocio, custodio actual del sistema o de los archivos y responsable de administrar el sistema. La antigua encargada podría ser una fuente si estuviera disponible y la empresa autorizara consultarla. Los nombres no se incluirán.

- **Incluye:** revisión de cómo se definen la frecuencia y la cobertura de los respaldos; capacidad y ubicación de almacenamiento; conservación y acceso a las copias; evidencia de su ejecución; características del último respaldo reportado; y una prueba controlada de recuperación, si se autorizara en una auditoría real.

- **Excluye:** auditoría general de todos los controles tecnológicos, evaluación del transporte, revisión de la exactitud financiera de ventas y deudas, y análisis independiente de los registros manuales. Estos temas no forman parte del proceso de respaldo seleccionado.

- **Limitación del ejercicio:** por confidencialidad, el equipo no puede consultar datos identificables ni examinar el respaldo real. El trabajo presentará los procedimientos y la evidencia que se solicitarían en una auditoría formal autorizada; no afirmará que el proceso fue probado ni que se encontraron pérdidas.

## 4. Criterios de evaluación

| Criterio | Fuente y aplicación |
|---|---|
| El proceso de respaldo debe estar definido e indicar responsables, información que se copia, frecuencia, ubicación, conservación y acceso a las copias. | Se solicitará la política o procedimiento vigente. Según la información disponible para el caso, no existe un procedimiento escrito; este dato está pendiente de corroboración. Si no hay una política formal, estos aspectos se usarán como criterios propuestos por el equipo y deberán confirmarse con el responsable del negocio. |
| Los respaldos deben cubrir la información que el negocio necesita conservar y contar con capacidad suficiente para el volumen actual y el crecimiento previsto de los datos. | Criterio propuesto por el equipo. Se contrastaría con las necesidades de conservación, el volumen de información y la capacidad de almacenamiento que el negocio defina. No se supondrán cantidades ni periodos de retención. |
| Las copias deben conservarse de forma que puedan localizarse y utilizarse cuando se necesiten, con acceso limitado a personas autorizadas. | Criterio propuesto por el equipo, sujeto a confirmar con el responsable y a contrastar con las políticas internas que existan. Se revisarían la ubicación de las copias, quién puede acceder a ellas y cómo se protegen. |
| La recuperación de los respaldos debe probarse periódicamente conforme a una política acordada, y los resultados deben permitir identificar si la información puede restaurarse. | Como referencia se propone el control 8.13 de ISO/IEC 27002:2022, que aborda el mantenimiento y la prueba periódica de copias de respaldo según una política acordada. Se emplea como referencia para el plan, no como prueba de que la empresa haya adoptado la norma. [Referencia oficial de ISO/IEC 27002:2022](https://www.iso.org/standard/75652.html) |
| La copia disponible debe permitir identificar qué información está cubierta y qué diferencias existen frente a los datos que el negocio necesita recuperar. | Criterio propuesto por el equipo. Se contrastarían los datos cubiertos por las copias con los registros del sistema, usando información anonimizada o enmascarada en los papeles de trabajo. |

ISO/IEC 27002:2022 ofrece orientación sobre controles de seguridad de la información. El control 8.13 se refiere al mantenimiento y las pruebas periódicas de respaldos de acuerdo con una política acordada. [Guía del grupo de auditoría ISO/IEC](https://committee.iso.org/files/live/sites/jtc1sc27/files/resources/Journal%202025.pdf)

## 5. Programa de trabajo propuesto

Los procedimientos siguientes son una propuesta para una auditoría formal autorizada por el negocio. La entrevista permitiría entender el proceso, pero sus respuestas se corroborarían con documentos, configuraciones, registros y pruebas técnicas. En este taller no se solicitarán ni examinarán datos reales de clientes.

| ID del riesgo | Control a evaluar | Criterio y fuente | Procedimiento propuesto | Población o muestra | Evidencia esperada | Posibles excepciones |
|---|---|---|---|---|---|---|
| R-02 | Diseño y documentación del proceso de respaldo. | El proceso debe definir responsables, información que se copia, frecuencia, ubicación, conservación, acceso y recuperación. Se solicitará la política interna; según la información disponible, no existe un procedimiento escrito, dato pendiente de corroboración. Como referencia se propone el control 8.13 de ISO/IEC 27002:2022, que trata el mantenimiento y las pruebas periódicas de copias conforme a una política acordada. [Referencia oficial de ISO/IEC 27002:2022](https://www.iso.org/standard/75652.html) | 1. Entrevistar al propietario y al custodio actual del sistema para describir cómo se realizan los respaldos. 2. Solicitar la política, instrucciones o acuerdos vigentes. 3. Revisar si definen responsabilidades, frecuencia, cobertura, capacidad, almacenamiento, conservación, permisos y pruebas de recuperación. 4. Corroborar las respuestas con configuraciones, registros de actividad o evidencia técnica disponible. | Política o instrucciones aplicables al sistema y documentación del proceso de respaldo. Se revisaría todo lo disponible; la cantidad de documentos se determinaría al recibir el inventario. | Política o instrucciones vigentes; descripción de responsabilidades; configuración de respaldos; inventario de medios o ubicaciones; reglas de conservación y acceso; notas de entrevista contrastadas con evidencia. | No existe una definición del proceso; no se asignan responsables; la frecuencia, cobertura o conservación no están definidas; o la entrevista no puede corroborarse con documentos o configuraciones. |
| R-02 | Ejecución, cobertura y capacidad de los respaldos. | Las copias deben cubrir la información que el negocio necesita conservar y contar con capacidad adecuada para el volumen de datos y su crecimiento previsto. Esta condición es una propuesta del equipo que deberá confirmarse con las necesidades del negocio y con el responsable; no se atribuye como requisito específico del control 8.13. | 1. Obtener el inventario de respaldos o exportaciones y los registros de ejecución. 2. Comparar la información cubierta con los datos que el negocio identifica como necesarios para sus operaciones. 3. Revisar el volumen de información, capacidad disponible, ubicación, conservación y controles de acceso de los medios. 4. Incluir el respaldo reportado como último respaldo y comparar su cobertura con la información que el sistema debía conservar, investigando posibles brechas o datos sin copia. 5. Documentar las diferencias con identificadores anonimizados o datos enmascarados. | Respaldos, exportaciones y registros de ejecución disponibles durante el periodo de uso del sistema. Se revisaría la población completa si su tamaño lo permite; si no, la muestra se definiría después de conocer el inventario y el volumen real. El respaldo reportado como último disponible se incluiría de manera dirigida. | Inventario de copias; registros de ejecución; metadatos de archivos, como fecha, tamaño, formato y ubicación; información de capacidad de almacenamiento; configuración de acceso; y comparación anonimizada de cobertura. | No se localizan copias o registros; la información necesaria no está incluida; la capacidad no es suficiente según las necesidades definidas por el negocio; existen periodos sin respaldo; o no se puede establecer qué información cubre cada copia. |
| R-02 | Recuperación e integridad de las copias de respaldo. | Las copias deben someterse a pruebas periódicas conforme a una política acordada. Se propone como referencia el control 8.13 de ISO/IEC 27002:2022. La recuperación se evaluaría en un entorno controlado y sin reemplazar el sistema de producción. | 1. Seleccionar una copia de respaldo según el inventario y el riesgo, incluyendo el último respaldo reportado si está disponible. 2. Obtener una copia de trabajo y validar su legibilidad e integridad técnica. 3. Restaurarla en un entorno de prueba aislado, con autorización del negocio. 4. Comparar la información restaurada con los registros que el negocio debe conservar y documentar qué datos pueden recuperarse y cuáles presentan diferencias. 5. Registrar los resultados sin exponer nombres ni direcciones de clientes. | Copias disponibles para el sistema. Si solo se identifica una, se probaría esa copia; si existen varias, la muestra se determinaría después de conocer la población, considerando las más recientes y las que cubran periodos relevantes. | Archivo de respaldo en copia de trabajo; registro de restauración; resultados de validación de integridad y cobertura; comparación anonimizada de registros; y documentación de excepciones. | No se encuentra la copia seleccionada; el archivo no puede leerse o restaurarse; la recuperación está incompleta; los datos presentan diferencias; o no existen resultados previos de pruebas de recuperación. |

**Nota de confidencialidad:** estos procedimientos describen la evidencia que se pediría en una auditoría formal con autorización. Para el taller no se revisarán archivos ni datos reales, y no se presentarán resultados como si las pruebas ya se hubieran realizado.

### Tratamiento de los registros del 27 al 30 de junio

El respaldo reportado tiene fecha del 26 de junio, mientras que el sistema se habría utilizado hasta el 30. El plan debe verificar si hay datos incorporados después del respaldo y si existe otra copia posterior. No se asumirá que esos datos faltan hasta comparar la evidencia disponible.

## 6. Responsables, cronograma y recursos

### Responsables propuestos

| Rol | Responsabilidad |
|---|---|
| Auditor responsable | Coordinar el plan, revisar los criterios y documentar las pruebas y limitaciones. |
| Integrantes del equipo | Apoyar la solicitud y organización de evidencia, la comparación de resultados y la preparación de la exposición. Los nombres se mantienen reservados en este borrador. |
| Jefe o propietario del negocio | Autorizar el acceso formal, definir las restricciones de confidencialidad e identificar al custodio del sistema o del respaldo. |
| Custodio del sistema o de los archivos | Explicar el proceso y, en una auditoría real autorizada, aportar la evidencia técnica requerida. |

### Cronograma hipotético de ejecución

| Fase | Actividad | Resultado esperado |
|---|---|---|
| Preparación | Confirmar objetivo, alcance, criterios, autorizaciones y medidas de protección de datos. | Plan aprobado y solicitud de información definida. |
| Solicitud de información | Pedir procedimiento, inventario de respaldos, metadatos y disponibilidad del responsable. | Evidencia inicial recibida o limitaciones documentadas. |
| Revisión del diseño | Entrevistar al custodio y contrastar su explicación con políticas, configuraciones y registros. | Descripción documentada del control esperado. |
| Prueba de operación | Localizar el respaldo, revisar su cobertura y, con autorización, hacer la restauración controlada. | Resultados de pruebas y excepciones observadas. |
| Cierre | Revisar la evidencia, explicar limitaciones y presentar conclusiones de la auditoría formal. | Comunicación de resultados basada en evidencia. |

Este cronograma describe una ejecución hipotética. Para el taller, el equipo desarrollará el plan y explicará qué evidencias se solicitarían; no realizará las pruebas sobre el sistema real.

### Recursos y dependencias

- Autorización formal del negocio para acceder a la evidencia.
- Participación del responsable o custodio del sistema.
- Copia de trabajo del respaldo, si existe y se autoriza su uso.
- Entorno de prueba aislado para una restauración, si la empresa la permite.
- Medio seguro para documentar evidencia minimizada o anonimizada.
- Confirmación del periodo, del inventario de respaldos y de la política interna, si existiera.

## 7. Supuestos, hechos reportados y limitaciones

### Hechos reportados para construir el caso

- El sistema se utilizó del 12 de mayo al 30 de junio de 2026.
- El sistema registraba nombre y dirección del cliente, pedido y valor.
- Se reporta un respaldo realizado el 26 de junio de 2026.
- La empresa dejó de utilizar el sistema después del 30 de junio.
- La encargada que ingresaba información renunció el 26 de junio.

Estos datos provienen de la descripción del caso y de información comunicada por la empresa. No se han comprobado mediante documentación o acceso al respaldo.

### Supuestos de planificación

- La auditoría formal tendría autorización del jefe o propietario antes de recibir evidencia.
- La empresa podría identificar a una persona responsable de custodiar el sistema o el respaldo.
- Para una prueba de recuperación se usaría un entorno aislado y se evitaría exponer datos personales en los papeles de trabajo.

### Información por solicitar en una auditoría real

- Ubicación, formato, fecha y tamaño del respaldo reportado del 26 de junio.
- Registro o configuración que permita corroborar la exportación.
- Existencia de copias posteriores al 26 de junio.
- Procedimiento interno de respaldos o confirmación de que no existe uno.
- Datos técnicos de cobertura para comparar con la información registrada hasta el 30 de junio.
- Autorización para realizar una prueba controlada de recuperación.

### Limitaciones

- El equipo académico no cuenta con autorización para consultar datos identificables de clientes ni para examinar el respaldo real. El acceso al sistema es limitado y no permite revisar libremente la información.
- La existencia, integridad, cobertura, capacidad de almacenamiento y recuperabilidad de los respaldos no pueden comprobarse con el acceso disponible para este taller. El respaldo reportado y el proceso de copias se tratarán como información pendiente de verificación.
- No se conoce el nombre del sistema ni se divulgarán identidades o datos sobre quién ingresó información, por motivos de confidencialidad. En una auditoría formal, esos datos se solicitarían a los responsables autorizados y se manejarían bajo acuerdos de confidencialidad.
- El equipo no ejecutará pruebas de restauración ni revisará archivos reales. La evidencia mencionada en el plan es la que se solicitaría en una auditoría formal autorizada; no se presentará como evidencia obtenida.
- La propuesta no incluye hallazgos, porcentajes de cumplimiento ni conclusiones sobre la eficacia del proceso de respaldos.

## 8. Conclusión del plan propuesto

El plan concentra la revisión en R-02 y en el respaldo reportado del 26 de junio. Propone verificar cómo se define el control, corroborar la existencia y cobertura de la copia, y comprobar su recuperación en un entorno de prueba si la empresa lo autorizara.

La diferencia entre la fecha del respaldo reportado y el último día de uso del sistema hace necesario revisar la cobertura de los registros hasta el 30 de junio. Debido a las restricciones de confidencialidad, el taller presenta únicamente la evidencia que se solicitaría en una auditoría formal; no afirma que la copia exista, esté completa o sea recuperable.

## Referencia a la matriz vigente

https://docs.google.com/spreadsheets/d/e/2PACX-1vQmaa1ZyalhYvfVZfbUknuG5T-Lddrlwxbyp_5dcre-hZxf9ZoWnAlknQNlQ_yoqA/pubhtml?gid=1062765412&single=true

## Fuentes

- ISO. **ISO/IEC 27002:2022 — Information security controls.** https://www.iso.org/standard/75652.html
- ISO/IEC JTC 1/SC 27. **Journal 2025**, discusión del control A.8.13 sobre respaldos. https://committee.iso.org/files/live/sites/jtc1sc27/files/resources/Journal%202025.pdf
- Matriz inicial de riesgos de sistemas del equipo, versión vigente.

# Taller: del riesgo priorizado al plan de auditoría

**Asignatura:** Auditoría de Sistemas (ET0114)  
**Docente:** Juan Duque  
**Equipo:** integrantes reservados en esta versión por confidencialidad  
**Caso:** Negocio familiar de comercialización de productos cárnicos  
**Sistema:** nombre reservado o no disponible  
**Fecha de exposición:** 30 de octubre de 2026  
**Fecha de entrega:** 1 de noviembre de 2026  

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

**Determinar si el respaldo reportado del 26 de junio de 2026 puede localizarse y recuperarse, y evaluar su cobertura respecto de la información registrada en el sistema hasta el 30 de junio de 2026.**

El objetivo plantea una condición que podría evaluarse con evidencia en una auditoría autorizada. No afirma que el respaldo exista, que esté completo o que pueda recuperarse.

## 3. Alcance funcional

- **Proceso:** creación, conservación y recuperación de respaldos de la información del sistema.
- **Sistema o componente:** sistema de información de ventas utilizado por el negocio y el medio donde se habría guardado el respaldo del 26 de junio. El nombre del sistema y el medio de almacenamiento están por confirmar.
- **Información incluida:** registros de pedidos asociados a clientes, direcciones y valores. En las evidencias de trabajo se usarían identificadores anonimizados o datos enmascarados, según lo que autorice la organización.
- **Población:** respaldos o exportaciones que existan para el sistema durante su periodo de uso y registros que cubran del 12 de mayo al 30 de junio de 2026. El número real de elementos se determinaría al obtener un inventario autorizado.
- **Periodo:** del 12 de mayo al 30 de junio de 2026. Se revisaría específicamente el respaldo reportado del 26 de junio y la cobertura de los registros hasta el último día de uso.
- **Responsables o fuentes de información:** el jefe o propietario del negocio, la persona que actualmente custodie el sistema o sus archivos y, si estuviera disponible y autorizado, la antigua encargada del registro.
- **Incluye:** ubicación y características técnicas del respaldo; cobertura temporal; controles para su conservación; y una prueba de recuperación en un entorno controlado, si la organización la autorizara.
- **Excluye:** evaluación general de todos los controles del sistema, auditoría del transporte y análisis de los registros manuales o financieros. El alcance se limita al respaldo y recuperación de los datos del sistema.
- **Limitación del ejercicio:** el equipo no tiene autorización para revisar datos identificables de clientes ni para examinar el respaldo real. Por ello, este documento define procedimientos y evidencias esperadas, pero no presenta resultados de auditoría.

## 4. Criterios de evaluación

| Criterio | Fuente y aplicación |
|---|---|
| Las copias de respaldo se conservan y se prueban periódicamente conforme a una política acordada para respaldos. | Se propone como referencia el control 8.13 de ISO/IEC 27002:2022, relativo a respaldos de información, software y sistemas. Se aplica como criterio de diseño del plan, no como prueba de que la empresa haya adoptado la norma. [Referencia oficial de ISO/IEC 27002:2022](https://www.iso.org/standard/75652.html) |
| El respaldo debe corresponder a la información que la organización considera necesaria conservar y permitir su recuperación de acuerdo con el proceso definido. | Condición propuesta por el equipo para evaluar la cobertura y recuperabilidad. Debe contrastarse con las necesidades del negocio y confirmarse con el responsable durante una auditoría real. |
| La organización define cómo realizar, conservar y probar sus respaldos. | Se solicitaría el procedimiento vigente. Según la información disponible para el caso, no existe un procedimiento escrito; esto debe corroborarse con el responsable. Mientras no se confirme una política interna, la referencia ISO se utilizaría como guía de evaluación y no como obligación interna ya adoptada. |

ISO/IEC 27002:2022 es una norma de controles y orientación para seguridad de la información. El grupo de auditoría de ISO/IEC describe el control 8.13 como el mantenimiento y prueba periódica de respaldos de acuerdo con una política acordada. [Guía del grupo de auditoría ISO/IEC](https://committee.iso.org/files/live/sites/jtc1sc27/files/resources/Journal%202025.pdf)

## 5. Programa de trabajo propuesto

Los procedimientos siguientes son una propuesta para una auditoría formal con autorización del negocio. La entrevista serviría para comprender el proceso, pero no sería suficiente por sí sola para demostrar que el respaldo operó correctamente.

| ID del riesgo | Control a evaluar | Criterio y fuente | Procedimiento propuesto | Población o muestra | Evidencia esperada | Posibles excepciones |
|---|---|---|---|---|---|---|
| R-02 | Definición y ejecución del proceso de respaldo. | Existencia de una forma definida de respaldar y conservar la información; control 8.13 de ISO/IEC 27002:2022, usado como referencia propuesta. Procedimiento interno por solicitar y confirmar. | 1. Entrevistar al responsable actual sobre quién generaba los respaldos, cómo se guardaban y cómo se identificaba la última copia. 2. Solicitar el procedimiento o instrucciones vigentes y determinar si contemplan responsables, ubicación, frecuencia, conservación y pruebas de recuperación. 3. Corroborar lo informado con registros de exportación, configuraciones o metadatos disponibles. | Procedimiento de respaldo aplicable al sistema y registros de respaldos o exportaciones del 12 de mayo al 30 de junio de 2026. Si se informa una única copia, revisar esa copia. No se presupone el tamaño de la población. | Procedimiento vigente, configuración del sistema relacionada con exportaciones, registro de actividad o inventario de respaldos, y metadatos del archivo (fecha, tamaño, formato y ubicación), presentados sin datos personales. | No se localiza un procedimiento; no se identifica a un responsable; el respaldo reportado no se encuentra; o las fechas o características del archivo no concuerdan con lo reportado. |
| R-02 | Integridad, cobertura y recuperación del respaldo reportado. | El respaldo debe poder recuperarse y cubrir la información que el negocio necesita conservar. Como referencia de control, se propone ISO/IEC 27002:2022, control 8.13, que considera pruebas periódicas de respaldos conforme a una política acordada. | 1. En una auditoría autorizada, obtener una copia de trabajo del respaldo y validar su fecha, formato y legibilidad. 2. Restaurarlo en un entorno de prueba aislado, sin reemplazar el sistema de producción. 3. Comparar la cobertura restaurada con los registros del sistema para el periodo correspondiente. 4. Revisar especialmente los registros comprendidos entre el 27 y el 30 de junio para establecer si están incluidos en la copia reportada del 26 o si existe otra copia posterior. 5. Registrar cualquier diferencia con códigos anonimizados, sin incluir nombres ni direcciones en los papeles de trabajo del curso. | El respaldo reportado del 26 de junio y los registros disponibles entre el 12 de mayo y el 30 de junio. Si la población es pequeña y está disponible, se compararía completa; si no, se elegiría una muestra basada en fechas y riesgo, una vez conocido el volumen real. | Archivo de respaldo en copia de trabajo; registro técnico de la restauración; listado de cobertura por fecha; comparación anonimizada de registros o cantidades; y documentación de excepciones. | El respaldo no puede restaurarse; está incompleto o dañado; no cubre registros que la organización debía conservar; o no hay evidencia suficiente para corroborar la fecha, la cobertura o el resultado de la prueba. |

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

- El equipo académico no tiene autorización para ver datos identificables de clientes ni revisar el respaldo real.
- No se puede confirmar la existencia, integridad, cobertura o recuperabilidad del archivo con el acceso disponible para el taller.
- No se conoce el nombre del sistema ni quién ingresó la información del 27 al 30 de junio. Esos datos no se incluirán si la empresa no autoriza su divulgación; en una auditoría formal se pedirían a los responsables bajo confidencialidad.
- La propuesta no contiene hallazgos, porcentajes de cumplimiento ni conclusiones sobre la eficacia de los controles.

## 8. Conclusión del plan propuesto

El plan concentra la revisión en R-02 y en el respaldo reportado del 26 de junio. Propone verificar cómo se define el control, corroborar la existencia y cobertura de la copia, y comprobar su recuperación en un entorno de prueba si la empresa lo autorizara.

La diferencia entre la fecha del respaldo reportado y el último día de uso del sistema hace necesario revisar la cobertura de los registros hasta el 30 de junio. Debido a las restricciones de confidencialidad, el taller presenta únicamente la evidencia que se solicitaría en una auditoría formal; no afirma que la copia exista, esté completa o sea recuperable.

## Referencia a la matriz vigente

Este plan mantiene la referencia al riesgo **R-02** de la matriz inicial de riesgos de sistemas. La matriz completa debe incluirse como anexo o enlazarse desde el repositorio.

## Fuentes

- ISO. **ISO/IEC 27002:2022 — Information security controls.** https://www.iso.org/standard/75652.html
- ISO/IEC JTC 1/SC 27. **Journal 2025**, discusión del control A.8.13 sobre respaldos. https://committee.iso.org/files/live/sites/jtc1sc27/files/resources/Journal%202025.pdf
- Matriz inicial de riesgos de sistemas del equipo, versión vigente.

# Informe académico simulado de auditoría y plan de acción

**Asignatura:** ET0114 · Auditoría de Sistemas  
**Organización:** Carnicos y Chorizos Familia Restrepo  
**Integrantes:** Luis Fernando Restrepo Holguin  
**Riesgo priorizado:** R-02 · Pérdida, daño o imposibilidad de recuperar la información  
**Naturaleza del ejercicio:** simulado; no se examinó evidencia real de la empresa  

> **Nota:** Los registros, el archivo de respaldo, las pruebas y los resultados que aparecen como simulados se crearon únicamente para este ejercicio. No describen resultados comprobados de la empresa.

## 1. Resumen ejecutivo

Este informe desarrolla una prueba simulada del proceso de respaldos del sistema de información de un negocio familiar que comercializa productos cárnicos. El sistema estaba instalado en un solo computador y almacenaba datos de clientes y pedidos, como nombre, dirección, pedido y valor. Según la información recibida para el caso, se utilizó hasta el 30 de junio de 2026 y se habría realizado un último respaldo el 26 de junio. La existencia y ubicación de ese respaldo no se han comprobado.

Se seleccionó el riesgo R-02 de la matriz vigente, valorado en 20 puntos y clasificado como crítico. El objetivo general del plan es evaluar si el proceso de respaldos está definido y permite proteger y recuperar la información necesaria para las operaciones del negocio. Para este taller se simuló una prueba puntual de cobertura y recuperación, sin usar datos personales reales.

En el conjunto ficticio se incluyeron seis registros de pedidos y un respaldo simulado del 26 de junio. La prueba simulada logró recuperar los dos registros incluidos en esa copia. Los otros cuatro registros del conjunto, correspondientes a días posteriores, no estaban en el archivo simulado y no había otra copia simulada en el inventario del ejercicio. Esto representa una excepción **solo dentro del escenario ficticio**. No demuestra que la empresa haya perdido información ni permite concluir que su proceso real sea eficaz o ineficaz.

## 2. Contexto y riesgo seleccionado

La organización es un negocio familiar dedicado a la comercialización de carne de cerdo, pollo y chorizos. Entre sus actividades están la recepción y venta de productos, la atención de pedidos y la distribución de la mercancía.

El negocio utilizó un sistema de información instalado en un solo computador. Allí se registraban datos de clientes y pedidos. Según la descripción del caso, los pedidos se tomaban en la calle y luego se ingresaban al sistema al llegar al negocio, lo que podía representar trabajo adicional y dificultar el registro oportuno. La matriz también señala que parte de la información se manejaba en cuadernos distribuidos entre dos personas y que estos no siempre contenían los mismos datos.

La información disponible indica que el sistema se dejó de utilizar al finalizar junio de 2026. También se reportó que el último respaldo se habría hecho el 26 de junio. No conocemos la ubicación de esa copia ni tenemos autorización para examinar el archivo real. La ausencia de un procedimiento escrito de respaldos también fue reportada para el caso, pero no se ha verificado documentalmente.

El riesgo seleccionado es **R-02: pérdida, daño o imposibilidad de recuperar la información**. En la matriz, su probabilidad se valoró en 4 y su impacto en 5, con un nivel de 20 (crítico). La elección no se basa únicamente en el puntaje: este riesgo afecta la disponibilidad de la información necesaria para reconstruir operaciones y ofrece un proceso concreto para evaluar mediante registros de respaldo y una prueba de recuperación. R-01 también tiene un puntaje crítico, pero esta auditoría se delimita a los respaldos.

## 3. Objetivo y alcance

### Objetivo general del plan

Evaluar si el proceso de respaldo de la información del sistema está definido y opera de manera confiable para proteger y recuperar íntegramente los datos necesarios para las operaciones del negocio, considerando el volumen y crecimiento de la información, la frecuencia de las copias, su almacenamiento y conservación, el control de acceso y las pruebas de restauración; identificar brechas en los respaldos disponibles y posibles pérdidas de información.

### Objetivo de la prueba de este informe

Evaluar, mediante un conjunto de datos ficticios, si un respaldo simulado puede restaurarse y si cubre los registros que el negocio necesita conservar en el escenario planteado.

### Alcance

- **Proceso:** creación, conservación y recuperación de respaldos.
- **Sistema o componentes:** sistema de información de ventas, computador donde estaba instalado y medio utilizado para almacenar copias. El nombre del sistema y el medio real están por confirmar.
- **Información de interés:** registros de pedidos vinculados con clientes, direcciones y valores. En la simulación no se utilizaron datos identificables.
- **Periodo de referencia del caso:** del 12 de mayo al 30 de junio de 2026. Se considera el último respaldo reportado del 26 de junio como un elemento por investigar, no como el único criterio de auditoría.
- **Incluye:** definición del proceso, cobertura de la información, frecuencia, capacidad y ubicación del almacenamiento, conservación, acceso y recuperación de copias.
- **Excluye:** auditoría general de todos los controles tecnológicos, evaluación del transporte, exactitud financiera de las operaciones y revisión independiente de los registros manuales.
- **Limitación:** la empresa no autorizó revisar los datos identificables ni el respaldo real. Por ello, la prueba que se presenta es simulada.

## 4. Criterios y metodología

### Criterio de referencia

Se propone como referencia el control 8.13 de ISO/IEC 27002:2022, relacionado con el mantenimiento y las pruebas periódicas de copias de respaldo de acuerdo con una política acordada. Se utiliza como orientación para este ejercicio; no se afirma que la empresa haya adoptado la norma ni que esté certificada. [Referencia oficial de ISO/IEC 27002:2022](https://www.iso.org/standard/75652.html)

Para la prueba simulada se definió además esta condición académica: **el respaldo debe restaurar los registros que declara contener y su cobertura debe compararse con la información que el negocio necesita conservar**. Esta condición se creó para la práctica; no es una política interna comprobada de la empresa.

### Papel de trabajo simulado

| Elemento | Descripción |
|---|---|
| **Objetivo de la prueba** | Comprobar si el respaldo simulado puede restaurarse y si cubre los registros del conjunto ficticio. |
| **Población simulada** | Seis registros ficticios de pedidos y una copia ficticia de respaldo. Esta población se creó para el taller y no representa la cantidad de datos real. |
| **Muestra** | Se revisaron los seis registros y la única copia incluida en el ejercicio. Es un censo del conjunto simulado, no una muestra de la empresa. |
| **Procedimiento simulado** | Revisar el inventario ficticio de copias; restaurar la copia en un entorno de prueba hipotético; comparar los registros recuperados con los seis registros del conjunto ficticio; documentar diferencias. |
| **Evidencia simulada** | Inventario ficticio, archivo de respaldo representado para el ejercicio, lista de registros simulados y resultado ficticio de restauración. No se consultaron archivos de la empresa. |

### Registros ficticios usados en la prueba

Los identificadores, fechas y valores de la tabla son inventados para la práctica. No contienen nombres ni direcciones reales.

| ID simulado | Fecha del registro | Valor ficticio (COP) | Incluido en el respaldo simulado |
|---|---|---:|---|
| SIM-001 | 24/06/2026 | 52.000 | Sí |
| SIM-002 | 26/06/2026 | 87.500 | Sí |
| SIM-003 | 27/06/2026 | 45.000 | No |
| SIM-004 | 28/06/2026 | 62.000 | No |
| SIM-005 | 29/06/2026 | 31.500 | No |
| SIM-006 | 30/06/2026 | 74.000 | No |

## 5. Resultados y hallazgo simulado

### Resultado de la prueba

En el escenario ficticio, el respaldo simulado del 26 de junio se restauró correctamente y devolvió los dos registros que el inventario indicaba que contenía. Al comparar la copia con la población simulada de seis registros, cuatro registros posteriores no aparecieron en esa copia.

El inventario ficticio del ejercicio no contenía una copia posterior. Por lo tanto, bajo las condiciones simuladas, la cobertura no incluía todos los registros del conjunto. El resultado no permite afirmar que estos datos se hayan perdido en la empresa real: los registros y la copia son ficticios, y no se revisaron respaldos reales.

### H-01 — Cobertura incompleta en la prueba simulada

- **Criterio:** el respaldo debe poder restaurarse y su cobertura debe contrastarse con la información que el negocio necesita conservar. Como referencia general se propone el control 8.13 de ISO/IEC 27002:2022. La condición específica de cobertura es un criterio académico creado para esta simulación.
- **Condición simulada:** la copia ficticia restauró dos de los seis registros del conjunto del ejercicio. Los cuatro registros restantes no estaban incluidos y el inventario simulado no contenía otra copia.
- **Causa:** pendiente de determinar. La simulación no aporta evidencia para establecer por qué no había una copia posterior ni quién sería responsable.
- **Efecto o riesgo:** en el escenario ficticio, los registros no incluidos no podrían recuperarse desde esa copia. Esto representa un riesgo potencial de pérdida de información, no una pérdida comprobada en la empresa.
- **Recomendación:** definir y documentar el proceso de respaldo, asignar responsabilidades, establecer la cobertura y frecuencia según las necesidades del negocio, conservar copias con capacidad adecuada y probar periódicamente su recuperación.

## 6. Conclusión y limitaciones

La prueba ficticia muestra cómo se podría evaluar la restauración y la cobertura de un respaldo. En ese escenario, la copia se restauró, pero no incluía todos los registros de la población simulada. Esto permitió formular un hallazgo académico y proponer una acción relacionada con la cobertura y la gestión de respaldos.

La prueba no evaluó el proceso real de la empresa ni permitió determinar si su respaldo existe, dónde se encuentra, qué datos contiene o si puede recuperarse. Tampoco se revisaron la frecuencia real de las copias, la capacidad de almacenamiento, los permisos de acceso ni la existencia de otros respaldos. Por ello, no se concluye que la empresa haya perdido información ni que sus controles reales sean adecuados o inadecuados.

La conclusión se limita al conjunto ficticio de seis registros y a una copia simulada. Para emitir una conclusión sobre la empresa sería necesario contar con autorización formal y evidencia real suficiente, protegiendo siempre los datos personales y la información sensible.

## 7. Plan de acción propuesto

Las siguientes acciones responden al hallazgo simulado. No han sido aprobadas ni implementadas por la empresa.

| ID del hallazgo | Acción propuesta | Responsable propuesto | Prioridad y justificación | Plazo propuesto | Evidencia de cierre |
|---|---|---|---|---|---|
| H-01 simulado | Identificar e inventariar las copias existentes y comparar su cobertura con la información que el negocio necesita conservar. Si se identifican registros sin respaldo, definir con la empresa cómo recuperarlos desde fuentes autorizadas. | Propietario del negocio o persona designada para custodiar la información. | Alta en el escenario simulado, porque algunos registros no estaban cubiertos por la copia examinada. La prioridad real debe definirse con la empresa. | 30 días después de la aprobación, como plazo propuesto. | Inventario de copias, conciliación documentada de la información y registro de las diferencias resueltas o pendientes. |
| H-01 simulado | Documentar el proceso de respaldo, incluyendo responsables, alcance de la información, frecuencia, capacidad y ubicación de almacenamiento, conservación, control de acceso y pruebas de recuperación. | Propietario del negocio y responsable designado del sistema. | Alta en el escenario simulado, porque el proceso debe permitir conservar y recuperar los registros necesarios. | 30 días después de la aprobación, como plazo propuesto. | Procedimiento aprobado por la organización y evidencia de una prueba de restauración posterior. |

Si estas acciones se aplicaran en un caso real, los responsables y plazos tendrían que acordarse con la empresa. En este ejercicio, solo son propuestas y no deben presentarse como compromisos confirmados.

## 8. Referencias y anexos

- Matriz inicial de riesgos de sistemas del equipo, riesgo R-02.
- Plan de auditoría y alcance funcional desarrollados para el taller.
- ISO. [ISO/IEC 27002:2022 — Information security controls](https://www.iso.org/standard/75652.html).
- Anexo de registros ficticios y papel de trabajo simulado incluido en la sección 4.

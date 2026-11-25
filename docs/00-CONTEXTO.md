# Shizami

**Estado del plan:** preliminar, pendiente de investigación y validación.

**Sprint activo:** [Sprint 01](sprints/sprint-01.md), pendiente de planificación.

## Visión

Shizami ayuda a estudiantes que encuentran mucha información educativa y necesitan saber qué aprender, en qué orden, cómo practicar y cuándo están listos para avanzar. La visión es una plataforma web y móvil de aprendizaje progresivo, interactivo y personalizado, que empieza con programación y competencias tecnológicas. La propuesta frente a Mimo y otros referentes es ofrecer formación en español con mayor profundidad, proyectos reales y objetivos ligados a competencias profesionales.

## Tres pilares

| Pilar | Responsabilidad |
| --- | --- |
| Knowledge Graph | Organizar conceptos y prerrequisitos para orientar qué aprender y en qué orden. A futuro, permitir reutilizar contenidos y reconocer competencias ya dominadas. |
| Learning Engine | Enseñar, ofrecer práctica, evaluar y registrar progreso. El motor se concibe como independiente de los cursos para poder incorporar contenidos y ejercicios nuevos. |
| Course Factory | Producir, validar y actualizar cursos a escala. La visión contempla agentes especializados y revisión técnica, pedagógica y humana antes de publicar. |

## Alcance inicial propuesto

- Empezar con una experiencia web y un curso piloto. JavaScript es el candidato inicial y la selección queda abierta.
- Investigar Mimo y Duolingo con REA desde el inicio. El criterio de cierre acordado cubre el flujo funcional y UX, las APIs que consume el cliente, el modelo de datos observable, el almacenamiento y la sincronización, y las brechas y oportunidades. El [documento de investigación](01-INVESTIGACION-REA.md) reúne el criterio, el detalle técnico y el resumen ejecutivo. La duración está pendiente de definir.
- Organizar el currículo en categoría → ruta → curso → módulo → unidad → lección. Una lección puede combinar objetivo, explicación, ejemplos, práctica guiada e independiente y repaso. La estructura mínima del piloto queda por decidir.
- Explorar ejercicios interactivos como selección múltiple, completar código, ordenar instrucciones y predecir resultados. El piloto definirá qué tipos incorporar y cómo medir el aprendizaje.
- Gestionar contenidos como código en Git, con formatos como Markdown y JSON y validación automatizada según corresponda. Mantener los cursos separados del código de la aplicación.
- Acordar el grado de implementación del Knowledge Graph y de la Course Factory para el MVP. Definir público, objetivos de aprendizaje y evidencia para validar el curso piloto con estudiantes.

## Restricciones del plan base

- Implementaciones propias y una interfaz visual diferenciada de los productos de referencia. Toda reutilización de código o contenido depende de su licencia o de un permiso aplicable.
- Validación técnica, pedagógica y humana para publicar cursos generados con IA.
- Cursos definidos fuera del código de la aplicación.
- Arquitectura inicial sin microservicios.
- Aplicación nativa, sincronización offline y otras ampliaciones registradas en el [backlog](03-BACKLOG.md).

## Preparación del MVP

El recorrido propuesto comprende investigación competitiva y pedagógica, diseño curricular, exploración de la Course Factory, arquitectura, Learning Engine, producción del piloto y validación. El orden, los entregables y la distribución por sprints se definirán durante el planeamiento.

- [Investigación REA y competitiva](01-INVESTIGACION-REA.md)
- [Arquitectura](02-ARQUITECTURA.md)
- [Backlog](03-BACKLOG.md)
- [Plan de pruebas](testing/plan-pruebas.md)
- [Avances](bitacora/avances.md)
- [Errores y correcciones](bitacora/errores-y-fixes.md)

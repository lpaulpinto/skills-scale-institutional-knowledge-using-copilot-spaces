# OctoAcme Project Management Docs

Bienvenido a la documentación de Gestión de Proyectos de OctoAcme. Este README proporciona una descripción general de nuestros procesos de gestión de proyectos y enlaces convenientes a todos nuestros documentos clave de procesos.

## Resumen de Gestión de Proyectos de OctoAcme

OctoAcme sigue un enfoque de gestión de proyectos iterativo y centrado en el cliente, estructurado en cinco fases principales: **Iniciación**, **Planificación**, **Ejecución**, **Lanzamiento** y **Cierre & Retrospectiva**. 

El proceso comienza con la validación del negocio y la alineación de partes interesadas mediante un documento de una página (Project One-pager) que define el problema, los objetivos SMART y las métricas de éxito. Durante la planificación, el trabajo se divide en incrementos entregables, se estiman las dependencias y se documenta la Definición de Hecho. Esta estructura garantiza que cada proyecto tiene objetivos claros, propiedad definida y una línea de tiempo realista antes de comenzar la ejecución.

La estructura organizativa se basa en tres roles principales: el **Gestor de Proyectos (PM)**, quien coordina entregas y gestiona riesgos; el **Gestor de Productos (PdM)**, quien define resultados y prioriza el trabajo; y los **Desarrolladores**, quienes implementan las características con énfasis en la calidad y la colaboración. La comunicación se mantiene estructurada mediante una cadencia clara: sincronizaciones semanales entre PM y PdM, standups diarios del equipo (dos veces por semana), actualizaciones mensuales con partes interesadas y escaladas ad-hoc según sea necesario.

Durante la ejecución, OctoAcme utiliza tableros de proyectos (GitHub Projects) con flujos de trabajo estandarizados: Backlog → Ready → In Progress → In Review → QA → Done. Se requieren Pull Requests pequeños (≤400 líneas) con criterios de aceptación claros, pruebas automatizadas y al menos una aprobación antes de fusionar. El control de calidad incluye pruebas unitarias, pruebas de integración y pruebas de humo para flujos críticos, además de escaneos de seguridad en CI/CD.

Finalmente, después de cada sprint, lanzamiento o hito importante, el equipo realiza retrospectivas estructuradas para capturar aprendizajes y convertirlos en elementos de acción con propietarios y fechas de vencimiento, creando una cultura de mejora continua medida y celebrada.

## Documentos de Procesos

Explora cada guía de proceso para obtener directrices completas, plantillas y listas de verificación:

- [**Descripción General de Gestión de Proyectos**](octoacme-project-management-overview.md) — Introducción concisa a nuestro enfoque, roles clave y ciclo de vida.
- [**Guía de Iniciación de Proyectos**](octoacme-project-initiation.md) — Pasos iniciales para validar ideas, alinear partes interesadas y autorizar trabajo.
- [**Planificación de Proyectos**](octoacme-project-planning.md) — Cómo desglosar el trabajo, establecer cronogramas y prepararse para la ejecución.
- [**Ejecución y Seguimiento**](octoacme-execution-and-tracking.md) — Ritmo del equipo, flujos de trabajo, calidad y seguimiento del progreso.
- [**Gestión de Riesgos y Comunicación**](octoacme-risks-and-communication.md) — Identificación, gestión y comunicación de riesgos y dependencias.
- [**Guía de Lanzamiento e Implementación**](octoacme-release-and-deployment.md) — Procedimientos estandarizados para lanzar características a producción.
- [**Retrospectiva y Mejora Continua**](octoacme-retrospective-and-continuous-improvement.md) — Captura de aprendizajes e implementación de mejoras iterativas.
- [**Roles y Personas**](octoacme-roles-and-personas.md) — Definición de responsabilidades para PM, PdM, Desarrolladores y otras funciones clave.

## Principios Clave

- **Centrado en el cliente:** Priorizar el valor y la usabilidad del cliente.
- **Entrega iterativa:** Entregar incrementos pequeños y probables.
- **Propiedad clara:** Cada proyecto tiene un PM y un Gestor de Productos designados.
- **Decisiones informadas por datos:** Medir impacto e iterar basándose en evidencia.
- **Seguridad psicológica:** Fomentar retroalimentación y aprendizaje.

## Cómo Usar Esta Documentación

- Mantén el Charter del Proyecto actualizado en el repositorio de tu proyecto.
- Para nuevos proyectos, comienza con la **Guía de Iniciación** y sigue el ciclo de vida completo.
- Añade documentos específicos de procesos a `.copilot/` si deseas que Copilot Spaces los utilice como contexto.
- Consulta los documentos de procesos específicos mientras ejecutas tu proyecto para garantizar el cumplimiento de los estándares de OctoAcme.

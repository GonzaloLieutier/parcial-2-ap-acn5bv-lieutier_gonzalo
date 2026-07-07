# Parcial 2 -- Administración de Proyectos.

**Materia:** Administración de Proyectos.

**Alumno:** Gonzalo Lieutier

**Proyecto:** Agape - Aplicación de gestión de grupos.

# Introducción

En la actualidad, muchas parroquias gestionan la inscripción a sus grupos y actividades mediante formularios, mensajes de WhatsApp o de manera presencial. Esto puede dificultar la organización, la comunicación entre los distintos grupos.
Con el objetivo de mejorar este proceso, se propone el desarrollo de **Ágape**, una aplicación que permitirá a los miembros de la comunidad conocer los grupos disponibles, consultar información relevante e inscribirse de forma sencilla desde un único lugar. Además, la aplicación facilitará a los coordinadores la administración de los grupos y la comunicación con sus integrantes.
En este documento se presenta la planificación inicial del proyecto, incluyendo la definición de los objetivos, el análisis de los principales interesados, la metodología de trabajo seleccionada, los requerimientos funcionales y la organización de las tareas mediante un tablero de seguimiento.


# Objetivo SMART

Desarrollar Ágape, una aplicación móvil y web que permita a los miembros de la parroquia consultar los grupos disponibles, inscribirse a ellos y acceder a información sobre actividades y encuentros. El proyecto tendrá como objetivo finalizar el desarrollo del producto mínimo viable (MVP) en un plazo de cuatro meses, logrando que al menos el 80 % de las inscripciones a los grupos parroquiales se realicen a través de la aplicación durante los primeros tres meses posteriores a su implementación.

# Análisis de Stakeholders

Los stakeholders son todas aquellas personas o grupos que tienen interés o se ven afectados por el desarrollo del proyecto. Identificar a los principales interesados permite comprender sus necesidades, expectativas y el nivel de influencia que poseen sobre el éxito de la aplicación **Ágape**.

| Stakeholder | Interés | Influencia | Necesidades / Expectativas |
|--------------|----------|------------|----------------------------|
| Cura | Alto | Alta | Contar con una herramienta que facilite la organización de la comunidad, mejore la comunicación y permita supervisar la actividad de los distintos grupos parroquiales. |
| Coordinadores de grupos | Alto | Alta | Administrar los integrantes de sus grupos, publicar novedades, gestionar inscripciones y comunicarse con los participantes de manera sencilla. |
| Comunidad de la parroquia | Alto | Media | Conocer los grupos disponibles, inscribirse fácilmente, consultar horarios, recibir notificaciones y mantenerse informados sobre las actividades parroquiales. |


## Perfil de los Stakeholders

### Cura

Es el principal impulsor del proyecto y quien representa a la parroquia. Su objetivo es mejorar la organización de la comunidad mediante una herramienta que centralice la información y facilite la participación de los feligreses.

### Coordinadores de grupos

Son los responsables de gestionar cada grupo parroquial. El objetivo es que usen la aplicación para administrar las inscripciones, compartir información importante y mantener el contacto con los integrantes.

### Comunidad de la parroquia

Son los usuarios finales de la aplicación. Esperan tener una plataforma simple e intuitiva que les permita conocer las propuestas de la parroquia, inscribirse a los grupos de interés y acceder a toda la información necesaria desde un mismo lugar.

# Metodología ágil seleccionada

Para el desarrollo de la aplicacion se usaran dos metodologias agiles: Scrum + Kanban. Esto permite organizar el trabajo en ciclos cortos de desarrollo, priorizar las funcionalidades más importantes y visualizar el avance de cada tarea durante todo el proyecto.

## Scrum

Scrum se va a usar para planificar el trabajo en sprints de 2 semanas, en los cuales se van a desarrollar incrementos funcionales del producto. Al finalizar cada sprint, el equipo va a revisar lo construido y ajustaria las prioridades según las necesidades del proyecto.

Los roles principales serán:

| Rol | Responsabilidad |
|------|----------------|
| Product Owner | Representar las necesidades de la parroquia, priorizar funcionalidades y validar que el producto responda al objetivo del proyecto. |
| Scrum Master / equipo de coordinación | Facilitar la organización del trabajo, remover obstáculos y asegurar que se respeten las prácticas ágiles. |
| Equipo de desarrollo | Diseñar, construir y probar las funcionalidades de la aplicación. |

Los eventos de Scrum que se aplicarán son:

| Eventos | Descripción |
|------------|-------------|
| Planificación del sprint | Definir las tareas y objetivos que se van a trabajar durante las siguientes 2 semanas. |
| Daily breve | Revisar avances, bloqueos y próximos pasos del equipo. |
| Review | Presentar el incremento desarrollado a los interesados principales. |
| Retrospectiva | Analizar qué funcionó bien, qué se puede mejorar y qué ajustes aplicar en el próximo sprint. |

## Kanban

Kanban se va a usar como herramienta visual para realizar el seguimiento de las tareas. El tablero se usa para conocer el estado de cada actividad y detectar posibles bloqueos durante el desarrollo.

El tablero va a contar con estas columnas:

| Columna | Descripción |
|----------|-------------|
| Pendiente | Tareas identificadas que todavía no empezaron. |
| En proceso | Tareas que el equipo está desarrollando. |
| En revisión | Funcionalidades terminadas que deben validarse o corregirse. |
| Finalizado | Tareas completadas y aceptadas. |

## Justificación

Se uso scrum y kanban en el proyecto ya que necesita avanzar de manera ordenada hacia un MVP en un plazo de cuatro meses, pero también necesita flexibilidad para recibir feedback de los interesados.

Scrum va a permitir dividir el desarrollo en etapas cortas, priorizando funcionalidades esenciales como la consulta de grupos, la inscripción de miembros, la administración por parte de coordinadores y la comunicación con la comunidad. Y kanban va a facilitar el seguimiento visual del trabajo y ayuda a que el equipo pueda ver las tareas pendientes, bloqueadas o listas para revisión.

De esta manera, la metodología elegida permite entregar valor de forma incremental, validar avances con los usuarios, y ajustar el alcance del producto según las necesidades que aparezcan durante el desarrollo.

# Análisis de requerimientos

Los requerimientos del proyecto surgen de las necesidades de los principales interesados: el cura, los coordinadores de grupos y la comunidad de la parroquia. La idea principal es que la aplicación ayude a centralizar la información, facilitar las inscripciones y mejorar la comunicación entre los grupos.

## Requerimientos funcionales

| Numero | Requerimiento | Descripción |
|--------|---------------|-------------|
| RF01 | Consultar grupos disponibles | El usuario debe poder ver los grupos que existen dentro de la parroquia. |
| RF02 | Ver detalle de cada grupo | El usuario debe poder consultar información como horarios, descripción, lugar de encuentro y responsable del grupo. |
| RF03 | Inscribirse a un grupo | El miembro de la comunidad debe poder anotarse a un grupo desde la aplicación. |
| RF04 | Administrar integrantes | Los coordinadores deben poder ver y gestionar las personas inscriptas en sus grupos. |
| RF05 | Publicar novedades o actividades | Los coordinadores deben poder compartir información importante sobre encuentros, cambios o avisos. |
| RF06 | Recibir notificaciones | Los usuarios deben poder recibir avisos relacionados con los grupos en los que participan. |

## Requerimientos no funcionales

| Numero | Requerimiento | Descripción |
|--------|---------------|-------------|
| RNF01 | Aplicación simple e intuitiva | La aplicación debe ser fácil de usar para personas con distintos niveles de experiencia tecnológica. |
| RNF02 | Acceso desde web y móvil | El sistema debe poder usarse desde una computadora o desde un celular. |
| RNF03 | Información clara y actualizada | Los datos de los grupos, horarios y actividades deben mostrarse de forma ordenada y mantenerse actualizados. |
| RNF04 | Seguridad básica | La aplicación debe proteger los datos personales de los usuarios registrados. |

## Historias de usuario

| Numero | Historia de usuario | Objetivo |
|--------|--------------------|----------|
| HU01 | Como miembro de la comunidad, quiero ver los grupos disponibles para elegir en cuál participar. | Conocer las propuestas de la parroquia. |
| HU02 | Como miembro de la comunidad, quiero ver el detalle de un grupo para saber si me interesa participar. | Consultar información antes de inscribirse. |
| HU03 | Como miembro de la comunidad, quiero inscribirme a un grupo para participar de sus actividades. | Facilitar la inscripción desde un solo lugar. |
| HU04 | Como coordinador, quiero ver los integrantes inscriptos para organizar mejor el grupo. | Gestionar la participación de los miembros. |
| HU05 | Como coordinador, quiero publicar novedades para comunicar información importante. | Mantener informados a los integrantes. |
| HU06 | Como usuario, quiero recibir notificaciones para estar informado sobre actividades y cambios. | Mejorar la comunicación dentro de la comunidad. |

# Tablero de seguimiento

Para realizar el seguimiento del proyecto se va a usar un tablero en Trello. Este tablero permite organizar las historias de usuario, ver el estado de cada tarea y controlar el avance del desarrollo de la aplicación.

https://trello.com/invite/b/6a46d2fbc19ed0e54af1cb20/ATTI2f16c667e0cd82542d69d3fe26c209fa5741C497/agape |

| Milestone | Objetivo | Fecha estimada | Dependencias |
|---|---|---|---|
| M1 - Buscar grupos | Que los usuarios puedan encontrar información de los grupos. | Semana 1 a 4 | Definición de grupos y datos básicos. |
| M2 - Inscripción y participación | Que los usuarios puedan anotarse y gestionar su participación. | Semana 5 a 8 | M1 finalizada. |
| M3 - Gestión y comunicación | Que coordinadores puedan administrar grupos y comunicar novedades. | Semana 9 a 12 | M1 y M2 avanzadas. |

## Estimacion de requerimientos

| Milestone | HU | Estimación |
|---|---|---:|
| M1 - Buscar grupos | M1.1 - Buscar grupos por nombre | 2 |
| M1 - Buscar grupos | M1.2 - Filtrar grupos por categoría | 3 |
| M1 - Buscar grupos | M1.3 - Consultar horarios de encuentro | 2 |
| M1 - Buscar grupos | M1.4 - Ver responsable de cada grupo | 1 |
| M2 - Inscripción y participación | M2.1 - Completar formulario de inscripción | 3 |
| M2 - Inscripción y participación | M2.2 - Confirmar inscripción enviada | 2 |
| M2 - Inscripción y participación | M2.3 - Cancelar una inscripción | 3 |
| M2 - Inscripción y participación | M2.4 - Consultar estado de inscripción | 2 |
| M3 - Gestión y comunicación | M3.1 - Crear novedades para un grupo | 3 |
| M3 - Gestión y comunicación | M3.2 - Editar información de un grupo | 3 |
| M3 - Gestión y comunicación | M3.3 - Consultar listado de integrantes | 2 |
| M3 - Gestión y comunicación | M3.4 - Notificar cambios de actividad | 5 |

# Ajuste en la metodología de trabajo

Durante el desarrollo del proyecto puede aparecer una situación donde sea necesario ajustar la forma de trabajo. En este caso, se plantea una situación relacionada con el flujo de inscripción a los grupos, ya que es una de las funcionalidades principales de la aplicación.

## Situación detectada

Durante una review del sprint, se les muestra a los coordinadores y a algunos miembros de la comunidad el avance del flujo de inscripción. Al probarlo, se detecta que algunos usuarios no entienden bien cómo buscar un grupo, completar la inscripción o confirmar si quedaron anotados.

Esto muestra que, aunque la funcionalidad esté desarrollada, puede no ser lo suficientemente clara para personas con poca experiencia usando aplicaciones.

## Impacto en el proyecto

Este problema afecta directamente al objetivo del proyecto, ya que la aplicación busca que gran parte de las inscripciones a los grupos se realicen desde la plataforma. Si el proceso no es simple, los usuarios podrían volver a usar WhatsApp, formularios o la inscripción presencial.

También puede afectar el alcance del MVP, porque sería necesario mejorar la experiencia de uso antes de seguir avanzando con nuevas funcionalidades.

## Ajuste propuesto

Para adaptar la metodología de trabajo, se va a repriorizar el backlog y se van a agregar tareas de mejora de usabilidad dentro del próximo sprint. Antes de seguir con funcionalidades nuevas, el equipo va a revisar el flujo de inscripción y simplificar los pasos necesarios para anotarse a un grupo.

También se va a incorporar una validación con usuarios al final de cada sprint, para recibir feedback antes de dar por finalizada una funcionalidad. De esta manera, la review no solo sirve para mostrar avances, sino también para detectar problemas de uso.

Desde Kanban, las tareas que necesiten cambios o revisión se van a mover a la columna **En revisión**, para que el equipo pueda visualizar mejor qué elementos todavía no están listos para finalizarse.

## Resultado esperado

Con este ajuste se espera mejorar la claridad del proceso de inscripción, reducir errores de uso y asegurar que la aplicación sea más fácil de utilizar para la comunidad. Además, permite que el equipo mantenga la flexibilidad de la metodología ágil y adapte el trabajo según las necesidades reales de los usuarios.

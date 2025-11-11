**Parte 1: Análisis comparativo de modelos de desarrollo de software**

Completa la siguiente tabla comparativa. Deberás investigar y extraer la información directamente de los materiales del curso, citando las fuentes para cada punto relevante.

| Característica/Aspecto          | Modelos Clásicos (Predictivos)                                                                                                          | Modelos Evolutivos o Incrementales                                                                                                         | Metodologías Ágiles (Adaptativas)                                                                                                             |
|:---------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------|
| Definición Principal            | Desarrollo planificado y secuencial, donde las fases se siguen estrictamente (Modelo en Cascada, Modelo en V).                           | Desarrollo mediante prototipos o versiones parciales que se van mejorando hasta el producto final (Modelo de Construcción de Prototipos). | Desarrollo flexible y adaptativo centrado en ciclos cortos y entregas frecuentes (Manifiesto Ágil, Kanban, Scrum, XP).                         |
| Características Clave / Enfoque | - Fases secuenciales estrictas.<br>- Requisitos definidos desde el inicio.<br>- Documentación detallada.                                | - Entregas parciales y sucesivas.<br>- Retroalimentación entre iteraciones.<br>- Mejora continua del producto.                            | - Ciclos cortos (sprints).<br>- Alta interacción equipo-cliente.<br>- Equipos autoorganizados.<br>- Documentación ligera y centrada en valor. |
| Ventajas (Pros)                  | - Control y planificación claros.<br>- Predecible si los requisitos son estables.<br>- Útil en proyectos regulados o críticos.        | - Entregas tempranas y visibles.<br>- Permite flexibilidad moderada.<br>- Menor riesgo al dividir el proyecto en incrementos.              | - Adaptable a cambios.<br>- Entregas frecuentes de valor.<br>- Fomenta colaboración e innovación.                                             |
| Desventajas (Contras)            | - Poco flexible ante cambios.<br>- Detección tardía de errores.<br>- Riesgo de que el producto final no cumpla necesidades cambiantes. | - Puede requerir mayor esfuerzo de integración.<br>- Cambios tardíos costosos.<br>- Necesita disciplina para gestión de incrementos.    | - Requiere compromiso del equipo y cliente.<br>- Difícil de aplicar sin buena organización.<br>- Menos predictibilidad en proyectos grandes.  |
| Aportación en la Actualidad     | Relevante en proyectos críticos, regulados o con requisitos estables donde la predictibilidad es clave.                                 | Actúa como transición entre métodos clásicos y ágiles; permite iteraciones sin perder planificación inicial.                         | Predominante hoy en día; facilita entrega continua, respuesta rápida al cambio y prácticas modernas de desarrollo.                           |



**Parte 2: Reflexión sobre la detección y corrección de fallos y cambios**

Basándote en las fases del ciclo de vida del software y en los diferentes modelos de desarrollo estudiados, responde y reflexiona sobre las siguientes cuestiones:

1. Corrección de cambios y fallos en diferentes modelos: Explica cómo los distintos tipos de modelos de desarrollo (clásicos, evolutivos, ágiles) manejan la corrección de fallos y la incorporación de cambios una vez que el proyecto ha avanzado:

**¿Cómo aborda la realimentación y la posibilidad de "volver atrás" el Modelo en Cascada con Realimentación?**
+ El Modelo en Cascada con Realimentación es una variante del modelo en cascada que introduce realimentación entre etapas.
+ Esto permite volver atrás en cualquier momento para corregir, modificar o depurar algún aspecto.
+ Es ideal para proyectos rígidos, con pocos cambios y requisitos claros, aunque no es adecuado si se prevén muchos cambios.
+ En contraste con el cascada tradicional, que no permite retorno y donde los errores tardíos generan sobrecoste, esta variante mejora la corrección temprana.

**¿Cómo permiten los Modelos Evolutivos o Incrementales "refinar en sucesivas versiones" el sistema y la "rápida realimentación del usuario"?**
+ Los Modelos Evolutivos o Incrementales desarrollan una implementación inicial del sistema, que se expone a los comentarios del usuario.
+ Esta retroalimentación se usa para refinar el sistema en sucesivas versiones, hasta obtener el sistema adecuado.
+ Las actividades de especificación, desarrollo y pruebas se ejecutan en cada iteración, lo que permite rápida realimentación del usuario y ajuste continuo del software.
+ Ejemplos: Modelo Iterativo Incremental y Modelo en Espiral.

**¿Cómo las Metodologías Ágiles, con su enfoque en la "respuesta ante el cambio", las "iteraciones (sprint)" y las "pequeñas mejoras continuas" (XP), facilitan la adaptación y la corrección?**
+ Las Metodologías Ágiles se basan en desarrollo iterativo e incremental, donde los requisitos y soluciones evolucionan con el tiempo.
+ Promueven: trabajo en equipo, colaboración con el cliente, adaptación al cambio, y equipos autoorganizados y multidisciplinares.
+ Ejemplos concretos:
    - Scrum: iteraciones (sprints) regulares, entrega parcial utilizable al final de cada sprint, reuniones diarias para seguimiento.
    - XP (Extreme Programming): pequeñas mejoras continuas, refactorización, integración continua, programación por parejas, participación directa del cliente en el equipo.

**Finalmente, describe el papel fundamental de la Fase de Mantenimiento en la corrección de defectos ("mantenimiento correctivo") y la adaptación a nuevas situaciones ("mantenimiento evolutivo y adaptativo") a lo largo de la vida útil del software.**

El enfoque de cada modelo implica corrección continua y adaptación:
+ Mantenimiento correctivo: corrección de defectos detectados durante la vida útil del software (implícito en realimentación y refinamiento de modelos evolutivos e iterativos).
+ Mantenimiento evolutivo y adaptativo: adaptación del software a nuevos requisitos o mejoras, integrado de forma natural en modelos incrementales y ágiles, donde cada iteración permite incorporar cambios y mejorar funcionalidades.

**``Fuente: Punto 4. Modelos y Metodologías de Desarrollo de Software del repositorio adjuntado en la tarea y algunas dudas y consultas en google``**

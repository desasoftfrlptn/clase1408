# Apunte colaborativo — Ficha 3 · Richards & Ford (decisiones estructurales)

**Aporte a la sección:** "¿Qué es arquitectura de software?"
**Grupo:** Iroz · Nosetti · Meccico

> Leé primero `../lecturas/ficha3_richards_ford.md`. Acá escribís el aporte del grupo, con tus palabras.

---

## Nuestro aporte

### 1. ¿Qué hace un arquitecto que un programador "normal" no hace?

La principal diferencia es el **nivel de responsabilidad y alcance de las decisiones** que toma cada uno. Un programador normalmente se concentra en resolver problemas concretos de implementación, como desarrollar una funcionalidad, diseñar una clase, corregir un error o elegir un patrón de diseño para resolver un problema específico.

En cambio, el arquitecto de software tiene una visión más amplia del sistema. Su responsabilidad es tomar y guiar las **decisiones arquitectónicas** que van a determinar cómo se estructura el sistema, cómo se comunican sus partes y qué características de calidad debe cumplir. El libro menciona como una de las principales expectativas del arquitecto justamente la capacidad de tomar decisiones de arquitectura y utilizarlas para orientar las decisiones técnicas del equipo. Además, el arquitecto no trabaja únicamente desde lo técnico. Tiene que comprender el **dominio del negocio**, comunicarse con diferentes personas, negociar decisiones y conseguir que los equipos respeten las decisiones arquitectónicas. El libro establece ocho expectativas principales para un arquitecto: tomar decisiones de arquitectura, analizar continuamente la arquitectura, mantenerse actualizado, asegurar el cumplimiento de las decisiones, tener experiencia diversa, conocer el dominio de negocio, poseer habilidades interpersonales y comprender la política de la organización.

Por ejemplo, un programador puede decidir cómo implementar una determinada funcionalidad utilizando una clase o un patrón de diseño. El arquitecto, en cambio, puede decidir si el sistema tendrá una arquitectura monolítica, distribuida, basada en capas o en microservicios. También puede establecer reglas como qué componentes pueden acceder directamente a la base de datos o cómo deben comunicarse determinados módulos.



### 2. ¿Cuál decisión de arquitectura les parece la más difícil de decidir y por qué?

Considero que porque no existe una opción que sea universalmente mejor. La elección depende del contexto del sistema, de los requerimientos, de los recursos disponibles y de las características de arquitectura que se quieran priorizar. Una arquitectura monolítica puede ser más sencilla de desarrollar, probar y desplegar inicialmente, ya que gran parte del sistema se encuentra dentro de una misma unidad. Esto puede resultar conveniente para sistemas pequeños o cuando el equipo de desarrollo es reducido. Una arquitectura distribuida permite separar responsabilidades y componentes en diferentes procesos o servicios. Esto puede favorecer determinadas características como la escalabilidad o la independencia entre componentes, pero introduce nuevos problemas y costos.


Por ejemplo, en una arquitectura monolítica, los distintos componentes del sistema se encuentran dentro de la misma aplicación. Por eso, cuando un componente necesita información de otro, simplemente puede realizar una llamada interna.
En cambio, en una arquitectura distribuida, los componentes pueden estar separados en diferentes servicios o máquinas. En ese caso, para comunicarse tienen que hacerlo a través de una red. Esto hace que aparezcan problemas que en un monolito serían menos frecuentes, como que un servicio no responda, que la comunicación tarde más tiempo o que los datos entre los distintos servicios no estén actualizados al mismo tiempo.

En conclusión, considero que la decisión entre monolítico y distribuido es particularmente difícil porque tiene consecuencias sobre prácticamente todo el sistema. No solamente cambia la forma en que se organiza el código, sino también la comunicación, el despliegue, las pruebas, la infraestructura, la escalabilidad y el manejo de errores,
por este motivo, **la mejor arquitectura no es necesariamente la más compleja ni la más moderna, sino la que logra el mejor equilibrio entre las necesidades del sistema y los costos o problemas que introduce cada decisión**
---

> **Acordate:** 1–2 párrafos por respuesta, con un ejemplo propio. No copies el texto de la ficha.











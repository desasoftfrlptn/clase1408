# Ficha 1 — Ian Sommerville · *Ingeniería del Software* (7ª ed.)

**Grupo:** Sesin · Ballarre · Díaz Guevara · Caracas Aponte
**Tu aporte va en:** `apunte/ficha1.md`

**Dónde leer:** cap. 6, §6.3 (patrones de arquitectura) y §6.1 (decisiones de arquitectura) · 📄 `../libros/sommerville7_es.pdf`

---

## Texto breve (idea central)

El **patrón de capas** organiza el sistema en niveles apilados. Cada capa **usa los servicios de la capa de abajo** y **ofrece servicios a la de arriba**. La gran ventaja es la **modificabilidad**: podés cambiar una capa (por ejemplo, la base de datos) sin tocar las demás, siempre que mantengas la interfaz entre capas.

## Inciso (a responder en tu aporte)

1. Definan con sus palabras: ¿qué es una capa y cuál es su **regla de dependencia**?
2. Den **un ejemplo concreto** de cómo separar en capas "protege" un cambio (por ejemplo: cambiar la base de datos no obliga a tocar la pantalla).

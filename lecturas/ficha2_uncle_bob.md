# Ficha 2 — Robert C. Martin (Uncle Bob) · *Arquitectura Limpia*

**Grupo:** Esteban · Hrynkiewicz · Puebla · Hurst
**Tu aporte va en:** `apunte/ficha2.md`

**Dónde leer:** cap. 1 (y el diagrama de los círculos concéntricos) · 📄 `../libros/clean_architecture_es.pdf`

---

## Texto breve (idea central)

La arquitectura limpia separa el código en **círculos concéntricos**, con la lógica de negocio en el centro. La regla es tajante: **las dependencias siempre apuntan hacia adentro**. El núcleo no conoce los frameworks, ni la base de datos, ni la interfaz de usuario — son detalles intercambiables que lo rodean.

## Inciso (a responder en tu aporte)

1. ¿Qué significa que **"las dependencias apuntan hacia adentro"**?
2. ¿Por qué la lógica de negocio NO debería depender de la base de datos ni de la pantalla? ¿Qué ganamos con eso?

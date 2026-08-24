# Apunte colaborativo — Ficha 1 · Ian Sommerville (patrón de capas)

**Aporte a la sección:** "¿Qué es una capa y por qué separar?"
**Grupo:** Sesin · Ballarre · Díaz Guevara · Caracas Aponte

> Leé primero `../lecturas/ficha1_sommerville.md`. Acá escribís el aporte del grupo, con tus palabras.

---

## Nuestro aporte

### 1. ¿Qué es una capa y cuál es su regla de dependencia?

Una capa es una división que encapsula un conjunto específico de funcionalidades similares dentro del sistema. 
Cuentan con una regla de dependencia jerárquica que exige que las capas superiores consuman únicamente los servicios que ofrece la capa que se encuentra inmediatamente por debajo de ella.

### 2. Un ejemplo concreto de cómo separar en capas "protege" un cambio

si en un sistema bancario se decide rediseñar la app movil, cambiando la capa de presentacion, este rediseño no afecta en absoluto la lógica de cálculo de intereses en la base de datos de las cuentas.

---

> **Acordate:** 1–2 párrafos por respuesta, con un ejemplo propio. No copies el texto de la ficha.

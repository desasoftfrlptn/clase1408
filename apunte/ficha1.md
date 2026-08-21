# Apunte colaborativo — Ficha 1 · Ian Sommerville (patrón de capas)

**Aporte a la sección:** "¿Qué es una capa y por qué separar?"
**Grupo:** Sesin · Ballarre · Díaz Guevara · Caracas Aponte

> Leé primero `../lecturas/ficha1_sommerville.md`. Acá escribís el aporte del grupo, con tus palabras.

---

## Nuestro aporte

### 1. ¿Qué es una capa y cuál es su regla de dependencia?

Una capa es una parte del sistema que agrupa funciones relacionadas. Cada capa utiliza los servicios que le ofrece la capa que está por debajo y, a su vez, ofrece servicios a la capa superior. La idea es que cada capa conozca qué servicio puede usar, pero no necesite saber cómo está implementado internamente. Así, si se modifica una capa pero se mantiene la misma interfaz, el cambio no debería afectar al resto del sistema.

### 2. Un ejemplo concreto de cómo separar en capas "protege" un cambio

Supongamos un sistema de gestión de expedientes, como los utilizados en organismos públicos, por ejemplo Augusta o sistemas relacionados como Authentica, donde un empleado busca una causa y consulta sus movimientos. Si cambia la forma en que se guardan o se obtienen esos datos, pero la capa encargada sigue ofreciendo las mismas operaciones, la pantalla no tendría que modificarse. El cambio queda concentrado en la capa de acceso a datos, sin afectar al resto del sistema.
---

> **Acordate:** 1–2 párrafos por respuesta, con un ejemplo propio. No copies el texto de la ficha.

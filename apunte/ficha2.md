# Apunte colaborativo — Ficha 2 · Robert C. Martin / Uncle Bob (Arquitectura Limpia)

**Aporte a la sección:** "¿Qué es una capa y por qué separar?"
**Grupo:** Esteban · Hrynkiewicz · Puebla · Hurst

> Leé primero `../lecturas/ficha2_uncle_bob.md`. Acá escribís el aporte del grupo, con tus palabras.

---

## Nuestro aporte

### 1. ¿Qué significa que "las dependencias apuntan hacia adentro"?

Significa que las dependencias deben apuntar a capas de mas alto nivel o logica de negocio, de esta manera las capas interiores no dependen ni deben conocer los detalles de las capas exteriores. 
Por ejemplo, yendo a la logica de la web uno pondria cambiar la estetica de una pagina sin necesidad de cambiar la logica de negocio

### 2. ¿Por qué la lógica de negocio NO debería depender de la base de datos ni de la pantalla? ¿Qué ganamos?

Lo que se busca con el diseño en capas es lograr la mayor independencia posible entre sus capas. Cuando se habla de que la logica de negocio no deberia depender de la base de datos ni de la pantalla, esta hablando de esa interdependencia. De esta manera, se pueden hacen cambios en la base de datos sin afectar la logica de negocio, y de la misma forma se pueden hacer cambios en la pantalla o cambios esteticos sin afectarla

---

> **Acordate:** 1–2 párrafos por respuesta, con un ejemplo propio. No copies el texto de la ficha.

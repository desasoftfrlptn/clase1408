# clase1408 — Apunte colaborativo · Arquitectura y Capas

**Materia:** Desarrollo de Software — Comisión S32 (3er año, Ingeniería en Sistemas de Información)
**Unidad 1:** Arquitectura de Aplicaciones Multicapa
**Actividad:** trabajo previo a la clase del **viernes 21/08/2026**

---

## ¿De qué se trata?

Entre toda la comisión vamos a construir el **apunte colaborativo** de la Unidad 1 y, de paso, practicamos **Git + GitHub** con un flujo real de trabajo en equipo.

Cada alumno:

1. **Lee una ficha** de lectura (cada grupo lee un autor distinto sobre el mismo tema: arquitectura y capas).
2. **Escribe su aporte** en el archivo que le corresponde dentro de `apunte/`.
3. **Lo sube con Git**: rama + commit + pull request (el flujo completo que vimos en clase).

El resultado: **un único apunte de la unidad**, escrito por toda la comisión, con historial de quién aportó qué y por qué.

> ⚠️ Antes de arrancar, leé **`CONTRIBUTING.md`** — ahí está el paso a paso exacto de Git. Los comandos de la clase están en **`comandos.git`**.

---

## Asignación de fichas

Cada grupo lee un autor y aporta a una sección del apunte. La ficha está en `lecturas/`; el aporte se escribe en `apunte/`.

| Ficha | Autor | Tema que aporta | Alumnos |
|---:|---|---|---|
| 1 | Ian Sommerville | Patrón de capas y modificabilidad | Sesin · Ballarre · Díaz Guevara · Caracas Aponte |
| 2 | Robert C. Martin (Uncle Bob) | Arquitectura limpia y dependencias | Esteban · Hrynkiewicz · Puebla · Hurst |
| 3 | Richards & Ford | Decisiones estructurales difíciles de revertir | Iroz · Nosetti · Meccico |
| 4 | Martin Fowler | Lo difícil de cambiar vs lo fácil | Michelli · Durán · Nepotti |
| 5 | Carlo Ghezzi | Cualidades transversales del software | Lafitte · Hernández Ulanio · Taini |
| 6 | John Ousterhout | Complejidad y simplicidad | Carrasco · Farías · Pieroni |

---

## Nómina de la comisión

| Legajo | Alumno | Usuario GitHub | Ficha |
|---:|---|---|:--:|
| 20766 | SESIN, LEANDRO JAVIER | | 1 |
| 26807 | ESTEBAN, LUCAS DARIO | | 2 |
| 27019 | IROZ, NAHUEL LUCAS OMAR | | 3 |
| 30820 | MICHELLI, GABRIEL MATIAS | | 4 |
| 31064 | PIERONI, NICOLAS AGUSTIN | | 6 |
| 31780 | CARACAS APONTE, ELIAS OSWALDO | | 1 |
| 31971 | LAFITTE GUADARRAMA, FRANCO | FrancoLafitte | 5 |
| 32520 | CARRASCO, MARTIN ALEJANDRO | | 6 |
| 32782 | BALLARRE, CECILIA MARIEL | CeciliaBallarre | 1 |
| 33112 | HRYNKIEWICZ, CRISTIAN MIGUEL | croshkz | 2 |
| 33136 | NOSETTI, MARIA CONSTANZA | | 3 |
| 33149 | DURAN, LUCIA | luduran44-lgtm | 4 |
| 33292 | HERNANDEZ ULANIO, NAHUEL ENRIQUE | | 5 |
| 33629 | HURST, TIZIANO JAVIER | tizihurst | 2 |
| 33650 | FARIAS, IGNACIO | | 6 |
| 33716 | DIAZ GUEVARA, LUCA SEBASTIAN | | 1 |
| 33784 | PUEBLA, ZOE VALENTINA | | 2 |
| 33926 | MECCICO, SANTIAGO CARLOS | | 3 |
| 34256 | NEPOTTI, AGUSTÍN JOSÉ | | 4 |
| 34575 | TAINI, SANTINO | | 5 |

---

## Estructura del repo

```
clase1408/
├── README.md          ← estás acá (consigna + asignación)
├── CONTRIBUTING.md    ← cómo contribuir con Git (leer ANTES de empezar)
├── comandos.git       ← cheatsheet de los comandos vistos en clase
├── lecturas/          ← las 6 fichas de lectura (una por grupo)
│   ├── ficha1_sommerville.md
│   ├── ficha2_uncle_bob.md
│   ├── ficha3_richards_ford.md
│   ├── ficha4_fowler.md
│   ├── ficha5_ghezzi.md
│   └── ficha6_ousterhout.md
├── apunte/            ← el apunte colaborativo (acá se escribe el aporte)
│   ├── ficha1.md … ficha6.md
└── libros/            ← PDFs de referencia (los capítulos citados en cada ficha)
```

---

## ¿Cómo me sumo si todavía no estoy en el repo?

1. **Registrate en el issue** [📋 Registro de GitHub](https://github.com/desasoftfrlptn/clase1408/issues/1): dejá un comentario con tu nombre y tu usuario (`Nombre Apellido — @usuario`).
2. El docente te agrega como colaborador y te avisa.
3. Después seguí el flujo de `CONTRIBUTING.md`.

> ¿Todavía no tenés cuenta de GitHub? Creala en [github.com](https://github.com) y registrate en el issue con tu usuario nuevo.

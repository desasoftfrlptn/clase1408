# Cómo contribuir — Políticas de contribución

El apunte colaborativo se construye con Git. Este es el flujo completo, paso a paso. **Leelo entero antes de empezar.**

---

## Reglas de oro

1. **No se pushea directo a `main`.** Siempre se trabaja en una rama y se abre un *pull request*.
2. **Solo tocás TU archivo** en `apunte/ficha{n}.md`. No edites archivos de otra ficha ni de otro grupo.
3. **Un commit = un aporte claro.** El mensaje dice QUÉ cambiaste y POR QUÉ.

---

## Flujo paso a paso

### 1. Clonar el repo (una sola vez)

```bash
git clone https://github.com/desasoftfrlptn/clase1408.git
cd clase1408
```

### 2. Crear tu rama

El nombre de la rama es `ficha{n}/{apellido}`. Ejemplo, si sos **Sesin** (ficha 1):

```bash
git checkout -b ficha1/sesin
```

### 3. Escribir tu aporte

Abrí el archivo que te corresponde (`apunte/ficha{n}.md`), leé la ficha de tu grupo en `lecturas/` y escribí tu aporte respondiendo el inciso.

> **Regla del archivo compartido:** si sos parte de un grupo de 3 o 4, tu archivo lo edita más gente. Por eso trabajás en tu propia rama: así no pisás el trabajo de tus compañeros. Al final, los aportes se unen con el pull request.

### 4. Guardar tu trabajo (commit)

```bash
git add apunte/ficha1.md
git commit -m "docs(apunte): aporte ficha 1 - Sesin (Sommerville)"
```

Formato del mensaje: `docs(apunte): aporte ficha {n} - {Apellido} ({autor})`

### 5. Subir tu rama (push)

```bash
git push origin ficha1/sesin
```

### 6. Abrir el pull request

Entrá a GitHub → tu rama va a aparecer con un botón **"Compare & pull request"**. Clickealo, ponele un título claro (`Aporte ficha 1 - Sesin`) y crealo.

El docente revisa, y si todo está bien, **hace merge** (une tu aporte a `main`).

---

## Convenciones resumidas

| Cosa | Convención | Ejemplo |
|---|---|---|
| Rama | `ficha{n}/{apellido}` | `ficha3/meccico` |
| Commit | `docs(apunte): aporte ficha {n} - {Apellido} ({autor})` | `docs(apunte): aporte ficha 3 - Meccico (Richards & Ford)` |
| PR | título claro y corto | `Aporte ficha 3 - Meccico` |

---

## ¿Qué escribo en mi aporte?

Tu ficha de lectura (`lecturas/ficha{n}.md`) tiene un **texto breve** con la idea central del autor y un **inciso** con preguntas. Tu aporte en `apunte/ficha{n}.md` responde ese inciso con tus palabras:

- **No copies el texto de la ficha.** La idea es que la expliques vos, con un ejemplo propio.
- **1 a 2 párrafos** alcanzan. La idea es que sume al apunte, no un paper.
- Si el grupo es de varios, **coordinen**: no repitan lo mismo, cada uno aporta una mirada (definición, ejemplo, consecuencia).

---

## Problemas frecuentes

| Problema | Solución |
|---|---|
| "Permission denied" al pushear | Todavía no aceptaste la invitación de colaborador, o estás en la rama `main`. |
| "non-fast-forward" / te pide hacer pull | Alguien ya pusheó a esa rama. Hacé `git pull origin ficha{n}/{apellido}` y después `git push`. |
| Conflicto de merge | Dos personas tocaron la misma línea. Se resuelve a mano (lo vemos en clase; si te pasa antes, avisá al docente). |
| `git checkout -b` me da error | Primero tenés que estar dentro del repo clonado (`cd clase1408`). |

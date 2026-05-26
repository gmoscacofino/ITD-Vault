---
description: Generar un caso simulacro del parcial para practicar
allowed-tools: Read, Glob, Grep
---

# Simulacro de parcial

Tema o impuesto específico (opcional): **$ARGUMENTS**

(Ejemplos:
- `/simulacro` → caso integral random sobre cualquier tema
- `/simulacro Ganancias` → caso de Ganancias
- `/simulacro IVA empresa constructora` → caso específico
- `/simulacro reorganización` → tema específico)

## Pasos a seguir

1. **Si hay argumentos**: usar como tema/foco del caso.
   **Si no hay argumentos**: elegir un tema random entre los más probables del parcial (ver Cheat-Sheet → "Reglas críticas").

2. **Inspirarse en ejercicios del vault** (`03-Ejercicios/Consignas/` y `Resueltos-Catedra/`) para mantener el estilo realista del profesor (Juan García / Natalia Oyola):
   - Caso narrativo con un CFO/CEO en una situación de negocio.
   - Datos numéricos concretos (USD, %).
   - Múltiples preguntas en cadena.
   - A veces incluye trampas (datos irrelevantes, redacción ambigua).

3. **Generar UN caso nuevo** (NO copiar uno existente). Estructura:
   - **Contexto narrativo**: empresa argentina, situación, contraparte.
   - **Datos**: importes, tasas, fechas, residencias.
   - **Preguntas concretas** (2-4 puntos a resolver).
   - **Tasas a usar**: indicar al final como en los materiales reales.

4. **NO mostrar la resolución todavía**. Solo el enunciado.

5. **Después de mostrar el caso**, decir al usuario:
   > Cuando quieras, intentá la resolución y pegámela acá con `/check`. O si querés que la resuelva yo, decime "resolvé este caso".

6. **Ajustar la dificultad** según el contexto:
   - Si el usuario pidió un tema específico → foco ahí, sin distraer.
   - Si pidió general → integrar varios impuestos (Ganancias + IVA + IIBB + IDyCB).

7. **No inventar normativa**. Las tasas, presunciones y plazos tienen que coincidir con lo que está en el vault.

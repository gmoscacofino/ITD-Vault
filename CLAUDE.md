# CLAUDE.md — Vault ITD

==**Antes de cualquier respuesta, leé `00-Sistema/SYSTEM-PROMPT.md` y aplicá todas sus reglas.**==

---

## Estructura del vault

```
00-Sistema/        ← SYSTEM-PROMPT, INDEX, Cheat-Sheet, Excalidraw
01-Teoria/         ← Ganancias, IVA, IIBB, IDyCB, Sistema Tributario
02-Conceptos-Clave/← Hecho Imponible, Tax Credit, Gross-up, Fallos
03-Ejercicios/
  ├── Consignas/        ← Enunciados (lectura)
  ├── Resueltos-Catedra/← Validados, uno por caso (referencia confiable)
  │     └── Material XX/← Carpeta por material
  └── Resueltos-Claude/ ← Generados por vos (a chequear)
04-Parciales-Anteriores/
```

## Slash commands disponibles

| Comando | Para qué |
|---|---|
| `/resolver` | Resolver un caso del vault |
| `/explicar` | Explicar un concepto teórico |
| `/check` | Chequear una resolución mía |
| `/simulacro` | Generar caso parcial para practicar |
| `/cheat` | Mostrar el cheat-sheet |

Ver `.claude/commands/` para el detalle de cada uno.

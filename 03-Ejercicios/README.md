# 03 - Ejercicios

Carpeta de ejercicios prácticos organizada en 3 sub-carpetas según su estado.

---

## Estructura y flujo

```
03-Ejercicios/
├── Consignas/              ← ENUNCIADOS de todos los ejercicios (lectura)
├── Resueltos-Catedra/      ← Resoluciones VALIDADAS en clase / cátedra
└── Resueltos-Claude/       ← Resoluciones generadas por Claude (a chequear)
```

### Flujo de trabajo

1. **Consignas/**: lectura inicial. Acá están todos los ejercicios sin resolución.
2. **Resueltos-Claude/**: cuando uso Claude para resolver un ejercicio, la resolución se guarda acá. Empieza vacía.
3. **Resueltos-Catedra/**: una vez chequeada con el profe o con la resolución oficial de la cátedra, el ejercicio se mueve desde `Resueltos-Claude/` a `Resueltos-Catedra/` (renombrando si hace falta).

==Regla simple==: si está en `Resueltos-Catedra/`, podés confiar. Si está en `Resueltos-Claude/`, es propuesta a validar.

---

## Estado actual

| Material | Consignas | Resuelto Cátedra | Resuelto Claude |
|---|---|---|---|
| #06 — Repaso I Ganancias | ✅ | ✅ | — |
| #07 — Ganancias e IVA | ✅ | ✅ | — |
| #09 — IIBB e IVA | ✅ | — | (pendiente) |
| #10 — Ganancias / IVA / IIBB / IDyCB | ✅ | — | (pendiente) |
| #11 — Integral | ✅ | ✅ Caso I (Caso II pendiente) | — |
| #12 — Ejercitación integral | ✅ | — | (pendiente) |

---

## Cómo pedirle a Claude Code que resuelva un ejercicio

Ejemplo de prompt en Claude Code:

> Resolvé el Caso 1 del Material 9 (está en `03-Ejercicios/Consignas/Material 09 - Consignas.md`).
> Aplicá las reglas del SYSTEM-PROMPT. Guardá la resolución en `03-Ejercicios/Resueltos-Claude/Material 09 - Caso I - Claude.md` con el formato de los ejercicios que ya están en Resueltos-Catedra/.

Después de chequear con el profe:

> El Caso 1 del Material 9 que resolviste está validado. Movelo de `Resueltos-Claude/` a `Resueltos-Catedra/Material 09 - Resuelto.md` (o combinalo con otros casos validados de ese material).

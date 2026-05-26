---
description: Chequear una resolución del usuario contra la teoría del vault
allowed-tools: Read, Glob, Grep
---

# Chequear resolución

Resolución a chequear: **$ARGUMENTS**

(Ejemplo: `/check resolví el Material 9 Caso 1 así: [pegás tu resolución]` o `/check 03-Ejercicios/Resueltos-Claude/Material 09 - Caso I - Claude.md`)

## Pasos a seguir

1. **Identificar qué se está chequeando**:
   - Si los argumentos son una ruta de archivo → leerla y analizarla.
   - Si los argumentos son texto pegado → trabajar sobre ese texto.

2. **Identificar el ejercicio que el usuario está resolviendo** (qué Material, qué Caso). Buscar la consigna en `03-Ejercicios/Consignas/`.

3. **Si existe resolución validada en `Resueltos-Catedra/`**: compará contra ella punto por punto. Indicá:
   - ✅ Lo que está bien.
   - ❌ Lo que está mal y cuál es el error.
   - ⚠️ Lo que está ambiguo o le faltan datos.

4. **Si NO existe resolución validada**: chequeá contra la teoría del vault:
   - ¿Identificó correctamente los 4 elementos del Hecho Imponible?
   - ¿Aplicó las reglas correctas según las notas?
   - ¿Los cálculos son consistentes con las tasas/fórmulas del Cheat-Sheet?
   - ¿Citó normativa real (no inventada)?

5. **Sé exigente como mentor honesto**:
   - No digas "está bien" si no está bien.
   - Si hay un error conceptual de base, marcalo antes de revisar los cálculos.
   - Si saltó el encuadre y fue directo al cálculo, eso es ERROR de método aunque el número sea correcto.

6. **Formato de respuesta**:
   - Empezar con un diagnóstico general: ✅ Correcto / ⚠️ Parcialmente correcto / ❌ Tiene errores serios.
   - Listar problemas concretos con cita a la nota del vault que prueba el error.
   - Sugerir cómo corregir.
   - No reescribir toda la resolución a menos que el usuario lo pida.

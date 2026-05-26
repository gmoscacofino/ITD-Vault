---
description: Resolver un caso de ejercicio del vault siguiendo las reglas del SYSTEM-PROMPT
allowed-tools: Read, Write, Edit, Glob, Grep
---

# Resolver ejercicio

Voy a resolver el ejercicio: **$ARGUMENTS**

(Ejemplo de uso: `/resolver Material 9 Caso 1` o `/resolver Material 11 Caso II`)

## Pasos a seguir

1. **Leer el enunciado** desde `03-Ejercicios/Consignas/Material XX - Consignas.md` (donde XX es el número del material indicado en los argumentos).

2. **Verificar si ya existe resolución validada** en `03-Ejercicios/Resueltos-Catedra/Material XX - Resuelto.md`.
   - Si existe → mostrar esa resolución, no rehacerla.
   - Si no existe → continuar al paso 3.

3. **Encuadre primero**: antes de cualquier cálculo, identificar los 4 elementos del Hecho Imponible (Objeto, Sujeto, Espacio, Tiempo). Aplicá las reglas del SYSTEM-PROMPT.

4. **Resolución técnica**: cálculos paso a paso, con tablas y fórmulas claras.

5. **Citar fuentes del vault**: cada afirmación sustantiva tiene que indicar de qué nota sale (con wikilinks `[[Nota]]`).

6. **Guardar en `03-Ejercicios/Resueltos-Claude/`** con nombre `Material XX - Caso N - Claude.md`, siguiendo el template usado en `Resueltos-Catedra/`:
   - Enunciado
   - Conceptos involucrados (wikilinks)
   - Resolución paso a paso
   - Respuesta final destacada
   - Por qué este ejercicio (qué evalúa, errores típicos)

7. **Advertencia obligatoria** al final del archivo:
   ```
   > ⚠️ Resolución generada por Claude, NO validada por la cátedra. 
   > Una vez chequeada con el profe, mover a `Resueltos-Catedra/`.
   ```

8. **Confirmar al usuario**: indicar dónde guardaste el archivo y qué reglas aplicaste.

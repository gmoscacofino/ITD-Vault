# ITD Vault — 81.47 Impuestos para la Toma de Decisiones I

Vault colaborativo de Obsidian para preparar el final de ITD (ITBA, comisión A, Profs. García + Oyola).

---

## Qué es esto

Una colección de **~60 notas en Markdown** que cubren toda la teoría del curso, conectadas entre sí con `[[wikilinks]]`. Está pensado para abrirse con **Obsidian**, pero también funciona como repositorio de archivos `.md` que se puede leer en cualquier editor o desde GitHub.

### Qué contiene

```
ITD-Vault/
├── 00-Sistema/           → INDEX (mapa del vault) + SYSTEM-PROMPT para Claude
├── 01-Teoria/
│   ├── Sistema-Tributario/   → panorama general del sistema impositivo argentino
│   ├── Ganancias/        → 13 notas: objeto, sujetos, fuente, tasas, quebrantos, 
│   │                      reorganización, beneficiarios del exterior, etc.
│   ├── IVA/              → 13 notas: objeto, mecánica DF/CF, importación de 
│   │                      servicios, exportaciones, empresa constructora, etc.
│   ├── IIBB/             → 5 notas: hecho imponible, base imponible, convenio 
│   │                      multilateral, exenciones
│   └── IDyCB/            → impuesto a débitos y créditos bancarios
├── 02-Conceptos-Clave/   → 12 notas transversales: Hecho Imponible (4 elementos), 
│                            Devengado vs Percibido, Renta Mundial, Tax Credit, 
│                            Gross-up, Fideicomiso, fallos clave (Tucumana, 
│                            Red Hotelera, Angulo), etc.
├── 03-Ejercicios-Resueltos/  → vacía por ahora, se llena al final con los 
│                                ejercicios prácticos
├── 04-Parciales-Anteriores/  → vacía, para parciales viejos si los conseguimos
└── 05-Apuntes-Crudos/    → vacía, para apuntes sin procesar
```

### Cómo está armada cada nota

Cada nota sigue el mismo template:
1. **TL;DR** — resumen rápido (qué necesitás saber en 30 segundos)
2. **Material de origen** — de dónde viene (clase, material, fallo)
3. **Concepto central / por qué importa**
4. **Reglas técnicas** — el contenido principal
5. **Casos típicos / aplicados** — ejemplos
6. **Errores comunes** — qué no hacer
7. **Conceptos relacionados** — `[[wikilinks]]` a otras notas

Las notas integran información de las distintas fuentes (clase, materiales oficiales, notas de Lauti, notas de Berni, resumen complementario) en un cuerpo único, sin secciones separadas por fuente.

### Empezá por acá

Abrí **`00-Sistema/INDEX.md`** — es el mapa completo con tablas, esquemas de navegación rápida y los puntos de entrada según qué estés estudiando.

---

## Cómo usar el vault — paso a paso

Hay **dos perfiles** de uso: **editor** (puede modificar y subir cambios) y **consumidor** (solo lee). La mayoría va a ser consumidor.

### Si sos CONSUMIDOR (solo querés leer y estudiar)

**Lo que necesitás instalar:**
- [GitHub Desktop](https://desktop.github.com/) (para bajar el vault)
- [Obsidian](https://obsidian.md/) (para leerlo con todas sus funciones)

**Pasos:**

1. **Instalá GitHub Desktop** desde el link de arriba. Creá una cuenta de GitHub si no tenés.

2. **Pediles a los editores que te agreguen al repo privado.** Necesitan tu usuario de GitHub. Te llegará una invitación por mail — aceptala.

3. **Cloná el repo en tu computadora:**
   - Abrí GitHub Desktop.
   - File → Clone Repository.
   - Buscá el repo `ITD-Vault` (te tiene que aparecer porque te invitaron).
   - Elegí dónde guardarlo (anotá la ruta).
   - Click en "Clone".

4. **Instalá Obsidian** desde obsidian.md.

5. **Abrí el vault en Obsidian:**
   - Abrí Obsidian.
   - "Open folder as vault".
   - Seleccioná la carpeta `ITD-Vault` que acabás de clonar.
   - Listo, ya podés navegar las notas.

6. **Para actualizar el vault cuando los editores suban cambios:**
   - Abrí GitHub Desktop.
   - Click en "Fetch origin" (arriba a la derecha).
   - Si aparece "Pull origin", click ahí.
   - Las notas se actualizan automáticamente en Obsidian.

> **Importante**: como consumidor, **NO edites las notas localmente**. Si querés sugerir un cambio, mandale el contenido a alguno de los editores o abrí un Issue en GitHub.

### Si sos EDITOR (vas a modificar y subir cambios)

**Lo que necesitás instalar:**
- [GitHub Desktop](https://desktop.github.com/) o Git por línea de comandos
- [Obsidian](https://obsidian.md/)
- **Plugin Git de Obsidian** (lo instalás desde adentro de Obsidian)

**Pasos:**

1. Hacé los pasos 1 a 5 de "Consumidor" arriba.

2. **Instalá el plugin Git en Obsidian:**
   - Obsidian → Settings (rueda dentada abajo a la izquierda).
   - Community plugins → Turn on community plugins.
   - Browse → buscar "Git" → instalar el de **Vinzent03**.
   - Activarlo.

3. **Configurá el plugin Git:**
   - En Settings → Community plugins → Git → Options.
   - Ajustá: "Auto pull interval" (recomendado: 10 min) y "Auto commit-and-sync interval" (recomendado: 15 min).
   - Setear tu nombre y email de Git (los mismos de tu cuenta GitHub).

4. **Flujo de trabajo cuando editás:**
   - Abrí Obsidian y trabajá normalmente (creá, editás, borrás notas).
   - El plugin va a hacer commits automáticos cada X minutos.
   - Antes de empezar a editar, **siempre hacé pull primero** (ícono de Git en la barra lateral o `Ctrl+P` → "Git: Pull"). Esto evita conflictos con cambios de los otros editores.
   - Cuando termines de editar, hacé `Ctrl+P` → "Git: Commit-and-sync" para subir todo.

5. **Si hay conflicto** (dos personas editaron la misma línea):
   - Obsidian te avisa.
   - Abrí el archivo, decidí qué versión queda.
   - Hacé commit y sync de nuevo.

### Si tenés Claude Pro (todos lo tienen) — uso con MCP

Con MCP Obsidian, **Claude lee el vault directamente** y responde preguntas usando tus propias notas como contexto.

**Pasos:**

1. **Cloná el vault** siguiendo los pasos de Consumidor.

2. **Instalá el MCP de Obsidian para Claude:**
   - En claude.ai → Settings → Connectors.
   - Buscá "Obsidian" o "filesystem".
   - Configurá apuntando a la carpeta `ITD-Vault` que clonaste.
   - (Si no aparece directamente, googlear "Obsidian MCP Claude" — hay guías paso a paso, va cambiando rápido).

3. **Cargá el SYSTEM-PROMPT** que está en `00-Sistema/SYSTEM-PROMPT.md`. Copialo y pegalo como instrucciones personalizadas en un nuevo proyecto de Claude.

4. **Listo**: ahora cuando le preguntes a Claude algo del curso, va a buscar en tus notas primero antes de responder. Ejemplo: "explicame el Fallo Angulo usando lo que está en el vault" — Claude lee la nota correspondiente y te responde con esa información.

---

## Convenciones del vault

Para mantener consistencia si edites o agregás notas:

- **Nombres de notas sin acentos** (ej. `Importacion de Servicios.md`, no `Importación...`). Esto evita problemas de encoding entre Windows / Mac / Linux.
- **Links entre notas con `[[wikilinks]]`** (formato Obsidian). Ej. `[[IVA - Objeto]]`.
- **Resaltados con `==texto==`** para puntos críticos.
- **Citas y referencias en blockquotes** (`>`) cuando se quiere destacar algo textual o conceptos clave.
- **Una nota por concepto**: si un tema crece demasiado, separarlo en notas conectadas.

---

## Reglas de colaboración

1. **No borres notas ajenas sin avisar.** Si pensás que algo está mal, marcalo con un comentario al inicio de la nota (`> [!warning] Revisar: ...`) y avisá en el grupo.

2. **Pull antes de editar, sync después.** Para evitar conflictos.

3. **Si agregás contenido nuevo, actualizá el INDEX.** En `00-Sistema/INDEX.md`.

4. **Validá contra la cátedra antes del parcial.** Las notas reflejan lo enseñado en clase + materiales, pero los montos, alícuotas y umbrales pueden estar desactualizados. Revisá con García/Oyola.

5. **Reportá errores como Issues en GitHub.** Si encontrás algo mal y no sos editor, abrí un Issue describiendo el problema.

---

## Estado actual y pendientes

**Cubierto:**
- Teoría completa de los 4 impuestos: Ganancias, IVA, IIBB, IDyCB.
- Conceptos transversales (Hecho Imponible, Devengado vs Percibido, Renta Mundial, etc.).
- Fallos clave (Tucumana, Red Hotelera, Angulo).

**Pendiente:**
- Ejercicios prácticos resueltos (se agregan al final de la cursada).
- Parciales anteriores (si los conseguimos).
- Validación final por la cátedra.

---

## Créditos

Vault armado a partir de:
- Notas de Berni de Giuliano Mosca Cofino (`2026-XX-XX_ITD.md`).
- Notas de Lauti del curso completo (txt, 1021 líneas).
- Resumen complementario "Cheto" (docx).
- Materiales oficiales 1-4 + Material 7 (casos prácticos).
- Slides y audios de clases.

Generado con asistencia de Claude (Anthropic).

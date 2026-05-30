# IVA — Exenciones

> Operaciones que están dentro del objeto del IVA pero la ley las exime expresamente. Romper la neutralidad tiene consecuencias.

---

## TL;DR

- **Exento** ≠ **No alcanzado**: el exento está dentro del objeto pero la ley lo eximió. El no alcanzado nunca entró al objeto.
- Las exenciones suelen ser para: libros, educación, salud, transporte, ciertos servicios públicos.
- Exentar **rompe la neutralidad** del IVA: el CF de compras se vuelve costo.
- Argentina tiene exenciones por **tema contingente** (ley dice algo pero se hace otra cosa por convenios o reglamentos).

---

## Material de origen

- **Material de Lectura #4** — Exenciones del IVA
- **Notas de clase**: 2026-04-17
- **Art. 7 LIVA**

---

## Exento vs No Alcanzado

### Diferencia crítica

| Categoría | ¿Está en el objeto? | Tratamiento del CF | Quien la cobra |
|---|---|---|---|
| **No alcanzado** | NO | Sin contexto (no opera el impuesto) | Nadie |
| **Exento** | SÍ (en el objeto), pero la ley lo libera | CF asociado se pierde (es costo) | Nadie cobra DF |

> Para fines prácticos en muchos casos, exento y no alcanzado tienen efectos similares (ninguno cobra IVA). Pero la distinción importa para:
> - Saber si la operación se tiene que **informar** en DDJJ.
> - Saber si el **CF se puede recuperar** o no.

### Ejemplo

**Servicio médico** (exento):
- Está en el objeto del IVA (es prestación de servicios).
- La ley lo eximió.
- El médico no cobra IVA al paciente.
- Pero el médico tampoco puede computar el IVA de sus compras (CF) como recuperable.

**Pago de impuestos** (no alcanzado):
- No es venta de cosas muebles ni servicio.
- No está en el objeto.
- No se discute IVA.

---

## Listado típico de operaciones exentas

### Libros, diarios y revistas
- Libros físicos: exentos.
- Libros digitales: exentos (tras controversia).
- Diarios y revistas: exentos.

> Lógica: fomentar la cultura y el acceso a la información.

### Educación
- Servicios educativos prestados por establecimientos privados **reconocidos** (incorporados a planes oficiales).
- Universidades privadas habilitadas.
- Servicios de docencia particular: pueden estar exentos según condiciones.

> NO entran: capacitaciones empresariales no oficiales, ciertos cursos de extensión.

### Salud
- Servicios prestados por profesionales médicos individuales (en general exentos).
- Servicios de obra social (cobertura).
- Medicamentos: con tratamiento específico (algunos exentos, otros con tasa diferencial).

### Transporte
- Transporte público de pasajeros (interno).
- Transporte internacional de pasajeros con reciprocidad.

### Servicios financieros
- Ciertos servicios bancarios y de cambio.
- Operaciones con valores.
- Seguros (con matices).

### Honorarios de directorio, síndicos y consejo de vigilancia

Los **honorarios de directores, síndicos y miembros del consejo de vigilancia** (y equivalentes en otras sociedades, fundaciones, cooperativas) están **exentos de IVA**, siempre que:
- Se acredite la **efectiva prestación de servicios**.
- Exista una **razonable relación** entre el honorario y la tarea desempeñada.
- La tarea responda a los **objetivos de la entidad** y sea compatible con prácticas y usos del mercado.

> Fuente: **Material de Lectura #5**

### Concesiones — zona gris (ver CLAUDE.md)

==**La Ley de IVA exime "el otorgamiento de concesiones" sin distinguir público vs privado**==. Pero el Decreto Reglamentario restringe la exención solo a las concesiones **otorgadas por el Estado** (Nacional, Provincial, Municipal o CABA).

| Tipo | Posición Ley | Posición DR / AFIP |
|---|---|---|
| Concesión pública (Estado → privado) | Exenta | Exenta |
| Concesión privada (privado → privado) | Exenta (no distingue) | **Gravada** |

**Ejemplo**:
- El gobierno otorga a Metrovías la explotación del subte → **NO IVA** (concesión pública).
- Metrovías le cede a una empresa parte de una estación para instalar un local → **IVA** (concesión privada según DR/AFIP).

==**Riesgo**: quien otorga una concesión privada confiando en la ley puede recibir ajuste de AFIP basado en el DR==. Recomendación: asumir contingencia en concesiones privadas.

> Fuente: **Material de Lectura #5** — Pirámide jurídica: DR contradice Ley → prevalece Ley, pero AFIP aplica el DR.

### Subsidios — no gravados

==Los **subsidios** otorgados por el Estado **no están gravados con IVA**==.

**Lógica del análisis**: un subsidio es una transferencia del Estado que compensa parte del precio al usuario. Si existiera sin el subsidio, el precio pleno se le cobraría al usuario y no habría dudas sobre el IVA. El subsidio reemplaza precio que nadie cobra. Por lo tanto, el fisco no puede exigir IVA sobre el subsidio que no es un precio de venta.

> Fuente: **Material de Lectura #5** — Dictamen AFIP 35/2013 (disponible en campus ITBA): Los subsidios no están gravados en IVA.

> También aplica en **IIBB**: los subsidios y subvenciones del Estado no integran la base imponible de IIBB.

---

## El problema de las exenciones: pérdida de neutralidad

### Caso típico

Una empresa de servicios médicos:
- Compra insumos: paga IVA en las compras (CF).
- Presta servicios médicos: exentos, no cobra DF.

```
CF mensual: $5.000 (IVA pagado en insumos)
DF mensual: $0 (sus servicios son exentos)

¿Qué pasa con los $5.000 de CF?
- NO se pueden usar contra DF (no hay).
- NO se pueden pedir como devolución.
- → Se VOLVIERON COSTO.
```

### Impacto en precios

La empresa exenta, al no poder recuperar CF, **traslada ese costo a sus precios**. Esto significa que el consumidor final del servicio "exento" termina pagando un precio que incluye el IVA implícito de etapas anteriores.

> Es decir: las exenciones aparentes a veces no benefician realmente al consumidor final, porque el IVA "trabado" en la cadena se traslada implícitamente.

---

## Tema contingente: "la ley dice una cosa pero se hace otra"

### Concepto
Argentina tiene casos donde la ley general dice algo pero **reglamentaciones, decretos o convenios** establecen tratamiento distinto.

### Ejemplo: libros digitales
- Históricamente había debate sobre si el libro digital debía estar exento como el físico.
- La resolución fue **sí**: libros, tanto físicos como digitales, exentos.

### Ejemplo: concesiones
- La ley dice que las concesiones están exentas.
- La reglamentación lo restringió a **concesiones públicas**.
- Las concesiones privadas pasan a estar gravadas.

> El profesor marca esto como "tema contingente" donde la realidad práctica puede diferir de lo que la ley dice por su cuenta.

---

## Análisis caso por caso

Cuando se enfrenta una operación que pareciera exenta:

1. **¿Está en el objeto del IVA?** (Art. 1 LIVA: las 5 categorías)
2. **¿Hay una exención específica?** (Art. 7 LIVA)
3. **¿La exención está sujeta a alguna condición?** (ej. educación: estar reconocida oficialmente)
4. **¿Hay reglamentación que aclare/restrinja?** (decretos o resoluciones AFIP)

---

## Errores comunes

### Error 1 — Asumir que exento = sin impuesto
El exento NO cobra IVA en su venta, pero pierde el CF de sus compras. Si analizás el efecto económico total, puede haber "impuesto trabado" que se traslada.

### Error 2 — Aplicar exenciones sin requisitos
La exención en educación requiere reconocimiento oficial. Un profesor particular que no esté inscripto en planes oficiales NO está exento.

### Error 3 — Confundir exención con tasa reducida
Tasa reducida (10,5%) sigue siendo IVA gravado pero a tasa menor. Exención es no pagar nada (pero pierde CF).

### Error 4 — Asumir que toda concesión está exenta
Solo las concesiones públicas. Las privadas están gravadas.

### Error 5 — Olvidar el "tema contingente"
Antes de aplicar una exención literal de la ley, chequear reglamentación posterior, jurisprudencia o resoluciones AFIP.

---

## Implicancias para decisiones empresariales

### Para empresas con operaciones exentas

- Considerar el **costo trabado** del IVA en compras.
- Decidir entre tener filiales separadas o todo en una empresa según la composición de actividades.

### Para sectores parcialmente exentos

Si la empresa tiene actividades gravadas y exentas, debe **prorratear** el CF:
- CF asociado a ventas gravadas: recuperable.
- CF asociado a ventas exentas: costo.
- CF mixto: prorrateado según proporción de ventas gravadas/exentas.

### Para el consumidor de servicios exentos

Aparentemente "sin IVA" pero con IVA trabado en el precio. No siempre es un beneficio puro.

---

## Conceptos relacionados

- [[IVA - Objeto]] — qué entra al objeto
- [[IVA - Concepto y Logica]] — neutralidad y costo
- [[IVA - Tasas]] — alternativa: tasa reducida en vez de exención
- [[IVA - Controversias del Objeto]] — casos grises
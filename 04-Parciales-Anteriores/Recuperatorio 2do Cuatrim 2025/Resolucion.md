# Recuperatorio 2do Cuatrimestre 2025 — Resolución

> Fuente: xlsx cátedra (hoja "R2C2025" — marcada **BIEN RESUELTO**).
> Status: ✅ Validado en cátedra.
> Conceptos: [[Tax Credit]], [[Ganancias - Fuente]], [[Gross-up]], [[IVA - Exportaciones]], [[IVA - Importacion de Servicios]], [[IIBB - Exenciones y No Alcanzados]], [[IDyCB]]

---

## Razonamiento

### Encuadre — qué define cada alternativa

Las dos alternativas comparten el mismo **ingreso contractual con BHO Entertainment** (USD 420.000, facturado a las filiales chilena, brasilera y mexicana en partes iguales — los 3 países retienen 10% por CDI). El ingreso califica como **exportación de servicios** en ambas opciones (cliente del exterior + utilización fuera de AR — el contenido se exhibe en Chile, Brasil y México).

Lo que cambia entre A1 y A2 es **dónde se ejecuta la producción**. Eso impacta dos planos:

| | A1 — Filmar en **AR** | A2 — Filmar en **CHI** |
|---|---|---|
| **Fuente Ganancias de Tubo Quita** | Argentina (actividad en AR) | Extranjera (actividad en Chile) |
| **Tax credit por retenciones CDI (Chile + Brasil + México)** | ❌ NO (fuente AR → las retenciones CDI son costo) | ✅ SÍ (fuente extranjera → tax credit cancela las retenciones) |
| **IVA-RS sobre Gordon (importación de servicios)** | ✅ SÍ (servicio usado en AR) | ❌ NO (servicio usado en Chile) |
| **Retención IIGG sobre Gordon (CDI Argentina-UK, 10%)** | ✅ SÍ (Gordon trabaja en AR → fuente AR del beneficiario → retiene) | ❌ NO (Gordon trabaja en Chile → no fuente AR del beneficiario) |
| **IVA crédito sobre proveedores y alojamiento AR** | ✅ SÍ (USD 8.400 alojamiento + 3.360 prov.) | — |
| **IIBB** | Exento (ingreso es exportación) | Exento |

==**La clave del ejercicio**: la fuente Ganancias funciona en dos planos en este caso:==
- **A1 (filmar en AR)**: la **productora** tiene fuente AR (no puede tax credit por las retenciones CDI), Y **Gordon** tiene fuente AR (debe retenérsele IIGG + IVA-RS).
- **A2 (filmar en CHI)**: la **productora** tiene fuente extranjera (sí tax credit), Y **Gordon** trabaja en Chile (no es beneficiario del exterior con fuente AR → no se le retiene).

### Gross-up sobre Gordon (solo A1)

Gordon cobra **USD 160.000 limpios en mano** "por todo concepto" (la consigna dice que cualquier impuesto AR que sufra queda a cargo de Tubo Quita). La productora absorbe:

- **Retención IIGG por CDI Argentina-UK (10%)**: gross-up → **Bruto = 160.000 / 0,90 = USD 177.777,78**, **Retención = USD 17.777,78** pagada a AFIP.
- **IVA-RS** (Gordon presta servicio usado en AR → responsable sustituto): la cátedra usa **gross-up algebraico**: 160.000 / (1 − 0,21) = 202.531,65 → **IVA = USD 42.531,65** para el cálculo de "plata necesaria" (pregunta 2).

> **Nota sobre el IVA-RS — inconsistencia en el xlsx cátedra**:
> - Para el cálculo de "**plata necesaria para contratar Gordon**" (Q2) el xlsx usa **gross-up: USD 42.531,65** (= 160.000 × 21/79).
> - Para el cálculo de **IDyCB sobre costos** el xlsx usa **IVA simple: USD 33.600** (= 160.000 × 21%).
>
> Mantenemos ambos números tal cual los muestra el xlsx (marcado BIEN RESUELTO). La diferencia conceptual: el gross-up refleja el costo contractual total (Gordon libre de impuestos), el IVA simple refleja la base imponible declarada al RS.

---

## Técnica

### Bloque 1 — IDyCB (standalone)

Criterio cátedra de este parcial: **70% costo + 30% crédito**.

**IDyCB sobre ingresos** — base: cobro efectivo del cliente del exterior (ingreso − retenciones CDI 10%):

| | A1 ARG | A2 CHI |
|---|---:|---:|
| Ingreso bruto facturado | 420.000 | 420.000 |
| (−) Retenciones CDI (Chile + Brasil + México, 10% total) | (42.000) | (42.000) |
| **Base IDyCB ingresos** | **378.000** | **378.000** |
| × 0,6% | 2.268 | 2.268 |
| → 70% costo (EERR) | 1.587,60 | 1.587,60 |
| → 30% crédito IIGG | 680,40 | 680,40 |

**IDyCB sobre costos** — base: pagos por banco (criterio xlsx — usa IVA simple sobre Gordon):

| | A1 ARG | A2 CHI |
|---|---:|---:|
| Contratación Gordon (neto en mano) | 160.000 | 160.000 |
| IVA-RS Gordon a AFIP (criterio xlsx: 160k × 21%) | 33.600 | — |
| Retención IIGG Gordon a AFIP | 17.777,78 | — |
| Sueldo | 40.000 | 40.000 |
| Alojamiento (neto) | 40.000 | 32.000 |
| Viáticos y alimentos | — | 12.000 |
| Proveedores AR (neto) | 16.000 | — |
| IVA proveedores AR (pagado al prov. — base IDyCB) | 3.360 | — |
| Proveedores CHI | — | 32.000 |
| **Base IDyCB costos** | **310.737,78** | **276.000** |
| × 0,6% | 1.864,43 | 1.656 |
| → 70% costo (EERR) | 1.305,10 | 1.159,20 |
| → 30% crédito IIGG | 559,33 | 496,80 |

> **Detalle xlsx**: el cálculo de IDyCB sobre costos en A1 **no incluye el IVA alojamiento (8.400)** que sí se paga al proveedor. Es una omisión menor del xlsx cátedra (marcado BIEN RESUELTO). Preservamos el número original.

### Bloque 2 — Estado de Resultados (EERR)

| Concepto | A1 ARG | A2 CHI |
|---|---:|---:|
| Ingreso | 420.000 | 420.000 |
| (−) Contratación Gordon (neto) | (160.000) | (160.000) |
| (−) Retención Gordon (absorbida en gross-up) | (17.777,78) | — |
| (−) Sueldo | (40.000) | (40.000) |
| (−) Alojamiento | (40.000) | (32.000) |
| (−) Viáticos y alimentos | — | (12.000) |
| (−) Proveedores AR | (16.000) | — |
| (−) Proveedores CHI | — | (32.000) |
| (−) IIBB (ingreso es exportación → exento) | — | — |
| (−) IDyCB ingresos (70%) | (1.587,60) | (1.587,60) |
| (−) IDyCB costos (70%) | (1.305,10) | (1.159,20) |
| **Resultado antes IIGG** | **143.329,52** | **141.253,20** |
| (−) IIGG (30%) | (42.998,86) | (42.375,96) |
| (−/+) Retención cliente del exterior (10% × 420.000) | **(42.000)** *costo (fuente AR)* | (0) *tax credit cancela* |
| ==**Resultado final**== | ==**58.330,67**== | ==**98.877,24**== |

> **Cómo opera el tax credit en A2**:
> - Retención cliente del exterior = USD 42.000.
> - IIGG AR sobre resultado A2 = 42.375,96 → supera la retención.
> - Tax credit imputado = USD 42.000 (queda saldo IIGG por 376 a pagar).
> - **Efecto neto**: retención del exterior se compensa íntegramente.
>
> **Por qué A1 paga 42.000 extra**: fuente AR → retención del exterior es costo neto, no análogo computable como tax credit.

### Bloque 3 — Cashflow / "Cuánta plata necesito"

Esta es la **pregunta 2 del parcial**: cuánto dinero debe tener disponible la productora para contratar a Gordon.

**A1 — Contratar Gordon en Argentina**:

| Concepto | Importe |
|---|---:|
| Pago a Gordon (neto en mano) | 160.000 |
| IVA-RS a AFIP (Gordon, importación de servicios usado en AR) | 42.531,65 |
| Retención IIGG a AFIP (Gordon, benef. exterior) | 17.777,78 |
| ==**Plata necesaria para contratar Gordon en AR**== | ==**220.309,42**== |

**A2 — Contratar Gordon en Chile**:

| Concepto | Importe |
|---|---:|
| Pago a Gordon (neto en mano) | 160.000 |
| IVA-RS (no aplica — servicio usado en Chile) | — |
| Retención IIGG (no aplica — Gordon no es benef. exterior con fuente AR) | — |
| ==**Plata necesaria para contratar Gordon en CHI**== | ==**160.000**== |

==**Diferencia: USD 60.309 menos disponibilidad necesaria filmando en Chile.**==

> **Sobre IIBB en la contratación de Gordon** (la consigna pregunta explícitamente por "IVA, IIBB, etc"): **no aplica en ninguna alternativa.** Gordon es persona física no residente prestando un servicio puntual (8 episodios, no actividad habitual en jurisdicción) — la habitualidad necesaria para que IIBB lo alcance no se configura. Tampoco corresponde a Tubo Quita ingresar IIBB por la contratación de un proveedor (el IIBB grava ingresos del prestador, no costos del comitente). En A1 Tubo Quita sí soporta IIBB del 5%, pero sobre **sus propios ingresos por exportación** — y ese ingreso está **exento** por exportación de servicios, así que tampoco entra IIBB por ese lado.

---

## Respuesta final

### Pregunta 1 — ¿Qué alternativa conviene?

==**Acepto la propuesta de hacerlo en Chile (A2)**: rentabilidad sobre costos = **30,79%** (≥ umbral 30%), contra **16,13%** en Argentina (A1).==

| | A1 ARG | A2 CHI |
|---|---:|---:|
| Resultado final | 58.330,67 | **98.877,24** |
| Costos totales | 361.669,33 | 321.122,76 |
| **Rentabilidad sobre costos** | **16,13%** ❌ | **30,79%** ✅ |

A1 queda **por debajo del umbral del 30%** → se rechaza esa alternativa.

A2 supera el umbral por margen estrecho (0,79 pp) → se acepta.

**Por qué A2 > A1 (diferencia USD 40.546,57)**:
1. **Tax credit cancela la retención del exterior** (ahorro USD 42.000 en A2).
2. **No hay gross-up sobre Gordon** (ahorro USD 17.777,78 de retención absorbida).
3. **No hay IVA-RS upfront** (no afecta resultado pero sí caja).
4. Solo se compensa parcialmente con costos chilenos algo más altos en viáticos y alojamiento marginal.

### Pregunta 2 — ¿Cuánta plata para contratar Gordon?

==**Filmando en Argentina: USD 220.309,42** (160.000 neto + 42.531,65 IVA-RS + 17.777,78 retención IIGG).==

==**Filmando en Chile: USD 160.000** (solo el neto a Gordon, sin retenciones AR).==

---

## Por qué este ejercicio

1. ==**Fuente Ganancias es bilateral**==: define el tratamiento de la productora (tax credit sí/no) Y del actor (retención + IVA-RS sí/no). En A1 ambos caen como costos AR; en A2 ninguno.
2. ==**Doble gross-up en A1**==: retención IIGG sobre Gordon (USD 17.777,78) + IVA-RS sobre Gordon (USD 42.531,65) — ambos a cargo de la productora porque Gordon cobra "neto en mano".
3. ==**Rentabilidad sobre costos como criterio de decisión**==: resultado positivo no alcanza; hay que dividir resultado / costos y compararlo con el umbral exigido (≥ 30%).
4. ==**Plata necesaria ≠ resultado**==: el IVA-RS es neutro económicamente (recuperable como CF) pero **outflow inmediato**. La pregunta 2 mide caja, no P&L.
5. ==**IDyCB en este parcial usa split 70/30**== (no 67/33 como CLAUDE.md). Atender a esta diferencia.

**Errores típicos a evitar**:
- Computar tax credit en A1 (fuente AR) — está mal.
- Olvidar el gross-up sobre Gordon en A1 (USD 17.777,78 que la productora absorbe).
- No incluir el IVA-RS en la pregunta 2 ("cuánta plata necesito") — sin esos USD 42.531,65 la productora no puede ejecutar el pago, aunque económicamente sea neutro.
- Aplicar IIBB sobre los USD 420.000 — son exportación de servicios al exterior → exento.
- Aplicar IVA sobre los USD 420.000 — exportación → tasa 0%.

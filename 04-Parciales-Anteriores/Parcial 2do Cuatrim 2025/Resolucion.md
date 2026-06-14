# Parcial 2do Cuatrimestre 2025 — Resolución

> Fuente: xlsx cátedra (hoja "P2C2025" — marcada **BIEN RESUELTO**).
> Status: ✅ Validado en cátedra.
> Conceptos: [[Tax Credit]], [[Ganancias - Fuente]], [[Gross-up|Gross-down de IVA]], [[IVA - Exportaciones]], [[IIBB - Exenciones y No Alcanzados]], [[IDyCB]]

---

## Razonamiento

### Encuadre — qué define cada alternativa

Las tres alternativas comparten el mismo **ingreso contractual con EG Italia** (USD 100.000 por todo concepto, facturado a Italia). El **uso económico del software** se distribuye 25/75 entre las sociedades EG-AR y EG-BR (según la facturación esperada de EG en cada país):

| Atribución económica del ingreso | Importe |
|---|---:|
| Porción usada en AR (sociedad EG-AR, 25% del uso) | USD 25.000 |
| Porción usada en BR (sociedad EG-BR, 75% del uso) | USD 75.000 |

Las 3 alternativas difieren en **dónde se ejecuta el trabajo de desarrollo** y **quién lo presta**. Eso cambia el tratamiento de tres impuestos:

| | A1 — Prestado por Dosazero en **AR** | A2 — Prestado por Dosazero en **BR** (personal propio) | A3 — Prestado por **proveedor BR** subcontratado |
|---|---|---|---|
| **Fuente Ganancias para Dosazero** | AR (actividad en AR) | Extranjera (actividad en BR) | Extranjera (Dosazero intermedia, ejecución en BR) |
| **Tax credit por retención Italia** | ❌ NO (fuente AR → retención italiana es costo) | ✅ SÍ (fuente extranjera, hay IIGG AR contra qué imputar) | ✅ SÍ |
| **IVA sobre porción AR (25k)** | Gravado 21% → "por todo concepto" requiere gross-down | Exportación (prestado fuera) → tasa 0% | Exportación → tasa 0% |
| **IVA sobre porción BR (75k)** | Exportación (usado fuera de AR) → tasa 0% | Exportación → tasa 0% | Exportación → tasa 0% |
| **IIBB sobre porción AR** | Gravado 3% | Exento (efectivizado en exterior) | Exento |
| **IVA-RS sobre proveedor BR** | — | — | SÍ, sobre la porción usada en AR (25% × 42.000 = 10.500 × 21% = 2.205) |
| **Retención IIGG al proveedor BR** | — | — | ❌ NO (proveedor trabaja en BR → fuente extranjera del proveedor → no se grava en AR) |

==**La clave del ejercicio**: la **fuente Ganancias se define por dónde se ejecuta la actividad**, no por dónde está el cliente.== Esto determina si la retención italiana es costo (A1) o tax credit (A2/A3).

### Por qué A1 paga IVA + IIBB pero solo sobre la porción AR

- **A1**: Dosazero trabaja en AR.
  - Porción usada en AR (25.000): servicio prestado en AR, usado en AR → **IVA gravado 21% + IIBB gravado 3%**.
  - Porción usada en BR (75.000): servicio prestado en AR, usado en BR → **exportación** → IVA 0%, IIBB exento.
- **A2/A3**: el trabajo se hace en BR → todo el ingreso es exportación (no hay servicio prestado en AR) → 0% IVA, IIBB exento sobre el total.

### Por qué el ingreso AR cambia entre alternativas

- **A1**: la porción AR (25.000) "por todo concepto" incluye IVA → neto gravado = 25.000 / 1,21 = **20.661,16** (gross-down).
- **A2/A3**: la porción AR (25.000) sin IVA (es exportación) → neto = **25.000**.

---

## Técnica

### Bloque 1 — IDyCB (standalone)

Criterio cátedra de este parcial: **70% costo + 30% crédito** (≈ 2,33:1).

**IDyCB sobre ingresos** — base: cobro efectivo (ingreso total − retención italiana):

| | A1 | A2 | A3 |
|---|---:|---:|---:|
| Ingreso total facturado | 100.000 | 100.000 | 100.000 |
| (−) Retención Italia (10%) | (10.000) | (10.000) | (10.000) |
| **Base IDyCB ingresos** | **90.000** | **90.000** | **90.000** |
| × 0,6% | 540 | 540 | 540 |
| → 70% costo (EERR) | 378 | 378 | 378 |
| → 30% crédito IIGG | 162 | 162 | 162 |

**IDyCB sobre costos** — base: pagos por banco (costos + IVA + IIBB + IVA débito a pagar):

| | A1 | A2 | A3 |
|---|---:|---:|---:|
| Costo laboral propio | 35.000 | 35.000 | — |
| Costo proveedor BR | — | — | 42.000 |
| Viáticos/hoteles/alimentación | — | 15.000 | — |
| IVA-RS proveedor BR (importación, porción usada en AR: 21% × 10.500) | — | — | 2.205 |
| IIBB (solo A1, sobre porción AR neta) | 619,83 | — | — |
| IVA débito a AFIP (solo A1, sobre porción AR) | 4.338,84 | — | — |
| **Base IDyCB costos** | **39.958,68** | **50.000** | **44.205** |
| × 0,6% | 239,75 | 300 | 265,23 |
| → 70% costo (EERR) | 167,83 | 210 | 185,66 |
| → 30% crédito IIGG | 71,93 | 90 | 79,57 |

> **A3 paga IVA-RS solo sobre la porción usada en AR** (25% × 42.000 = 10.500; IVA-RS = 10.500 × 21% = 2.205). La porción usada en BR (75% del costo) es servicio del exterior usado fuera de AR → no genera IVA-RS. Como en A3 el ingreso es 0% IVA (exportación), el IVA-RS queda como **saldo a favor** del próximo período (no es costo P&L).
>
> **Por qué A3 no retiene IIGG al proveedor BR**: el proveedor trabaja en BR → fuente extranjera del proveedor → Argentina no grava IIGG sobre fuente extranjera de no residentes. La cláusula "de corresponder" de la consigna no se activa en este caso.

### Bloque 2 — Estado de Resultados (EERR)

| Concepto | A1 ARG | A2 BR x Dosazero | A3 BR x proveedor |
|---|---:|---:|---:|
| Ingreso porción AR (neto de IVA en A1) | 20.661,16 | 25.000 | 25.000 |
| Ingreso porción BR | 75.000 | 75.000 | 75.000 |
| **Total ingresos** | **95.661,16** | **100.000** | **100.000** |
| (−) Costo laboral propio | (35.000) | (35.000) | — |
| (−) Costo proveedor BR | — | — | (42.000) |
| (−) Viáticos/hoteles/alimentación | — | (15.000) | — |
| (−) IIBB (solo A1) | (619,83) | — | — |
| (−) IDyCB ingresos (70%) | (378) | (378) | (378) |
| (−) IDyCB costos (70%) | (167,83) | (210) | (185,66) |
| **Resultado antes IIGG** | **59.495,50** | **49.412,00** | **57.436,34** |
| (−) IIGG (30%) | (17.848,65) | (14.823,60) | (17.230,90) |
| (−/+) Retención Italia | **(10.000)** *costo (fuente AR)* | (0) *tax credit cancela* | (0) *tax credit cancela* |
| ==**Resultado final**== | ==**31.646,85**== | ==**34.588,40**== | ==**40.205,44**== |

> **Cómo opera el tax credit en A2/A3**:
> - Retención Italia = 10% × USD 100.000 = USD 10.000.
> - IIGG AR liquidado sobre resultado = 14.823 (A2) / 17.231 (A3) — ambos superan la retención.
> - Tax credit imputado contra IIGG AR = 10.000 (el menor entre retención y alícuota AR).
> - **Efecto neto**: la retención italiana se compensa íntegramente → no hay doble imposición.
>
> **Por qué A1 paga 10.000 extra**: fuente AR → retención italiana no es análoga al IIGG AR sobre la misma renta → queda como **costo neto** del negocio.

### Bloque 3 — Cashflow

> El xlsx cátedra no presenta cashflow separado para este parcial. El EERR de arriba representa el resultado económico final del negocio.
>
> Las divergencias EERR vs cashflow en este caso serían mínimas:
> - A1: IVA débito 4.339 cobrado al cliente AR (porción 25k), pagado a AFIP → outflow. CF de proveedores nulo (no hay compras locales con IVA crédito significativo). Saldo IVA del período: 4.339 a pagar.
> - A3: IVA-RS 2.205 pagado a AFIP por importación de servicios → outflow inmediato, recuperable como CF el mes siguiente (queda saldo a favor porque no hay débito que compensar).

---

## Respuesta final

### Pregunta iii — ¿Se acepta la propuesta?

==**SÍ se acepta**: las tres alternativas arrojan ganancia después de impuestos (resultados positivos USD 31.647 / 34.588 / 40.205).==

### Pregunta iv — ¿Cuál alternativa es la más rentable?

==**La alternativa A3 (subcontratar a proveedor brasilero) es la más conveniente: USD 40.205,44 de resultado final**, contra USD 34.588,40 (A2) y USD 31.646,85 (A1).==

**Por qué A3 > A2 > A1**:
- **A1 paga IIBB + IVA + USD 10.000 de retención italiana no recuperable** por ser fuente AR → pierde ~USD 8.558 vs A3.
- **A2 reduce impuestos AR (exportación) pero gasta USD 15.000 en viáticos** del personal de Dosazero que viaja a Brasil.
- **A3 elimina IIBB e IVA débito sobre el cliente, no paga viáticos** (el proveedor brasilero trabaja localmente), y la retención italiana se compensa con tax credit. Es la opción óptima.

**Diferencia A3 vs A1**: USD 8.558,59 a favor de A3 (27% mejor).

---

## Por qué este ejercicio

1. ==**Fuente Ganancias = dónde se ejecuta la actividad**==, no dónde está el cliente. Determina tax credit (A2/A3) vs costo (A1).
2. ==**Exportación de servicios** elimina IVA débito e IIBB== cuando el servicio se efectiviza fuera del país.
3. ==**Tax credit cancela la retención del exterior**== si la fuente es extranjera y hay IIGG AR contra qué imputar. Si fuente AR → la retención queda como costo.
4. ==**Precio "por todo concepto" requiere gross-down de IVA**==: neto = total / 1,21 (A1 porción AR).
5. ==**IVA-RS solo sobre la porción usada en AR**== (A3): el servicio importado se prorratea según el uso, no se aplica IVA-RS sobre la porción usada fuera.
6. ==**IDyCB en este parcial usa split 70/30**== (no 67/33 como en CLAUDE.md). Atender a esta diferencia.

**Errores típicos a evitar**:
- Computar tax credit en A1 (fuente AR) — está mal: el tax credit requiere fuente extranjera para el ingreso de Dosazero.
- Olvidar el gross-down de IVA en A1: tratar 25.000 como "neto" infla la base IIBB y la base IIGG.
- Aplicar IIBB sobre la porción Brasil — solo la porción AR está en juego para IIBB.
- En A3: olvidar que el IVA-RS sobre el proveedor brasilero queda como saldo a favor (no es costo) porque el ingreso es exportación.
- En A3: aplicar retención IIGG al proveedor brasilero — el proveedor trabaja en BR → fuente extranjera del proveedor → Argentina no retiene.

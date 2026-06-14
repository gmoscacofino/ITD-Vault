# Material 13 — Caso I: Gravix S.A. (plataforma de IA para departamento impositivo)

> Impuestos: [[IVA - Exportaciones]], [[IVA - Importacion de Servicios]], [[IIBB - Hecho Imponible]], [[Ganancias - Beneficiarios del Exterior]], [[IDyCB]]
> Status: ✅ Validado en clase

---

## Enunciado (resumen)

Gravix S.A. (residente argentina, RI en IVA) presta servicios de software impositivo desde CABA. Tres contratos cerrados en el mes:

- **A — Grupo Industrial Norte** (AR, RI, Córdoba): liquida impuestos AR. **$800.000/mes**.
- **B — FinCorp México** (mexicana, **con sucursal en Argentina**): monitorea obligaciones fiscales **argentinas** de la sucursal AR. Los reportes los usa el equipo mexicano para gestionar la operación local en AR. **USD 5.000/mes**.
- **C — RetailEurope GmbH** (alemana, sin presencia en AR): análisis comparativo de sistemas tributarios latinoamericanos. Usado **íntegramente en Alemania**. **USD 8.000/mes**.

Costos:
- **NormAI Inc.** (EE.UU., sin presencia en AR): API que es el motor de Gravix. **USD 6.000/mes**.
- **Sueldos y cargas sociales**: $9.000.000/mes.

Tasas: Ganancias 30%, IVA 21%, IIBB 3%, IDyCB 1,2% (0,6% + 0,6%), Ret. benef. exterior 31,5%, TC $1.000/USD, IDyCB vs Ganancias 33%.

---

## Razonamiento — antes de los números

El comercial dijo: *"los dos en dólares no pagan impuestos argentinos porque son clientes del exterior"*. **Está equivocado en dos de los tres contratos**. Lo que define el tratamiento NO es el domicilio del cliente, sino el **lugar de utilización económica** del servicio.

### Encuadre por contrato — Grilla del Hecho Imponible

| | **Contrato A** (Grupo Industrial Norte) | **Contrato B** (FinCorp México) | **Contrato C** (RetailEurope GmbH) |
|---|---|---|---|
| **Objeto** | Servicio impositivo | Servicio impositivo | Análisis comparativo LATAM |
| **Sujeto prestador** | Gravix (AR) | Gravix (AR) | Gravix (AR) |
| **Lugar prestación** | CABA (remoto) | CABA (remoto) | CABA (remoto) |
| **Utilización económica** | **AR** (Córdoba) | **AR** (sucursal local) | **Alemania** |
| **Encuadre IVA** | **Gravado 21%** | **Gravado 21%** — la utilización es la sucursal AR | **Exportación tasa 0%** |
| **Encuadre IIBB** | Gravado 3% | Gravado 3% | Exento (exportación de servicios) |
| **Encuadre Ganancias** | Sí, fuente AR | Sí, fuente AR | Sí, fuente AR (renta mundial residente) |

==**Solo el Contrato C es exportación de servicios.** Los contratos A y B son operaciones locales gravadas.==

### Por qué B no es exportación

El cliente formal es FinCorp México, pero el servicio sirve para gestionar la **sucursal argentina** de FinCorp. La utilización económica se produce en Argentina (la operación gestionada está en AR). En IVA y IIBB el criterio rector es "dónde se aprovecha el servicio", no "quién factura". → **Gravado igual que A.**

### NormAI — Importación de servicios

Servicio de software usado por Gravix en CABA. NormAI no tiene presencia en AR.

- **IVA**: Gravix es **responsable sustituto** (Art. 4 inc. h LIVA). Ingresa el IVA en nombre del proveedor. Es **neutro económicamente** (CF mes siguiente), solo hay costo financiero de timing.
- **Ganancias — Retención beneficiario del exterior**: aplica. El enunciado da 31,5% como retención. La cátedra computa la retención sobre un margen presunto del 90% del giro (criterio de clase): **retención = USD 6.000 × 90% × 31,5% = USD 1.701** (ARS 1.701.000).
- El enunciado **no aclara** si NormAI cobra libre de impuestos. La cátedra asume que Gravix **absorbe la retención** (la trata como costo adicional del servicio).

---

## Resolución — Técnica

### Paso 1 — Ingresos por contrato (en ARS, TC $1.000)

| | Neto facturado | IVA débito | IIBB |
|---|---:|---:|---:|
| Contrato A | 800.000 | 168.000 | 24.000 |
| Contrato B | 5.000.000 | 1.050.000 | 150.000 |
| Contrato C | 8.000.000 | **0** (export. tasa 0%) | **0** (exportación) |
| **Total** | **13.800.000** | **1.218.000** | **174.000** |

### Paso 2 — NormAI (importación de servicios)

- Costo bruto (lo que paga Gravix a NormAI): **6.000.000**
- Retención IIGG benef. exterior absorbida por Gravix: **6.000.000 × 90% × 31,5% = 1.701.000**
- IVA-RS (neutro, CF mes siguiente): 6.000.000 × 21% = **1.260.000**
- **Costo computable en EERR (deducible Ganancias) = 6.000.000 + 1.701.000 = 7.701.000**

### Paso 3 — IDyCB (cashflow)

| Movimiento bancario | Importe |
|---|---:|
| Créditos (ingresa): cobros con IVA = 13.800.000 + IVA débito 1.218.000 | **15.018.000** |
| Débitos (egresa): IIBB 174.000 + NormAI total 8.961.000 + Sueldos 9.000.000 | **18.135.000** |
| 0,6% sobre créditos | 90.108 |
| 0,6% sobre débitos | 108.810 |
| **IDyCB total** | **198.918** |

> Regla de cátedra (CLAUDE.md): **Resto → 67% costo + 33% crédito vs Ganancias.**
> - Costo deducible en EERR = 198.918 × 67% = **133.275,06**
> - Crédito contra IIGG = 198.918 × 33% = 65.643 *(no se computa porque hay quebranto: ver paso 5)*

### Paso 4 — Estado de Resultados (EERR)

| Concepto | Importe |
|---|---:|
| Ingresos | 13.800.000 |
| (−) IIBB | (174.000) |
| (−) Costo NormAI (con retención absorbida) | (7.701.000) |
| (−) IDyCB (67% costo) | (133.275,06) |
| (−) Sueldos y cargas | (9.000.000) |
| **Resultado antes de IIGG** | **(3.208.275,06)** |
| (−) IIGG (30%) | **0** (quebranto) |
| ==**Resultado final**== | ==**(3.208.275,06)**== |

### Paso 5 — Cashflow

| Concepto | Importe |
|---|---:|
| Ingresos cobrados (con IVA débito) | 15.018.000 |
| (−) IIBB pagado | (174.000) |
| (−) NormAI total (USD 6.000 + retención 1.701.000 + IVA-RS 1.260.000) | (8.961.000) |
| (−) Sueldos | (9.000.000) |
| (−) IDyCB | (198.918) |
| **Cashflow antes IIGG** | **(3.315.918)** |
| IIGG | 0 |
| ==**Cashflow del período**== | ==**(3.315.918)**== |

> El IVA-RS pagado (1.260.000) excede al IVA débito (1.218.000) → saldo a favor 42.000 que se traslada al período siguiente (no se cobra ahora, no afecta cashflow del mes).

---

## Conclusión — qué le decís al comercial

> *"No, no tenías razón. De los tres contratos, **solo el de RetailEurope (C) es exportación**. Norte (A) y FinCorp (B) son locales gravados: B no escapa porque la utilización económica está en su sucursal argentina, no en México."*
>
> *"Y peor: con el costo de NormAI (USD 6.000 al exterior + retención absorbida), los sueldos de $9M y los impuestos, **estamos perdiendo $3,2M por mes**. El número que tenés que mostrarle al inversor no es 'tres contratos cerrados', sino la P&L real: cuánto cuesta producir el servicio y cuánto entra después de impuestos."*

### Qué entra/sale realmente por cada contrato (margen neto antes de costos fijos)

| Contrato | Cobro neto | IVA débito | IIBB | Margen "limpio" del cliente |
|---|---:|---:|---:|---:|
| A — Norte | 800.000 | 168.000 (a AFIP) | 24.000 (cargo Gravix) | **776.000** |
| B — FinCorp | 5.000.000 | 1.050.000 (a AFIP) | 150.000 (cargo Gravix) | **4.850.000** |
| C — RetailEurope | 8.000.000 | 0 | 0 | **8.000.000** |

C es estructuralmente el mejor — pero no alcanza para cubrir NormAI + sueldos + impuestos.

---

## Por qué este ejercicio

1. ==**Utilización económica > domicilio del cliente**== para encuadrar IVA e IIBB en servicios.
2. ==Identificar la **trampa del Contrato B**==: cliente exterior pero sucursal AR → no es exportación.
3. ==**Importación de servicios**==: IVA-RS (neutro) + retención IIGG absorbida (criterio cátedra: 90% margen × 31,5%).
4. ==Diferencia EERR vs cashflow==: timing IVA-RS y débito (saldo a favor 42.000 en este caso).
5. ==**IDyCB siempre Resto**== (regla CLAUDE.md): 67% costo + 33% crédito (este último no se aprovecha si hay quebranto).
6. **Lección de negocio**: un contrato "en dólares" no garantiza margen — define más el lugar de utilización y la estructura de costos que la moneda.

**Error típico 1**: tratar B como exportación por ser cliente del exterior → ignora que la utilización es la sucursal AR.
**Error típico 2**: confundir IVA tasa 0% (exportación, C) con exento (no permite recuperar CF). En C la tasa 0% permite recuperar CF vinculado.
**Error típico 3**: olvidar la retención benef. exterior sobre NormAI (cátedra: 90% × 31,5%).
**Error típico 4**: computar el crédito IDyCB 33% contra IIGG cuando hay quebranto (IIGG = 0 → no hay contra qué computar).

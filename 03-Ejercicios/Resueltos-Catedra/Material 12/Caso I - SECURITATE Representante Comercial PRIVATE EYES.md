# Material 12 — Caso I: SECURITATE — Representante comercial de PRIVATE EYES

> Impuestos: [[Ganancias - Beneficiarios del Exterior]], [[Gross-up]], [[IVA - Importacion de Servicios]], [[IIBB - Hecho Imponible]], [[IDyCB]]
> Status: ✅ Validado en clase (1A). 1B con cálculo propio (xlsx con inconsistencias).

---

## Enunciado (resumen)

**SECURITATE** (sociedad tecnológica argentina) es contactada por **DEACTIVATE** (empresa israelí) para ser representante comercial del software cloud **PRIVATE EYES** en Argentina.

**Situación actual** (DEACTIVATE factura directamente):
- 350 clientes argentinos que compran a DEACTIVATE: USD 10.000/licencia/año
- Cliente retiene 31,5% → DEACTIVATE recibe USD 6.850, retención USD 3.150

**Condiciones de la propuesta**:
1. El precio final al cliente NO debe aumentar respecto de lo actual.
2. DEACTIVATE factura a SECURITATE **USD 6.200 libre de impuestos** por licencia (retención a cargo de SECURITATE). DEACTIVATE no acepta cobrar menos de USD 6.500 neto.
3. SECURITATE incrementará la base de clientes **+10%** con sus contactos → **385 clientes**.

**Utilidad Final Mínima Anual (UFMA)** exigida por dueño SECURITATE: **USD 192.500**.

Tasas: IIGG 30%, IVA 21%, IIBB 3%, IDyCB 1,2% (0,6%+0,6%), Ret. benef. exterior 31,5% (= 35% × 90% renta de fuente AR), TC unitario (xlsx en USD).

---

## Razonamiento — antes de los números

### Paso clave 1 — Determinar el precio que SECURITATE cobra al cliente argentino

Antes (cliente le compra a DEACTIVATE):
- Cliente RI paga USD 10.000 → retiene USD 3.150 (AFIP) → remite USD 6.850 a DEACTIVATE.
- IVA-RS: cliente paga 21% × 10.000 = USD 2.100 a AFIP → recuperable como CF.
- **Costo neto para cliente RI: USD 10.000** (la retención es para AFIP, no le suma al cliente; el IVA es neutro).

Con SECURITATE (empresa argentina):
- No hay retención de Ganancias (SECURITATE es local, no beneficiario del exterior).
- SECURITATE factura: neto gravado + 21% IVA → cliente recupera IVA como CF.
- **Costo neto para cliente RI = neto gravado**.

Para mantener el mismo costo:
```
Neto gravado por licencia = USD 10.000
Factura total con IVA     = 10.000 × 1,21 = USD 12.100
```

### Paso clave 2 — Gross-up de la retención que SECURITATE absorbe

DEACTIVATE exige USD 6.200 **libre de impuestos** → SECURITATE absorbe la retención de Ganancias 31,5%.

```
Bruto a reconocer = Neto / (1 − 0,315)
Bruto = 6.200 / 0,685 = USD 9.051,09 por licencia
Retención absorbida = 9.051,09 × 0,315 = USD 2.851,09 por licencia
```

> **Verificación de la condición de DEACTIVATE**: "no acepta cobrar menos de USD 6.500". DEACTIVATE recibe USD 6.200 (limpio). El bruto USD 9.051,09 es lo que SECURITATE deduce como costo en IIGG; DEACTIVATE no se entera. ✓

### Paso clave 3 — Encuadre por impuesto

| Impuesto | Tratamiento |
|---|---|
| **IVA** | Gravado 21% sobre venta local de licencias. IVA-RS sobre importación de servicios (compra a DEACTIVATE) → neutro económico, CF mes siguiente. |
| **IIBB** | Gravado 3% sobre ingresos brutos (sociedad → siempre alcanzada). |
| **Ganancias** | Empresa AR: 30% sobre resultado. Retención benef. exterior sobre DEACTIVATE absorbida por SECURITATE (gross-up). |
| **IDyCB** | 1,2% (0,6% débito + 0,6% crédito) sobre movimientos bancarios. **Regla cátedra: 67% costo + 33% crédito IIGG.** |

---

## Resolución 1A — Propuesta original (DEACTIVATE cobra USD 6.200 por licencia)

### Ingresos (385 clientes × USD 10.000)

| Concepto | Importe |
|---|---:|
| Ingreso neto | 3.850.000 |
| IVA débito (21%) | 808.500 |
| **Facturación total** | **4.658.500** |
| IIBB (3% × ingreso neto) | 115.500 |

### Costo DEACTIVATE (gross-up)

| Concepto | Por licencia | × 385 |
|---|---:|---:|
| Neto a DEACTIVATE | 6.200 | 2.387.000 |
| Retención IIGG absorbida | 2.851,09 | 1.097.671,53 |
| **Costo bruto deducible** | **9.051,09** | **3.484.671,53** |

### IDyCB

Movimientos bancarios:
- Créditos: cobro clientes con IVA = **4.658.500** → 0,6% = 27.951
- Débitos: pago DEACTIVATE 3.484.671,53 + IIBB 115.500 + IVA débito a AFIP 808.500 = **4.408.671,53** → 0,6% = 26.452,03

```
IDyCB total = 27.951 + 26.452,03 = 54.403,03
IDyCB costo en EERR (67%) = 36.450,03
Crédito IIGG (33%)        = 17.953,00
```

### Estado de Resultados 1A

| Concepto | Importe (USD) |
|---|---:|
| Ingreso | 3.850.000 |
| (−) IIBB | (115.500) |
| (−) Costo DEACTIVATE (gross-up) | (3.484.671,53) |
| (−) IDyCB (67% costo) | (36.450,03) |
| **EBITDA / Resultado antes IIGG** | **213.378,44** |
| (−) IIGG (30%) | (64.013,53) |
| ==**Resultado final 1A**== | ==**149.364,91**== |

### Conclusión 1A

==**Resultado USD 149.364,91 < UFMA USD 192.500 → NO se acepta la propuesta original.**==

Falta USD 43.135,09 para alcanzar la UFMA.

---

## Resolución 1B — DEACTIVATE baja USD 100 por licencia (cobra USD 6.100 neto)

### Recalculamos el gross-up

```
Bruto a reconocer = 6.100 / 0,685 = USD 8.905,11 por licencia
Retención absorbida = 8.905,11 × 0,315 = USD 2.805,11 por licencia
Costo total (385 licencias) = 385 × 8.905,11 = USD 3.428.467,15
```

> El xlsx de cátedra mantiene en 1B el COSTO 3.484.671,53 (mismo que 1A) y modifica el ingreso a 3.503.500 — interpretamos que hay inconsistencia en el armado del xlsx. Aplicamos la lectura literal del enunciado: DEACTIVATE baja USD 100, condición 1 sigue vigente (cliente paga lo mismo).

### Ingresos (sin cambios respecto de 1A)

Mismo precio al cliente (USD 10.000 neto/licencia × 385 = USD 3.850.000), IIBB 115.500, IVA débito 808.500.

### IDyCB 1B

- Créditos: 4.658.500 → 0,6% = 27.951
- Débitos: 3.428.467,15 + 115.500 + 808.500 = 4.352.467,15 → 0,6% = 26.114,80
- IDyCB total = 54.065,80
- IDyCB costo (67%) = 36.224,09
- Crédito IIGG (33%) = 17.841,71

### Estado de Resultados 1B

| Concepto | Importe (USD) |
|---|---:|
| Ingreso | 3.850.000 |
| (−) IIBB | (115.500) |
| (−) Costo DEACTIVATE (gross-up con 6.100) | (3.428.467,15) |
| (−) IDyCB (67% costo) | (36.224,09) |
| **EBITDA** | **269.808,76** |
| (−) IIGG (30%) | (80.942,63) |
| ==**Resultado final 1B**== | ==**188.866,13**== |

### Conclusión 1B

==**Resultado USD 188.866,13 < UFMA USD 192.500 → tampoco se acepta.**==

Falta USD 3.633,87 para alcanzar la UFMA — está muy cerca pero no alcanza. **Se rechaza la propuesta**.

> Alternativa: si SECURITATE pudiera negociar USD 110 de reducción (en lugar de USD 100), o sumar 1-2 clientes más, se alcanzaría la UFMA.

---

## Comparación 1A vs 1B

| | 1A (DEACTIVATE cobra 6.200) | 1B (DEACTIVATE cobra 6.100) |
|---:|---:|---:|
| Costo per licencia (gross-up) | 9.051,09 | 8.905,11 |
| Costo total (385 licencias) | 3.484.671,53 | 3.428.467,15 |
| EBITDA | 213.378,44 | 269.808,76 |
| Resultado final | **149.364,91** | **188.866,13** |
| Δ vs UFMA 192.500 | −43.135 | −3.634 |
| **Decisión** | **Rechazar** | **Rechazar (al filo)** |

---

## Por qué este ejercicio

1. ==**Costo igual para el cliente**==: redefinir el precio mirando qué soporta económicamente el cliente RI (la retención y el IVA son neutros para él).
2. ==**Gross-up algebraico puro**==: Bruto = Neto / (1 − tasa). La tasa 31,5% es ya la efectiva (35% × 90% renta de fuente AR).
3. ==**UFMA como umbral de decisión**==: el ejercicio no pregunta "cuánto gano", sino "¿supero la UFMA?".
4. ==**Sensibilidad**==: bajar USD 100 el costo unitario sube el resultado en ~USD 39.500 (apalancamiento del gross-up). Cerca pero no alcanza.
5. ==**IDyCB siempre Resto**==: 67% costo + 33% crédito IIGG.

**Error típico 1**: usar 6.200 como costo deducible (sin gross-up). Subestima retención y resultado.
**Error típico 2**: cobrar al cliente USD 12.100 (con IVA) como "ingreso" en lugar de USD 10.000 (neto). Infla IIBB y base de IIGG.
**Error típico 3**: incluir el IVA débito facturado al cliente como "ingreso" (no, va a AFIP).
**Error típico 4**: olvidar la condición de DEACTIVATE "no acepta menos de USD 6.500" — sirve como sanity check del gross-up, no como precio.

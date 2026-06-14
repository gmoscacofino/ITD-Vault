# Material 13 — Caso III: Polola S.A. — Exportación de servicios y "libre de impuestos"

> Impuestos: [[IVA - Exportaciones]], [[IIBB - Exenciones y No Alcanzados]], [[IVA - Importacion de Servicios]], [[Ganancias - Beneficiarios del Exterior]], [[IDyCB]]
> Status: ✅ Validado en clase

---

## Enunciado (resumen)

Polola S.A. (residente AR, RI en IVA). App para gestión financiera de parejas. Tres contratos:

- **A — MercadoFree** (AR, RI): beneficio para vendedores AR, usado en AR. **$7.260.000 por todo concepto, impuestos incluidos**.
- **B — Conecta Chile S.A.** (chilena, sin presencia en AR): **USD 15.000 libre de impuestos argentinos**. Dos variantes:
  - **B1**: parejas **chilenas** que operan en Chile (utilización en Chile).
  - **B2**: parejas de empleados de su **filial argentina**, que operan en AR (utilización en AR).

Costos:
- **Strype Inc.** (EE.UU., sin presencia en AR): USD 4.000/mes por procesamiento de pagos. Servicio desde EE.UU., utilizado en AR. **Libre de retenciones argentinas** (Polola absorbe la retención).
- **Sueldos y cargas sociales**: $8.000.000/mes.

Tasas: Ganancias 30%, IVA 21%, IIBB 3%, IDyCB 1,2% (0,6%+0,6%), Ret. benef. exterior 31,5%, TC $1.000/USD, IDyCB vs Ganancias 33%.

---

## Razonamiento — antes de los números

El comercial dijo dos cosas: *"B1 y B2 son iguales — mismo cliente, mismo precio"* y *"libre de impuestos = sin IVA, sin nada, margen limpio"*. **Las dos están mal**.

### Encuadre por contrato — Hecho Imponible

| | **Contrato A** (MercadoFree) | **Variante B1** | **Variante B2** |
|---|---|---|---|
| **Cliente** | AR (RI) | Chile | Chile |
| **Lugar prestación** | CABA | CABA | CABA |
| **Utilización económica** | **AR** | **Chile** | **AR** (parejas filial AR) |
| **IVA** | Gravado 21% | **Exportación tasa 0%** | **Gravado 21%** |
| **IIBB** | Gravado 3% | Exento (exportación) | Gravado 3% |
| **Ganancias** | Sí (renta AR) | Sí (renta mundial residente, fuente AR) | Sí (renta AR) |

==**B1 ≠ B2.** B1 es exportación verdadera; B2 no lo es porque la utilización económica es en AR.==

### Qué significa "USD 15.000 libre de impuestos argentinos"

- En **B1** (exportación): no hay IVA débito ni IIBB → la cláusula no cambia nada porque no hay impuestos AR que aplicar al cliente.
- En **B2** (gravado en AR): la cláusula es **un costo para Polola**. La cátedra interpreta que Polola factura los USD 15.000 como neto e invoicea el IVA débito por encima (cliente lo paga), pero **el IIBB queda a cargo de Polola** porque la cláusula impide trasladárselo.

> Interpretación de cátedra para B2: ingreso neto = 15.000.000 + IVA débito 3.150.000 facturado al cliente. IIBB 450.000 lo absorbe Polola (sale como costo, no se traslada).

### Contrato A — precio "por todo concepto, impuestos incluidos"

Hay que sacarle el IVA de adentro:
- Total facturado: 7.260.000 = neto × 1,21
- **Neto = 7.260.000 / 1,21 = 6.000.000**
- **IVA débito = 1.260.000**
- **IIBB = 3% × 6.000.000 = 180.000**

### Strype Inc. — Importación de servicios (libre de retenciones)

- **IVA-RS**: 4.000.000 × 21% = **840.000** (neutro, CF mes siguiente)
- **Retención IIGG benef. exterior** (criterio simplificado de cátedra en este caso, sin presunción 90%): **4.000.000 × 31,5% = 1.260.000**, absorbida por Polola.
- **Costo deducible en IIGG** = 4.000.000 + 1.260.000 retención = **5.260.000**

> Nota: en este Caso III la cátedra calculó la retención **directamente al 31,5% sobre el bruto** (sin pasar por el margen 90% que sí usó en Caso I y II). Es un criterio de simplificación específico de este ejercicio — seguimos el cálculo cátedra.

---

## Opción B1 — Contrato A + Contrato B1 (exportación)

### Estado de Resultados

| Concepto | Importe |
|---|---:|
| Ingresos (A: 6.000.000 + B1: 15.000.000) | 21.000.000 |
| (−) IIBB (solo A, B1 exento) | (180.000) |
| (−) Costo Strype (4.000.000 + retención 1.260.000) | (5.260.000) |
| (−) Sueldos y cargas | (8.000.000) |
| (−) IDyCB (67% costo) | (151.956) |
| **Resultado antes IIGG** | **7.408.044** |
| (−) IIGG (30%) | (2.222.413,2) |
| ==**Resultado final**== | ==**5.185.630,8**== |

### Cashflow

| Concepto | Importe |
|---|---:|
| Ingresos con IVA (A: 7.260.000 + B1: 15.000.000) | 22.260.000 |
| (−) IIBB | (180.000) |
| (−) Costo Strype con IVA (4M + ret 1.260.000 + IVA-RS 840.000) | (6.100.000) |
| (−) Sueldos | (8.000.000) |
| (−) IVA saldo a pagar (débito A 1.260.000 − crédito 0) | (1.260.000) |
| (−) IDyCB | (226.800) |
| **Cashflow antes IIGG** | **6.493.200** |
| (−) IIGG | (2.222.413,2) |
| (+) Crédito IIGG por IDyCB 33% | 74.844 |
| ==**Cashflow del período**== | ==**4.345.630,8**== |

**IDyCB Opción B1**:
- Créditos: 22.260.000 × 0,6% = 133.560
- Débitos: 15.540.000 (180k IIBB + 6.100.000 Strype + 8M sueldos + 1.260.000 IVA) × 0,6% = 93.240
- Total: **226.800** → 67% costo (151.956) + 33% crédito IIGG (74.844)

---

## Opción B2 — Contrato A + Contrato B2 (gravado, "libre de impuestos" no aplica)

### Estado de Resultados

| Concepto | Importe |
|---|---:|
| Ingresos (A: 6.000.000 + B2: 15.000.000) | 21.000.000 |
| (−) IIBB (A: 180.000 + B2: 450.000) | (630.000) |
| (−) Costo Strype | (5.260.000) |
| (−) Sueldos | (8.000.000) |
| (−) IDyCB (67% costo) | (179.091) |
| **Resultado antes IIGG** | **6.930.909** |
| (−) IIGG (30%) | (2.079.272,7) |
| ==**Resultado final**== | ==**4.851.636,3**== |

### Cashflow

| Concepto | Importe |
|---|---:|
| Ingresos con IVA (A: 7.260.000 + B2: 18.150.000 = 15M + IVA 3.150.000) | 25.410.000 |
| (−) IIBB | (630.000) |
| (−) Costo Strype con IVA | (6.100.000) |
| (−) Sueldos | (8.000.000) |
| (−) IVA saldo a pagar (débito 1.260 + 3.150 = 4.410.000) | (4.410.000) |
| (−) IDyCB | (267.300) |
| **Cashflow antes IIGG** | **6.002.700** |
| (−) IIGG | (2.079.272,7) |
| (+) Crédito IIGG por IDyCB 33% | 88.209 |
| ==**Cashflow del período**== | ==**4.011.636,3**== |

**IDyCB Opción B2**:
- Créditos: 25.410.000 × 0,6% = 152.460
- Débitos: 19.140.000 (630k + 6.100k + 8M + 4.410k) × 0,6% = 114.840
- Total: **267.300** → 67% costo (179.091) + 33% crédito IIGG (88.209)

---

## Comparación B1 vs B2

| | **Opción B1** (verdadera exportación) | **Opción B2** (gravado AR) | Diferencia |
|---|---:|---:|---:|
| Resultado EERR | 5.185.630,8 | 4.851.636,3 | **(333.994,5)** |
| Cashflow del período | 4.345.630,8 | 4.011.636,3 | **(333.994,5)** |
| IIBB | 180.000 | 630.000 | +450.000 |
| IVA saldo pagar | 1.260.000 | 4.410.000 | +3.150.000 |

==**B1 deja ARS 334.000 más que B2** — la diferencia es el IIBB extra (450.000) menos su efecto en IIGG e IDyCB.==

---

## Conclusión — qué le decís al comercial

> *"Te equivocaste en dos cosas. **Primero**: B1 y B2 no son iguales. B1 es exportación de servicios verdadera porque las parejas están en Chile — IVA tasa 0% y IIBB exento. B2 NO es exportación, aunque el cliente sea chileno, porque las parejas están en AR (filial argentina) — IVA 21% e IIBB 3%."*
>
> *"**Segundo**: 'libre de impuestos argentinos' no nos salva del IVA ni del IIBB cuando el servicio se utiliza en AR. En B2, el IVA termina pagándolo Conecta Chile (lo facturamos arriba de los USD 15k), pero el IIBB queda a cargo nuestro como costo. Por eso B2 deja ARS 334.000 menos que B1."*

---

## Por qué este ejercicio

1. ==**Definición de exportación de servicios**==: depende del **lugar de utilización económica**, no del domicilio del cliente. Cliente del exterior + utilización en AR = NO es exportación.
2. ==**"Libre de impuestos argentinos" no neutraliza el IVA ni el IIBB**==: si el hecho imponible está en AR, los impuestos AR aplican. La cláusula contractual define quién los soporta económicamente.
3. ==**Contrato A — precio "todo concepto, impuestos incluidos"**==: requiere sacar el IVA de adentro: neto = total / 1,21.
4. ==**Importación de servicios (Strype) con "libre de retenciones"**==: retención IIGG absorbida (cátedra Caso III: 31,5% directo, sin presunción 90%) + IVA-RS neutro pero outflow inmediato.
5. ==**B1 vs B2 numéricamente diferentes**==: la diferencia ~ARS 334k es el IIBB extra que B2 paga.
6. ==**IDyCB siempre Resto**==: 67% costo + 33% crédito IIGG.

**Error típico 1**: pensar que B1 y B2 son iguales porque el cliente y el precio son iguales — la utilización económica cambia el encuadre.
**Error típico 2**: aceptar "libre de impuestos argentinos" como cláusula que elimina IVA débito (no lo hace si la operación es gravada en AR).
**Error típico 3**: no sacar el IVA de adentro del Contrato A (cobrar IIBB sobre 7.260.000 en lugar de 6.000.000).
**Error típico 4**: ignorar la retención IIGG sobre Strype (aunque sea libre de retenciones, el costo lo absorbe Polola).
**Error típico 5**: confundir IVA tasa 0% (B1, exportación) con exento → tasa 0% permite recuperar CF vinculado.

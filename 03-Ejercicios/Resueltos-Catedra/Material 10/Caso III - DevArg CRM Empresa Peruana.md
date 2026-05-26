# Material 10 — Caso III: DevArg SA — Desarrollo de CRM para empresa peruana

> Impuestos: [[IVA - Exportaciones]], [[IVA - Saldos a Favor]], [[Tax Credit]], [[IIBB - Exenciones y No Alcanzados]], [[IDyCB]]
> Status: ✅ Validado en clase

---

## Enunciado

CFO de DevArg SA (empresa argentina de software). Empresa peruana solicita desarrollo de CRM. Precio: USD 500.000 por todo concepto (impuestos argentinos incluidos). Retención peruana: USD 10.000.

DevArg subcontratará el 100% del trabajo. Opciones:
- **a.1** Empresa argentina, servicio prestado en Argentina: USD 450.000 + IVA (USD 94.500)
- **a.2** Empresa argentina, servicio prestado en Perú: USD 470.000 (sin IVA)
- **b** Empresa peruana: USD 430.000 + IVA peruano 18% (USD 77.400)

1. ¿Aceptaría el trabajo?
2. ¿Cuál de las 3 opciones genera mayor utilidad?

Tasas: Ganancias 30%, IVA 21%, IIBB 5%, Débitos 0,6%, Créditos 0,6%.

---

## Conceptos involucrados

- [[IVA - Exportaciones]] — tasa 0%, CF del proveedor recuperable como saldo a favor
- [[IVA - Saldos a Favor]] — CF de exportaciones: recuperable por devolución o compensación
- [[Tax Credit]] — retención peruana como crédito en Ganancias AR
- [[IIBB - Exenciones y No Alcanzados]] — exportación de servicios al exterior: exenta
- [[IDyCB]] — sobre débitos y créditos bancarios

---

## Resolución

### Naturaleza del ingreso de DevArg

DevArg factura a empresa peruana (no residente). El CRM se usará en Perú → **exportación de servicios → IVA tasa 0%, IIBB exento.**

Cobro efectivo: USD 500.000 − USD 10.000 (retención Perú) = **USD 490.000**

La retención peruana (USD 10.000) es **tax credit** en Ganancias AR (renta de fuente extranjera).

IDyCB sobre el cobro (igual en todas las opciones):
- Crédito bancario: 490.000 × 0,6% = **USD 2.940**

---

### Opción a.1: Empresa argentina en Argentina (USD 450.000 + IVA USD 94.500)

**IVA:**
- El proveedor factura USD 94.500 de IVA → CF para DevArg
- DF de DevArg: 0 (exportación, tasa 0%)
- **Saldo a favor técnico: USD 94.500 → recuperable** (devolución/acreditación por exportaciones)
- IVA no es costo real — es un activo financiero recuperable

Costo neto efectivo: **USD 450.000**

IDyCB: (cobro 490K × 0,6%) + (pago total incl. IVA 544.500 × 0,6%) = 2.940 + 3.267 = **USD 6.207**

| Concepto | Monto |
|---|---|
| Ingreso bruto | 500.000 |
| (−) Costo empresa AR | (450.000) |
| (−) IDyCB | (6.207) |
| Resultado antes Ganancias | 43.793 |
| Ganancias AR bruta (30%) | 13.138 |
| (−) Tax credit Perú | (10.000) |
| **Ganancias neta** | **3.138** |
| **Resultado neto** | **40.655** |

---

### Opción a.2: Empresa argentina en Perú (USD 470.000, sin IVA)

Servicio prestado en el exterior → fuera del objeto del IVA argentino → sin IVA en la factura del proveedor.

IDyCB: (cobro 490K × 0,6%) + (pago 470K × 0,6%) = 2.940 + 2.820 = **USD 5.760**

| Concepto | Monto |
|---|---|
| Ingreso bruto | 500.000 |
| (−) Costo empresa AR | (470.000) |
| (−) IDyCB | (5.760) |
| Resultado antes Ganancias | 24.240 |
| Ganancias AR bruta (30%) | 7.272 |
| (−) Tax credit Perú | (7.272) — consume todo el crédito |
| **Ganancias neta** | **0** |
| **Resultado neto** | **24.240** |

---

### Opción b: Empresa peruana (USD 430.000 + IVA peruano 18% = USD 507.400)

**IVA peruano (USD 77.400):** DevArg lo paga dentro del precio. No es recuperable en Argentina. **Costo real.**

**IVA argentino por importación de servicios:**
DevArg importa servicios desde Perú → responsable sustituto → ingresa 430.000 × 21% = USD 90.300 como CF → neutro (recuperable).

Costo efectivo: USD 507.400

IDyCB: (cobro 490K × 0,6%) + (pago 507.400 × 0,6%) = 2.940 + 3.044 = **USD 5.984**

| Concepto | Monto |
|---|---|
| Ingreso bruto | 500.000 |
| (−) Costo empresa peruana + IVA peruano | (507.400) |
| (−) IDyCB | (5.984) |
| **Resultado antes Ganancias** | **(13.384) — PÉRDIDA** |

Tax credit de Perú (USD 10.000) no se puede utilizar (no hay Ganancias que pagar).
**Resultado neto Opción b: −USD 13.384**

---

### Comparación final

| | a.1 (AR en AR) | a.2 (AR en Perú) | b (empresa peruana) |
|---|---|---|---|
| Ingreso bruto | 500.000 | 500.000 | 500.000 |
| Cobro efectivo | 490.000 | 490.000 | 490.000 |
| Costo operativo neto | 450.000 | 470.000 | 507.400 |
| IVA CF recuperable | 94.500 | 0 | 90.300 |
| Ganancias neta | 3.138 | 0 | 0 |
| Tax credit utilizado | 10.000 | 7.272 | 0 |
| **Resultado neto** | **40.655** | **24.240** | **(13.384)** |

**1. SÍ acepta el trabajo** (opciones a.1 y a.2 generan utilidad).

==**2. Mejor opción: a.1** — empresa argentina prestando en Argentina. Aunque su costo bruto es mayor (USD 544.500 con IVA), el IVA es recuperable como saldo a favor de exportaciones → costo neto real USD 450.000, el más bajo. Además maximiza el aprovechamiento del tax credit peruano.==

> [!note] Por qué a.1 le gana a a.2 si a.2 parece más barata
> En a.2 el proveedor cobra USD 470.000 (sin IVA). En a.1 cobra USD 450.000 + USD 94.500 IVA, pero el IVA lo recupera DevArg. Costo neto a.1 = USD 450.000 vs USD 470.000 de a.2 → a.1 es USD 20.000 más barata en términos reales. El CF de exportaciones es un activo financiero, no una pérdida.

---

## Por qué este ejercicio

1. **CF de exportaciones = activo recuperable**: en tasa 0%, el IVA que te cobra el proveedor local es recuperable. No es costo, es una inmovilización temporal de fondos.
2. **IVA del exterior = costo real**: el IVA peruano que paga DevArg a la empresa peruana no es recuperable en Argentina.
3. **Tax credit**: la retención peruana es tax credit solo si hay Ganancias que pagar. En la opción con pérdida (b), el crédito no se puede usar.
4. **Opciones de subcontratación**: el lugar donde presta el subcontratista determina si hay IVA en su factura.

==Error típico==: tratar el IVA del proveedor local como costo. En exportaciones, ese CF es recuperable por devolución o compensación ante AFIP.

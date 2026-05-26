# Material 10 — Caso II: ARGSecurity — Consultoría de seguridad para filial argentina de BMV

> Impuestos: [[IVA - Exportaciones]], [[IVA - Importacion de Servicios]], [[Ganancias - Beneficiarios del Exterior]], [[IDyCB]]
> Status: ✅ Validado en clase

---

## Enunciado

CFO de ARGSecurity (SA residente fiscal argentina, consultoría informática). BMV Alemania necesita consultoría en seguridad informática para su **filial argentina** (BMV Argentina). BMV Alemania paga USD 100.000 por todo concepto. Sin retención alemana.

- **Opción 1:** Empleados de ARGSecurity. Costo: USD 65.000 (sueldos + cargas sociales).
- **Opción 2:** Contratar empresa uruguaya. Costo: USD 85.000.

i) Calcule el resultado por opción e indique cuál es la más rentable.
ii) ¿Cuánto dinero necesita financieramente para cubrir costos + impuestos por opción?

Tasas: Ganancias 30%, IVA 21%, IIBB 5%, Débitos 0,6%, Créditos 0,6%, Retención Ganancias ARG sobre renta fuente argentina: 31,5%.

---

## Conceptos involucrados

- [[IVA - Exportaciones]] — por qué NO es exportación (utilización económica en AR)
- [[IVA - Importacion de Servicios]] — responsable sustituto al contratar empresa uruguaya
- [[Ganancias - Beneficiarios del Exterior]] — retención 31,5% sobre renta de fuente argentina
- [[IDyCB]] — débitos y créditos bancarios

---

## Resolución

### Punto crítico: ¿Por qué NO es exportación de servicios?

Aunque ARGSecurity factura a BMV **Alemania** (no residente), el servicio beneficia a BMV **Argentina** (residente AR) → la utilización económica es en Argentina.

> Fuente: **Lectura 4 — IVA Exportación de Servicios**: para que sea exportación, la utilización económica debe ser en el exterior. Aquí el beneficiario real es la filial argentina → **no es exportación de servicios**.

Consecuencias:
- **IVA: 21%** (no tasa 0%)
- **IIBB: 5%** (no exento)

Precio "todo incluido" = USD 100.000 → IVA incluido:
- Neto IVA = 100.000 / 1,21 = **USD 82.645**
- DF IVA = **USD 17.355**
- IIBB = 82.645 × 5% = **USD 4.132**

---

### Opción 1: Empleados propios (costo USD 65.000)

CF de IVA: USD 0 (sueldos no generan CF)
IVA a ingresar: USD 17.355

IDyCB: (cobro 100K × 0,6%) + (sueldos 65K × 0,6%) = 600 + 390 = **USD 990**

| Concepto | Monto |
|---|---|
| Ingreso neto IVA | 82.645 |
| (−) Sueldos | (65.000) |
| (−) IIBB | (4.132) |
| (−) IDyCB | (990) |
| Resultado antes Ganancias | 12.523 |
| Ganancias (30%) | (3.757) |
| **Resultado neto** | **8.767** |

**Necesidad financiera antes de cobrar:**

| Concepto | Monto |
|---|---|
| Sueldos | 65.000 |
| IVA a ingresar | 17.355 |
| IIBB | 4.132 |
| IDyCB | 990 |
| **Total** | **87.477** |

---

### Opción 2: Empresa uruguaya (costo USD 85.000)

**IVA:**
ARGSecurity contrata empresa uruguaya para un servicio utilizado en Argentina → importación de servicios → ARGSecurity actúa como **responsable sustituto**:

- IVA importación de servicios (CF): 85.000 × 21% = **USD 17.850**
- DF: USD 17.355 / CF: USD 17.850 → **saldo a favor USD 495** (no paga IVA neto)

**Retención Ganancias:**
ARGSecurity debe actuar como agente de retención al pagar a la empresa uruguaya (renta de fuente argentina → Art. 93 inc. h):

- Retención: 85.000 × 31,5% = **USD 26.775**
- Pago neto a Uruguay: 85.000 − 26.775 = USD 58.225
- Ingresa a AFIP: USD 26.775
- Costo total para ARGSecurity: **USD 85.000** (distribuido entre proveedor y fisco)

IDyCB: (cobro 100K × 0,6%) + (pago bruto 85K × 0,6%) = 600 + 510 = **USD 1.110**

| Concepto | Monto |
|---|---|
| Ingreso neto IVA | 82.645 |
| (−) Costo empresa uruguaya | (85.000) |
| (−) IIBB | (4.132) |
| (−) IDyCB | (1.110) |
| **Resultado antes Ganancias** | **(7.597) — PÉRDIDA** |

Sin Ganancias a pagar. **Resultado neto Opción 2: −USD 7.597**

**Necesidad financiera:**

| Concepto | Monto |
|---|---|
| Pago empresa uruguaya | 85.000 |
| IVA importación de servicios (recuperable al mes siguiente) | 17.850 |
| IIBB | 4.132 |
| IDyCB | 1.110 |
| **Total bruto** | **108.092** |

---

### Comparación y conclusión

| | Opción 1 (empleados) | Opción 2 (empresa UY) |
|---|---|---|
| Ingreso neto IVA | 82.645 | 82.645 |
| Costo operativo | 65.000 | 85.000 |
| IVA neto a ingresar | 17.355 | 0 (saldo a favor) |
| IIBB | 4.132 | 4.132 |
| Resultado antes Ganancias | 12.523 | (7.597) |
| Ganancias | 3.757 | 0 |
| **Resultado neto** | **8.767** | **(7.597)** |
| Necesidad financiera | 87.477 | 108.092 |

==**OPCIÓN 1 es la única rentable.** La Opción 2 genera pérdida: el ingreso neto IVA (USD 82.645) no alcanza para cubrir el costo de la empresa uruguaya (USD 85.000).==

> [!warning] Trampa del proveedor del exterior
> A primera vista, contratar la empresa uruguaya parece una opción válida. El error es no identificar que la utilización económica en Argentina hace que el ingreso sea de IVA 21% (reduciendo el neto a 82.645), mientras que el costo del proveedor (85.000) supera ese neto. Hay que identificar la naturaleza del servicio antes de evaluar opciones.

---

## Por qué este ejercicio

1. **Identificar la utilización económica**: el cliente facturado (BMV Alemania) ≠ quien utiliza el servicio (BMV Argentina). La utilización define el tratamiento IVA.
2. **Responsable sustituto + retención Ganancias en paralelo**: al contratar empresa uruguaya, ARGSecurity tiene dos obligaciones simultáneas (IVA y Ganancias).
3. **Necesidad financiera vs resultado neto**: la Opción 2 tiene mayor necesidad financiera Y genera pérdida — doble problema.

==Error típico==: confundir al cliente que paga (no residente) con la utilización económica del servicio. BMV Alemania paga pero el servicio lo usa BMV Argentina → IVA 21%, IIBB 5%.

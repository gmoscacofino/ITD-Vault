# Recuperatorio 2do Cuatrimestre 2025 — Resolución

> Status: ✅ Bien resuelto y chequeado por la cátedra
> Ver consigna completa en [[Consigna]]

---

## Conceptos involucrados

- [[IVA - Exportaciones]] — producción de contenido para exhibición 100% en exterior → tasa 0%
- [[IIBB - Exenciones y No Alcanzados]] — exportación de servicios: exenta (efectivizada en exterior)
- [[Tax Credit]] — retenciones CDI: fuente AR (A1) → costo; fuente extranjera (A2) → tax credit
- [[Ganancias - Beneficiarios del Exterior]] — Gordon Ramsay: CDI Argentina-UK 10%; gross-up porque Tubo Quita absorbe el impuesto
- [[IVA - Importacion de Servicios]] — A1: responsable sustituto por servicio de Gordon (prestado en AR); CF recuperable
- [[IDyCB]] — 0,6% ingreso + 0,6% egreso; régimen Resto: 2/3 costo + 1/3 crédito Ganancias

---

## Encuadre previo

### Distribución del uso (proporción de ventas)

| País | Facturación | % |
|---|---|---|
| Chile | USD 1.000.000 | **10%** |
| Brasil | USD 4.000.000 | **40%** |
| México | USD 5.000.000 | **50%** |
| **Total** | **USD 10.000.000** | **100%** |

→ 100% de uso en el exterior → **exportación total de servicios**.

### IVA sobre ingresos

- Servicio utilizado 100% en Chile, Brasil, México → **IVA tasa 0%**
- No hay gross-down: el precio USD 420.000 es íntegramente ingreso neto (sin IVA argentino)

### IIBB

- Exportación de servicios efectivizada en el exterior → **exenta** en ambas opciones (IIBB = 0)

### Retenciones CDI sobre el ingreso de Tubo Quita

| | A1 (en Argentina) | A2 (en Chile) |
|---|---|---|
| Lugar de prestación | Argentina | Chile |
| Fuente | **Argentina** | **Extranjera** |
| Retenciones Chile/Brasil/México (10% c/u × 140.000 c/u) | **Costo** | **Tax credit** |
| Total retenciones | USD 42.000 | USD 42.000 |

Cobro efectivo de BHO: 420.000 − 42.000 = **USD 378.000**

---

## Referencia A — Ingreso

En ambas opciones: **USD 420.000** (tasa 0% IVA → sin gross-down).

---

## Referencia B — Costos

### Gordon Ramsay en Argentina (A1 únicamente)

Acuerdo: USD 20.000 neto por episodio × 8 = **USD 160.000** en mano.  
Tubo Quita absorbe los impuestos argentinos → gross-up.

**Retención CDI Argentina–UK (10%):**
```
Bruto = 160.000 / (1 − 0,10) = 177.777,78
Retención a AFIP = 177.777,78 × 10% = 17.777,78
```

**IVA — Responsable sustituto (servicio prestado en AR):**

El IVA como responsable sustituto es CF recuperable → no es costo económico, pero sí egreso de caja real. Fórmula del examen (gross-up IVA sobre el neto):
```
IVA = 160.000 × 21% / (1 − 21%) = 160.000 × 21/79 = 42.531,65
```
→ IVA CF recuperable al mes siguiente (no costo en P&L, sí en caja).

**¿Por qué no hay retención Ganancias sobre Gordon en A2?**  
Si Gordon graba en Chile → servicio prestado en el exterior → no hay obligación fiscal argentina sobre su honorario.

### Costos totales por opción (8 episodios)

| Concepto | A1 (Argentina) | A2 (Chile) |
|---|---|---|
| Contratación Gordon | 160.000 | 160.000 |
| Retención Gordon (costo) | **17.777,78** | — |
| IVA Gordon (CF recuperable) | *(42.531,65)* | — |
| Sueldos | 40.000 | 40.000 |
| Alojamiento | 40.000 | 32.000 |
| IVA alojamiento (CF recuperable) | *(8.400)* | — |
| Viáticos y alimentos | — | 12.000 |
| Proveedores AR | 16.000 | — |
| IVA proveedores AR (CF recuperable) | *(3.360)* | — |
| Proveedores Chile (con IVA chileno, irrecuperable) | — | 32.000 |
| **Costo total en P&L** | **273.777,78** | **244.000** |

> Los IVA marcados con *(cursiva)* son CF recuperables → no son costos en P&L, pero sí son egresos bancarios que generan IDyCB (Ref. D).

---

## Referencia C — IDyCB sobre ingresos

Cobro bancario efectivo: 420.000 − 42.000 (retenciones) = USD 378.000

```
IDyCB total   = 378.000 × 0,6% = 2.268
Régimen Resto → 2/3 costo = 1.512 | 1/3 crédito Ganancias = 756
```

---

## Referencia D — IDyCB sobre egresos

Base = suma de todos los egresos bancarios reales (incluyendo IVA, aunque sea recuperable).

| Concepto | A1 | A2 |
|---|---|---|
| Gordon neto | 160.000 | 160.000 |
| IVA Gordon (CF recuperable, pero egreso real) | 42.531,65 | — |
| Retención Gordon a AFIP | 17.777,78 | — |
| Sueldos | 40.000 | 40.000 |
| Alojamiento (sin IVA para A2) | 40.000 | 32.000 |
| IVA alojamiento AR | 8.400 | — |
| Viáticos y alimentos | — | 12.000 |
| Proveedores | 16.000 | 32.000 |
| IVA proveedores AR | 3.360 | — |
| **Total egresos bancarios** | **327.069,43** | **276.000** |
| IDyCB (0,6%) | 1.962,42 | 1.656 |
| **Costo (2/3)** | **1.278,68** | **1.104** |
| Crédito Ganancias (1/3) | 639,34 | 552 |

> Nota: El IVA de proveedores AR y alojamiento AR es CF recuperable para Tubo Quita (exportadora), pero es un egreso bancario real → genera IDyCB. Ídem IVA Gordon como responsable sustituto.

---

## Resultado antes de Ganancias

| Concepto | A1 | A2 |
|---|---|---|
| Ingreso | 420.000 | 420.000 |
| (−) Contratación Gordon | (160.000) | (160.000) |
| (−) Retención Gordon | **(17.777,78)** | — |
| (−) Sueldos | (40.000) | (40.000) |
| (−) Alojamiento | (40.000) | (32.000) |
| (−) Viáticos y alimentos | — | (12.000) |
| (−) Proveedores | (16.000) | (32.000) |
| (−) IDyCB ingresos (2/3) | (1.512) | (1.512) |
| (−) IDyCB egresos (2/3) | (1.278,68) | (1.104) |
| **Resultado antes Ganancias** | **143.431,54** | **141.384** |

---

## Ganancias y retenciones

**A1 — Fuente argentina:**
- Retenciones CDI de Chile/Brasil/México → **COSTO** (no tax credit: fuente argentina)
- Ganancias = 143.431,54 × 30% = **43.029,46** (paga a AFIP)
- Retenciones (costo adicional) = **42.000**

**A2 — Fuente extranjera:**
- Retenciones CDI → **TAX CREDIT** (compensa contra Ganancias AR)
- Ganancias = 141.384 × 30% = **42.415,20** (bruto)
- Tax credit disponible: 42.000 → Ganancias neta AFIP = 415,20
- Costo económico total de Ganancias: 42.415,20 (42.000 ya pagados vía retenciones + 415,20 a AFIP)

---

## Resultado final y rentabilidad

| Concepto | A1 | A2 |
|---|---|---|
| Resultado antes Ganancias | 143.431,54 | 141.384 |
| (−) Ganancias | (43.029,46) | (42.415,20) |
| (−) Retenciones (costo en A1) | **(42.000)** | — *(tax credit)* |
| ==**Resultado final**== | ==**58.402,08**== | ==**98.968,80**== |
| Costos totales | 361.597,92 | 321.031,20 |
| **Rentabilidad sobre costos** | **16,15%** | **30,83%** |
| Criterio (≥ 30%) | ❌ RECHAZA | ✅ ACEPTA |

---

## Respuestas

### i) ¿Se acepta la propuesta?

==**SÍ se acepta, pero SOLO la Opción A2 (grabar en Chile).**==

- A1 (Argentina): 16,15% sobre costos → **bajo el umbral mínimo del 30%** → se descarta.
- A2 (Chile): 30,83% sobre costos → **supera el mínimo requerido** → se acepta.

### ii) ¿Cuánto dinero se necesita para contratar a Gordon Ramsay?

| Concepto | Gordon en Argentina | Gordon en Chile |
|---|---|---|
| Honorario neto | 160.000 | 160.000 |
| Retención CDI AR–UK (costo absorbido) | 17.777,78 | — |
| IVA responsable sustituto (CF recuperable, necesidad financiera) | 42.531,65 | — |
| **Total necesario** | ==**220.309,43**== | ==**160.000**== |

> El IVA (42.531,65) es CF recuperable al mes siguiente, pero representa una necesidad financiera real hasta su recupero.  
> En Chile: no hay retención ni IVA argentino → solo el honorario neto.

---

## Por qué este parcial

Evalúa 6 conceptos integrados en una sola decisión de producción:

1. ==**Distribución de uso → exportación total**==: la proporción de ventas (Chile 10%, Brasil 40%, México 50%) determina que el 100% del servicio se usa en el exterior → IVA tasa 0%, IIBB exenta en ambas opciones.

2. ==**Lugar de prestación del servicio determina fuente y tax credit**==: filmado en Argentina = fuente argentina → retenciones CDI son costo. Filmado en Chile = fuente extranjera → retenciones CDI son tax credit.

3. ==**Gross-up cuando el proveedor cobra neto de impuestos**==: Gordon recibe 160.000 en mano → hay que gross-up para determinar cuánto debe facturar Tubo Quita como base de retención.

4. ==**IVA responsable sustituto: no costo, pero sí necesidad financiera**==: el IVA de Gordon (servicio en AR) es CF recuperable el mes siguiente → no aparece en el P&L como costo, pero Tubo Quita necesita 42.531,65 de liquidez hasta recuperarlo.

5. ==**IDyCB sobre todos los egresos bancarios**==: incluyendo el IVA pagado como responsable sustituto, aunque sea recuperable → genera IDyCB sobre el egreso real.

6. ==**Rentabilidad sobre costos como criterio de decisión**==: no basta con que el resultado sea positivo; hay que verificar que rentabilidad = resultado / costos ≥ 30%.

**Errores típicos de este parcial:**
- Incluir el IVA de Gordon como costo (no lo es: es CF recuperable)
- Tratar las retenciones CDI como tax credit en A1 (fuente argentina = costo, no crédito)
- No calcular la distribución de uso (Chile/Brasil/México) antes de encuadrar IVA e IIBB
- No incluir el IVA de alojamiento/proveedores AR en la base de IDyCB egresos
- Calcular rentabilidad sobre ingreso en vez de sobre costos

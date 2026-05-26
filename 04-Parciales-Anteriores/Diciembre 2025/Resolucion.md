# Parcial Diciembre 2025 — Resolución

> Status: ✅ Bien resuelto y chequeado por la cátedra
> Ver consigna completa en [[Consigna]]

---

## Conceptos involucrados

- [[IVA - Exportaciones]] — exportación parcial: porción AR gravada 21% (si se presta en AR); porción BR tasa 0% o fuera de objeto
- [[IVA - Concepto y Logica]] — precio "todo incluido" → gross-down para obtener neto gravado
- [[IIBB - Exenciones y No Alcanzados]] — exportación de servicios al exterior: exenta cuando se efectiviza en BR
- [[Tax Credit]] — retención Italia: fuente AR → costo; fuente extranjera → tax credit (compensa exactamente)
- [[IDyCB]] — 0,6% sobre ingresos + 0,6% sobre egresos; régimen "Resto": 2/3 costo + 1/3 crédito Ganancias
- [[IVA - Importacion de Servicios]] — A3: proveedor brasilero → responsable sustituto por porción usada en AR
- [[Ganancias - Beneficiarios del Exterior]] — A3: retención 31,5% sobre renta de fuente AR del proveedor brasilero

---

## Encuadre previo: distribución del ingreso

El sistema se usa en proporción a las ventas de cada entidad:

| Jurisdicción | Ventas | % |
|---|---|---|
| Argentina | USD 25M | **25%** |
| Brasil | USD 75M | **75%** |

Precio total "todo concepto" = USD 100.000.
EG Italia practica retención 10% → Dosazero cobra efectivamente **USD 90.000**.

---

## Análisis por opción

### Determinación de ingresos (Ref. A)

| Concepto | A1 (en AR) | A2 (en BR, propio) | A3 (en BR, proveedor) |
|---|---|---|---|
| Porción AR (25%) | **20.661,16** | **25.000** | **25.000** |
| Porción BR (75%) | 75.000 | 75.000 | 75.000 |
| **Ingreso total** | **95.661,16** | **100.000** | **100.000** |

**¿Por qué la porción AR de A1 es 20.661,16 y no 25.000?**

En A1 el servicio se presta físicamente en Argentina y se utiliza en Argentina → **IVA 21% aplica** sobre esa porción. El precio es "todo incluido" → el IVA está dentro del precio → hay que hacer gross-down:

```
25.000 / 1,21 = 20.661,16 (neto gravado)
IVA incluido  =  4.338,84
```

En A2 y A3 el servicio se presta en Brasil → **fuera del objeto del IVA argentino** → la porción AR no tiene IVA → ingreso neto = 25.000.

La porción BR (75.000) en los 3 casos: exportación de servicios o fuera del objeto → sin IVA.

---

### IIBB (Ref. B)

| Opción | IIBB | Fundamento |
|---|---|---|
| A1 | **619,83** | Porción AR gravada: 20.661,16 × 3% |
| A2 | 0 | Servicio efectivizado en Brasil → **exento** (exportación) |
| A3 | 0 | Ídem |

---

### IDyCB sobre ingresos (Ref. C)

En todas las opciones, Dosazero cobra **USD 90.000** (100.000 − 10.000 retención Italia):

```
IDyCB total    = 90.000 × 0,6% = 540
Régimen Resto  → 2/3 costo (pérdida) + 1/3 crédito Ganancias
Costo (2/3)    = 360
Crédito (1/3)  = 180
```

---

### IDyCB sobre egresos (Ref. D)

Los egresos bancarios generan IDyCB del mismo modo (2/3 costo + 1/3 crédito):

| Egreso | A1 | A2 | A3 |
|---|---|---|---|
| Costo laboral | 35.000 | 35.000 | 42.000 |
| Viáticos/hotelería | — | 15.000 | — |
| IIBB | 619,83 | — | — |
| IVA a ingresar (A1) | 4.338,84 | — | — |
| IVA importación de servicios (A3) | — | — | 2.205 |
| **Total egresos** | **39.958,67** | **50.000** | **44.205** |
| IDyCB (0,6%) | 239,75 | 300 | 265,23 |
| **Costo (2/3)** | **159,83** | **200** | **176,82** |
| Crédito (1/3) | 79,92 | 100 | 88,41 |

**A3 — IVA importación de servicios (USD 2.205):**

El proveedor brasilero presta el servicio en Brasil, pero el 25% se utiliza en Argentina → esa porción es **importación de servicios** → Dosazero actúa como responsable sustituto:

```
42.000 × 25% × 21% = 2.205 (CF recuperable → no es costo neto)
```

El IVA es CF recuperable para Dosazero (neutro en el estado de resultados), pero genera un egreso bancario real → incluido en la base IDyCB.

---

### Resultado antes de Ganancias

| Concepto | A1 | A2 | A3 |
|---|---|---|---|
| Ingreso total | 95.661,16 | 100.000 | 100.000 |
| (−) Costo laboral/proveedor | (35.000) | (35.000) | (42.000) |
| (−) Viáticos | — | (15.000) | — |
| (−) IIBB | (619,83) | — | — |
| (−) IDyCB ingresos (2/3) | (360) | (360) | (360) |
| (−) IDyCB egresos (2/3) | (159,83) | (200) | (176,82) |
| **Resultado antes Ganancias** | **59.521,49** | **49.440** | **57.463,18** |

---

### Ganancias y retención Italia

**A1 — Servicio en Argentina → fuente argentina:**
- Retención Italia (10%) = **COSTO** (no aplica tax credit)
- Ganancias = 59.521,49 × 30% = 17.856,45
- Retención Italia (costo adicional) = 10.000

**A2 y A3 — Servicio en Brasil → fuente extranjera:**
- Retención Italia (10%) = **TAX CREDIT** → compensa exactamente la Ganancias que reduce
- Ganancias bruta A2 = 49.440 × 30% = 14.832; tax credit 10.000 → net AFIP = 4.832
- Pero el costo económico = 14.832 (la retención ya "salió" y el crédito la compensó)
- Ganancias bruta A3 = 57.463,18 × 30% = 17.238,95; idem

> **Lógica del tax credit:** Dosazero cobra 90.000 (no 100.000) porque Italia retuvo 10.000. Para la declaración argentina incluye el bruto (100.000) y computa el tax credit de 10.000. El efecto neto en caja es idéntico a si no hubiera retención: el crédito compensa exactamente la pérdida. Por eso en A2/A3 las retenciones muestran 0 — no es costo adicional, ya está implícito.

---

### Resultado final

| Concepto | A1 | A2 | A3 |
|---|---|---|---|
| Resultado antes Ganancias | 59.521,49 | 49.440 | 57.463,18 |
| (−) Ganancias | (17.856,45) | (14.832) | (17.238,95) |
| (−) Retención Italia (costo) | **(10.000)** | — | — |
| ==**Resultado final**== | ==**31.665,04**== | ==**34.608**== | ==**40.224,23**== |

---

## Respuestas

### iii) ¿Se acepta la propuesta?

==**SÍ se acepta.** Las 3 opciones generan ganancia.==

### iv) ¿Cuál es la más rentable?

==**Opción A3 (proveedor brasilero): USD 40.224,23** — la más rentable de las tres.==

| Ranking | Opción | Resultado |
|---|---|---|
| 🥇 | A3 — Proveedor brasilero | USD 40.224,23 |
| 🥈 | A2 — Personal propio en Brasil | USD 34.608,00 |
| 🥉 | A1 — Personal propio en Argentina | USD 31.665,04 |

---

## Por qué este parcial

Evalúa 6 conceptos integrados en una sola decisión empresarial:

1. ==**Precio "todo incluido" → gross-down**==: cuando el IVA está incluido en el precio pactado, el neto gravado es precio/1,21. Si no se hace, se sobreestima el ingreso.

2. ==**Exportación parcial**==: el mismo servicio puede ser IVA 21% en una porción (uso en AR) y tasa 0% o fuera de objeto en otra (uso en BR), según dónde se efectiviza.

3. ==**Lugar de prestación determina fuente**==: prestado en AR = fuente argentina → retención Italia es costo. Prestado en BR = fuente extranjera → retención Italia es tax credit.

4. ==**Tax credit que se cancela a sí mismo**==: cuando el tax credit < Ganancias AR, el efecto neto en caja es neutro (la retención exterior y el crédito se compensan). No hay doble imposición.

5. ==**IDyCB sobre egresos incluye el IVA pagado a AFIP**==: el pago de IVA como responsable sustituto o el IVA neto a ingresar son egresos bancarios reales → generan IDyCB.

6. ==**Responsable sustituto proporcional (A3)**==: si el proveedor extranjero presta un servicio usado parcialmente en Argentina, la importación de servicios aplica solo sobre esa proporción.

**Errores típicos de este parcial:**
- No hacer gross-down del precio en A1 → sobreestima ingreso AR en USD 4.338
- Tratar la retención Italia como costo en A2/A3 → subestima resultado en USD 10.000
- No incluir IDyCB sobre el pago de IVA en los egresos → subestima IDyCB
- Aplicar IIBB sobre el ingreso bruto (100.000) en A1 en lugar del neto gravado (20.661,16)

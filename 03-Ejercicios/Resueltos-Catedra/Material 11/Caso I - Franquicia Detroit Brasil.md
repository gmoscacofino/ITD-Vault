# Material 11 — Caso I: Franquicia DETROIT en Brasil

> Impuestos: [[Ganancias - Residentes y Fuente Mundial]], [[Tax Credit]], [[IVA - Exportaciones]], [[IIBB - Exenciones y No Alcanzados]], [[IDyCB]]
> Status: ✅ Validado en clase

---

## Enunciado

CFO de **American Food SA** (residente fiscal argentina), cadena DETROIT. Modelo: 2 restaurants propios + 28 franquiciados en Argentina. Franquicias por 5 años incluyen: i) servicios de asesoramiento, ii) cesión de uso de la marca.

Un grupo económico brasilero ofrece **USD 600.000/año por todo concepto, neto de la retención del Impuesto a la Renta de Brasil del 10%**.

Se solicita: indicar el monto de **ingresos netos anuales** (ingresos menos el efecto de Ganancias, IVA, IIBB e IDyCB).

Tasas: Ganancias 30%, IVA 21%, IIBB 5%, IDyCB 1,2% (0,6% débito / 0,6% crédito).

---

## Conceptos involucrados

- [[Gross-up]] — a partir del neto cobrado, calcular el bruto declarable
- [[Tax Credit]] — retención brasilera como crédito de impuesto
- [[IVA - Exportaciones]] — exportación de servicios, tasa 0%
- [[IIBB - Exenciones y No Alcanzados]] — exportación de servicios exenta
- [[IDyCB]] — sobre el crédito bancario al cobrar

---

## Resolución

### Paso 1 — Gross-up del valor de la franquicia

USD 600.000 es el neto cobrado **después** de la retención brasilera del 10%:

```
X × (1 − 0,10) = 600.000
X = 600.000 / 0,90 = 666.667 (valor bruto)
Retención Brasil = 66.667
Cobro efectivo   = 600.000
```

Para Ganancias Argentina, el residente declara la **renta mundial al valor bruto** (USD 666.667).

### Paso 2 — IVA: exportación de servicios, tasa 0%

| Requisito exportación de servicios | Cumplimiento |
|---|---|
| Lugar de prestación: Argentina | ✅ American Food opera desde AR |
| Cliente no residente | ✅ Grupo brasilero |
| Utilización económica en el exterior | ✅ Restaurants en Brasil |

==**IVA = 0 (tasa 0%, no exenta). Permite recuperar CF vinculado.**==

### Paso 3 — IIBB: exenta (exportación de servicios)

El servicio se presta a cliente del exterior para ser utilizado en Brasil.

==**IIBB = 0**== (exención por exportación de servicios que se efectiviza en el exterior).

### Paso 4 — IDyCB

Al cobrar, American Food acredita USD 600.000 en cuenta bancaria:

```
Crédito bancario: 600.000 × 0,6% = USD 3.600
```

### Paso 5 — Ganancias con tax credit Brasil

| Concepto | Monto |
|---|---|
| Ingreso bruto devengado | 666.667 |
| Ganancias AR (30%) | 200.000 |
| (−) Tax credit Brasil | (66.667) |
| ==**Ganancias AR neta**== | ==**133.333**== |

**Límite del tax credit:** 666.667 × 30% = 200.000. Tax credit disponible (66.667) < límite → se computa la totalidad.

### Paso 6 — Resultado

| Impuesto | Monto |
|---|---|
| IVA | 0 |
| IIBB | 0 |
| IDyCB | 3.600 |
| Ganancias neta | 133.333 |
| **Total impuestos** | **136.933** |

| Concepto | Flujo de caja | Base devengada |
|---|---|---|
| Cobro efectivo / Ingreso bruto | 600.000 | 666.667 |
| (−) Ganancias neta | (133.333) | (133.333) |
| (−) IDyCB | (3.600) | (3.600) |
| ==**Ingresos netos**== | ==**463.067**== | **529.734** |

La diferencia entre columnas (USD 66.667) es la retención brasilera: se declara como ingreso en AR (renta mundial) y se usa como tax credit, pero **no se cobra en efectivo**.

---

## Variante — sin tax credit

Si no pudiera computarse el tax credit (impuesto no análogo, sin convenio):

```
Ganancias AR: 200.000 (sin crédito)
Ingresos netos en caja: 600.000 − 200.000 − 3.600 = USD 396.400
El tax credit vale USD 66.667 de diferencia.
```

---

## Por qué este ejercicio

1. ==Gross-up al revés==: del neto cobrado al bruto declarable.
2. ==Tax credit== con verificación del límite de alícuota argentina.
3. ==Identificación de exportación de servicios== en IVA (tasa 0%) y IIBB (exenta).
4. ==IDyCB sobre el crédito bancario==.
5. ==Distinción flujo de caja vs base devengada==.

**Error típico 1:** calcular Ganancias sobre 600.000 en vez de 666.667. Subestima impuesto y tax credit.
**Error típico 2:** confundir exportación "exenta" con tasa 0%. Son distintas: tasa 0% permite recuperar CF.
**Error típico 3:** omitir IDyCB.

# Material 09 — Caso V: IVA e IIBB — Automotriz con cuotas en USD pagadas en pesos

> Impuestos: [[IVA - Nacimiento del Hecho Imponible]], [[IVA - Diferencias de Cambio]], [[IIBB - Hecho Imponible]]
> Status: ✅ Validado en clase

---

## Enunciado

CFO filial argentina de multinacional alemana (BVMM). Autos fabricados en Alemania, importados y vendidos en Argentina con 50% de mark-up, facturados en **pesos al tipo de cambio oficial**.

Nueva propuesta: pago inicial + saldo en USD a TC oficial pagadero en pesos en 3 cuotas semestrales (respetando el TC oficial al momento de cada vencimiento).

Alícuota IVA: 21%. Alícuota IIBB: 5%.

1. ¿Qué porcentaje del precio debería contener el pago inicial?
2. ¿Qué problemáticas tiene este formato en IVA e IIBB y cómo resolverlas?

---

## Conceptos involucrados

- [[IVA - Nacimiento del Hecho Imponible]] — nace al entregar el bien (antes de cobrar las cuotas)
- [[IVA - Diferencias de Cambio]] — gravadas por teoría de la unicidad al cobrar cuotas a TC mayor
- [[IIBB - Hecho Imponible]] — devengamiento anual, anticipos mensuales

---

## Resolución

**Estructura del precio (ejemplo con USD 50.000 de importación):**
```
Costo importación: USD 50.000  (CF IVA = USD 10.500)
Precio de venta:   USD 75.000  (50% mark-up)
Neto gravado:      75.000 / 1,21 = USD 61.983
DF IVA:            USD 13.017
IVA a pagar:       13.017 - 10.500 = USD 2.517
IIBB a ingresar:   61.983 × 5% = USD 3.099
```

### 1. Porcentaje mínimo del pago inicial

Al momento de la entrega del auto nace el HI de IVA y se devenga el ingreso de IIBB. Ambos deben pagarse **antes de cobrar las cuotas futuras**.

```
Pago inicial mínimo = IVA a pagar + IIBB = 2.517 + 3.099 = USD 5.616
% sobre precio total = 5.616 / 75.000 = 7,49%
```

> [!note] Para el parcial
> Responder el **porcentaje mínimo**, no el monto. El enunciado pide ese dato.

==El pago inicial mínimo es el **7,49% del precio total** para cubrir IVA + IIBB al momento de la venta sin financiar impuestos con fondos propios.==

> [!note] Restricción práctica
> No se puede pedir que el pago inicial sea del 100% porque el objetivo comercial es vender autos en cuotas. El mínimo es cubrir los impuestos que nacen en el momento de la entrega.

### 2. Problemáticas en IVA e IIBB

**Problemática 1 — IVA: diferencias de cambio gravadas**

El HI de IVA nace al momento de la entrega. Si el TC sube al cobrar las cuotas futuras, la diferencia de cambio **está gravada con IVA** (teoría de la unicidad: lo accesorio sigue lo principal).

> Fuente: **Lectura 5 — Las Diferencias de Cambio en el IVA**: *"Las Diferencias de cambio están gravadas con IVA por teoría de la UNICIDAD."*

| | Cuota 1 | Cuota 2 | Cuota 3 |
|---|---|---|---|
| TC al momento de la venta | $1.000/USD | $1.000/USD | $1.000/USD |
| TC al momento del cobro | $1.500/USD | $2.000/USD | $2.500/USD |
| Diferencia de cambio | $500/USD | $1.000/USD | $1.500/USD |
| Gravada en IVA | ==SÍ== | ==SÍ== | ==SÍ== |

**Solución:** emitir comprobante adicional por cada diferencia de cambio al cobrar cada cuota.

---

**Problemática 2 — IVA: nacimiento del HI antes de cobrar (riesgo de liquidez)**

La empresa paga IVA sobre el precio total en el momento de la entrega, pero cobra en cuotas a lo largo de 18 meses.

**Solución:** pago inicial suficiente para cubrir el IVA neto (≥ 7,49% del precio).

---

**Problemática 3 — IIBB: devengamiento y diferencias de cambio**

IIBB grava los ingresos brutos **devengados**. En el mes de la venta se devenga el ingreso total. Cuando se cobran las cuotas a TC mayor, la diferencia es ingreso adicional gravado en IIBB del período de cobro.

**Solución:** declarar las diferencias de cambio como ingreso adicional en la liquidación de IIBB del período en que se cobren.

---

**Problemática 4 — Riesgo de incobrabilidad**

Los impuestos ya fueron abonados. Si el cliente no paga, el recupero es complejo en ambos impuestos.

**Solución:** pago inicial suficiente + documentar correctamente los contratos para facilitar el recupero.

---

| Impuesto | Problemática | Solución |
|---|---|---|
| IVA | Diferencias de cambio gravadas al cobrar cuotas a TC mayor | Comprobante adicional por diferencia en cada vencimiento |
| IVA | Impuesto devengado antes de cobrar → riesgo de liquidez | Pago inicial ≥ 7,49% del precio total |
| IIBB | Diferencias de cambio son ingreso adicional gravado | Declarar diferencias en el período de cobro |
| Ambos | Incobrabilidad de cuotas futuras con impuestos ya pagados | Pago inicial suficiente; documentar contratos |

> [!note] Alternativa: Leasing
> El leasing evita algunas problemáticas (no se transfiere la propiedad hasta el ejercicio de la opción). Pero en Argentina tiene el problema de que los tomadores deterioran el bien y las cuotas resultan muy caras. Funciona bien en USA pero no en AR.

---

## Por qué este ejercicio

Combina nacimiento del HI, diferencias de cambio y liquidez:
1. **Nacimiento del HI en IVA**: ocurre al entregar el bien, no al cobrar. El impuesto nace antes que el efectivo.
2. **Diferencias de cambio en IVA**: teoría de la unicidad hace que el aumento del TC genere DF adicional en el futuro.
3. **Pago inicial como herramienta**: el porcentaje mínimo es una decisión financiera derivada de cuándo nacen los impuestos.

==Error típico==: calcular el pago inicial como porcentaje del IVA sobre el precio total (21%) en lugar del IVA **neto** (DF - CF).

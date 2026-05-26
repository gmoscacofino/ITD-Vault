# Ganancias — Diferencias de Cambio

> Cuándo y cómo se computan las diferencias de cambio para Ganancias. Arts. 161, 162 y 164 del DR de la LIG.

---

## TL;DR

- **Toda operación en moneda extranjera** se asienta al tipo de cambio del día de la operación (entrada/salida del bien) — **Art. 161 DR**.
- Las diferencias de cambio sobre **operaciones gravadas** se computan en el balance impositivo anual — **Art. 162 DR**.
- ==Las diferencias por **ingreso o disposición de divisas** son siempre de **fuente argentina**==.
- ==**Art. 164 DR**: NO se admite diferencia de cambio que provenga de **transformar una deuda a otra moneda** distinta de la original, **salvo al pago o novación**==.

---

## Material de origen

- **Material de Lectura #4** — Diferencias de Cambio
- **Notas de clase**: 2026-04-24
- **Art. 161, 162, 164 del DR de LIG**

---

## Cuándo aparecen diferencias de cambio

### En operaciones de comercio

Cuando una operación se pacta en moneda extranjera (típicamente USD) y se ejecuta o paga después, entre los dos momentos hay un tipo de cambio distinto → ==**diferencia de cambio**==.

### Casos típicos

- Importación de bienes: facturás en USD hoy, pagás dentro de 90 días con TC distinto.
- Préstamo en USD: el capital sube en pesos a medida que se devalúa.
- Cuentas por cobrar en USD: el cliente paga en USD a TC más alto que cuando se devengó la venta.
- Pasivos comerciales con proveedores del exterior.

---

## Art. 161 DR — Asiento contable de operaciones en moneda extranjera

==Toda operación pagadera en moneda extranjera se asienta:==

| Tipo de operación | Tipo de cambio aplicable |
|---|---|
| **Al contado** | TC efectivamente pagado |
| **A crédito — compra** | TC del **día de entrada** de los bienes |
| **A crédito — venta** | TC del **día de salida** de los bienes |

> El asiento original fija el valor en pesos. A partir de ahí, cualquier movimiento del TC genera diferencia de cambio que se reconoce al pagar/cobrar/cerrar el ejercicio.

---

## Art. 162 DR — Fuente argentina

==Las diferencias de cambio que se produzcan por el **ingreso de divisas al país** o por la **disposición de las mismas** en cualquier forma, provenientes de operaciones gravadas y cancelaciones de los créditos que las financiaron, **serán consideradas en todos los casos de fuente argentina**==.

### Implicancia

Esto es importante: una diferencia de cambio asociada a comercio internacional desde Argentina **no es de fuente extranjera** (lo que podría implicar tax credit o no gravamen). Es **fuente argentina** y se incluye normalmente en el balance impositivo.

---

## Art. 164 DR — La restricción clave

==**EN NINGÚN CASO SE ADMITIRÁ** en el balance impositivo, la incidencia de **diferencias de cambio que se produzcan como consecuencia de la transformación de la deuda a otra moneda que la originalmente estipulada**, salvo que se produzca **al efectuarse el pago o novación**.==

### Qué prohíbe

Si una deuda nace en pesos y unilateralmente se "transforma" a USD (sin pago real ni novación formal), ==la diferencia de cambio resultante **NO es deducible**==.

### Por qué existe

Evitar que las empresas inventen una transformación de moneda para generar diferencia de cambio deducible artificial.

### Cuándo SÍ se admite

Solo si:
1. **Hay pago efectivo** en la nueva moneda, o
2. **Hay novación formal** del contrato (las partes documentan el cambio de moneda como nueva obligación).

---

## Ejemplo aplicado — caso típico de cepo cambiario

**Situación**: filial argentina aprueba dividendos para accionistas del exterior por **$100.000.000 (pesos)**.

**Problema**: la empresa va al BCRA a comprar USD para girar el dividendo, pero el BCRA no le permite acceder al MULC (cepo cambiario). El dividendo queda como pasivo "a pagar" en pesos.

**Movimiento del accionista del exterior**:
> "Si la deuda se mantiene en pesos, voy a perder por la inflación. Transformemos la deuda a USD."

```
T0: Deuda en pesos: $100.000.000 (al TC inicial de $100 → equivale a USD 1.000.000)

T1 (un año después): TC oficial $180.
  Si la deuda quedó en pesos:    sigue siendo $100.000.000 (en pesos)
  Si la deuda se transformó a USD: USD 1.000.000 × $180 = $180.000.000 (en pesos)

Pérdida por diferencia de cambio: $80.000.000.
```

**Tratamiento fiscal**:

==Por el **Art. 164 DR**, esa pérdida de $80M **NO es deducible** en Ganancias==, salvo que:
- Se pague efectivamente la deuda (al pagar, la diferencia de cambio se materializa y sí se admite), o
- Haya novación formal (cambio del contrato original que genere nueva obligación en USD).

> La transformación unilateral, "implícita" o "por costumbre" no alcanza. AFIP impugna la deducción.

---

## Diferencias de cambio en distintos contextos

### Caso 1: importación de bienes en USD (operación normal)

```
01/01: Importo bienes por USD 100K. TC = $100 → asiento $10.000.000.
01/06: Pago la importación. TC = $130 → desembolso $13.000.000.

Diferencia de cambio (pérdida): $3.000.000.
Tratamiento: ==deducible== (es operación normal, no transformación artificial).
```

### Caso 2: préstamo de la matriz en USD (operación normal)

```
01/01: Recibo préstamo USD 1M. TC = $100 → asiento pasivo $100M.
31/12: Cierre del ejercicio. TC = $150 → pasivo actualizado $150M.

Diferencia de cambio (pérdida): $50M.
Tratamiento: ==deducible== al devengar (la deuda nació en USD; sigue en USD).
```

### Caso 3: dividendo en pesos transformado a USD (Art. 164)

```
01/01: Dividendo aprobado $100M (en pesos).
        Accionista pide transformación a USD: USD 1M.
31/12: TC = $180 → "deuda nueva en USD" valuada en $180M.

Diferencia de cambio (pérdida): $80M.
Tratamiento: ==NO deducible== (Art. 164 DR). Salvo pago efectivo o novación.
```

---

## Diferencias de cambio en operaciones con vinculadas

### Capital del préstamo

==**No genera renta de fuente argentina** para el acreedor del exterior==.
- No aplica Art. 24 (que rige operaciones con vinculadas del exterior con renta de fuente argentina).
- → Se deduce **al devengar** (normal).

### Intereses del préstamo

==**Generan renta de fuente argentina** para el acreedor del exterior==.
- Aplica Art. 24 último párrafo.
- → Se deduce **al pagar** (salvo que se pague antes del vto de la DDJJ del ejercicio de devengo, en cuyo caso se deduce en ese ejercicio).

> Ver [[Ganancias - Concepto y Optimizacion]] y [[Ganancias - Criterios de Imputacion]] para detalle del Art. 24.

---

## Implicancias prácticas

### Para empresas con deuda con el exterior

- Monitorear la composición del pasivo y la moneda original.
- Documentar cualquier novación con contrato escrito.
- En caso de cepo cambiario, no asumir que la transformación implícita genera deducciones.

### Para multinacionales con financiamiento intragrupo

- Préstamos en moneda dura (USD, EUR) generan diferencias de cambio deducibles si el peso se devalúa.
- ==Este es uno de los motivos por los que el préstamo de la matriz suele ser preferible al aporte de capital== en jurisdicciones con alta devaluación (ver [[Ganancias - Concepto y Optimizacion]]).

### Para operaciones de comercio exterior

- Importadores: la diferencia de cambio entre factura y pago es gasto deducible.
- Exportadores: la diferencia de cambio entre factura y cobro es ingreso gravado (si es ganancia) o gasto deducible (si es pérdida).

---

## Errores comunes

### Error 1 — Asumir que toda diferencia de cambio es deducible
NO. Si la deuda fue transformada de una moneda a otra sin pago/novación, la diferencia NO se admite (Art. 164).

### Error 2 — Olvidar Art. 24 en operaciones con vinculadas
La diferencia de cambio sobre **intereses** con vinculadas del exterior **se deduce al pago**, no al devengo.

### Error 3 — Confundir fuente de la diferencia de cambio
Las diferencias de cambio asociadas a operaciones comerciales argentinas son **fuente argentina** (Art. 162), aunque la contraparte sea del exterior.

### Error 4 — No documentar la novación
Si se cambia la moneda de un pasivo, hay que documentarlo formalmente como novación. Sin documentación, AFIP puede aplicar Art. 164 y rechazar la deducción.

### Error 5 — Aplicar Art. 164 a operaciones normales
El Art. 164 aplica solo a "transformaciones de la deuda a otra moneda". Una operación nacida en USD que evoluciona normalmente NO entra en esta restricción.

---

## Conceptos relacionados

- [[Ganancias - Concepto y Optimizacion]] — préstamo vs capital, diferencia de cambio como ventaja
- [[Ganancias - Criterios de Imputacion]] — Art. 24 (vinculadas del exterior)
- [[Ganancias - Endeudamiento con el Exterior]] — diferencia de cambio como causa de PN negativo
- [[IVA - Diferencias de Cambio]] — paralelo en IVA (tratamiento distinto)
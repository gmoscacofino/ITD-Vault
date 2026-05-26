# IVA — Diferencias de Cambio

> Cuando facturás en una moneda y cobrás en otra, hay diferencias de cambio. ¿Está gravado el IVA sobre la diferencia? Sí, según AFIP.

---

## TL;DR

Si facturás en una moneda (ej. USD) y cobrás en otra (ej. ARS), la **diferencia de cambio entre factura y cobro está gravada con IVA** según interpretación de AFIP.

- AFIP: hay que calcular IVA sobre la diferencia de cambio (porque "extiende" la base imponible).
- Resultado real: el fisco se queda con más IVA del que correspondería matemáticamente al valor original.

---

## Material de origen

- **Material de Lectura #4** — Diferencias de Cambio
- **Notas de clase**: 2026-04-17

---

## El problema

### Caso típico

Una empresa argentina factura un servicio a un cliente en **USD**, pero cobra en **ARS**:

```
Marzo - emisión de factura:
  Venta: USD 100 a TC $1.400
  Neto gravado: $140.000
  + IVA 21%: $29.400
  Total facturado: $169.400
  
  La empresa reconoce el IVA del mes 3.
  Le ingresa al fisco $29.400 al hacer la DDJJ.

Abril - cobro de la factura:
  TC ahora: $1.450
  Cliente paga USD 100 × $1.450 = $145.000 (neto)
  
  Diferencia de cambio: $145.000 - $140.000 = $5.000 a favor de la empresa
  El cliente paga el IVA ajustado al nuevo TC: $30.450
```

> En esta situación, la empresa cobra al cliente IVA correspondiente al nuevo TC ($30.450), pero ya había ingresado al fisco IVA al TC anterior ($29.400). Hay una **diferencia de cambio**.

---

## La interpretación AFIP

### Posición fiscal
AFIP interpreta que **la diferencia de cambio integra la base imponible** y por lo tanto se debe ingresar IVA sobre esa diferencia adicional.

### Cálculo

```
Diferencia de cambio (sobre neto): $145.000 - $140.000 = $5.000
IVA adicional sobre la diferencia: $5.000 × 21% = $1.050

(Pero AFIP lo calcula de otra forma, similar.)

Total ingresado al fisco:
  Marzo: $29.400 (IVA original)
  Ajuste: $1.050 (IVA sobre diferencia)
  Total: $30.450 ≈ lo que cobró efectivamente al cliente
```

### Aparente coherencia

A primera vista parece coherente: cobré IVA al TC actual ($30.450), ingreso al fisco ese monto. Pero...

---

## El problema real

### El cálculo "extiende" la base imponible

AFIP calcula el IVA sobre la **diferencia de cambio total** (no solo sobre el neto sin IVA), lo que técnicamente excede el valor original de la venta en pesos.

> Detalle técnico: cuando AFIP calcula el IVA sobre la diferencia de cambio, está aplicando el 21% sobre $5.000 (la diferencia en pesos sobre el neto). Sin embargo, si lo mirás desde la perspectiva del valor económico en USD, el IVA total ingresado puede superar a 21% del precio en USD.

### Resultado real (numérico)

Si seguís el cálculo paso a paso:

```
La empresa cobra al cliente: $175.450 ($145K neto + $30.450 IVA)
Le ingresa al fisco: $29.400 + $1.270,5 = $30.670,5

Después de pagar al fisco, le quedan:
  $175.450 - $30.670,5 = $144.779,5

Debería quedarse con USD 100 = $145.000
Faltan $220,5 (es decir, perdió $220,5)
```

### Conclusión del profesor

==El régimen de IVA sobre diferencias de cambio **le quita plata al empresario**==. Es matemáticamente desfavorable para el contribuyente.

---

## Cuándo NO hay diferencia de cambio

### Si facturás y cobrás en la misma moneda

```
Facturás en USD y cobrás en USD → no hay diferencia de cambio.
Facturás en ARS y cobrás en ARS → no hay diferencia de cambio.
```

### Cuándo SÍ hay

==Facturás en una moneda y cobrás en otra==.

Ejemplo típico:
- Empresa argentina exporta y factura en USD.
- Cobra del cliente extranjero en USD.
- Convierte a ARS al ingresar dólares (operación cambiaria).
- → Aquí puede haber diferencias asociadas a la conversión cambiaria, no a una verdadera "diferencia entre moneda factura y moneda cobro".

> El caso clásico es operación local con facturación dolarizada y cobro en pesos.

---

## Por qué la AFIP lo grava

### Lógica fiscal
Si el IVA es 21% sobre el precio de venta, y el precio "real" en pesos al momento del cobro es mayor al del momento de facturación, AFIP busca capturar IVA sobre **toda la base que efectivamente se materializó**.

### Crítica
La crítica del profesor: la diferencia de cambio es una **ganancia financiera** del vendedor (no parte del precio de venta original). Gravar IVA sobre eso es extender la base imponible más allá de lo razonable.

> "Lo único que demuestra es que le meten la mano en el bolsillo al empresario."

---

## Implicancias para decisiones empresariales

### Para empresas con clientes que pagan en otra moneda

- **Ojo con las facturaciones dolarizadas**: el "negocio" en USD puede tener un costo fiscal en IVA por diferencia de cambio.
- Si es posible, facturar y cobrar en la misma moneda.
- Si no, considerar el costo del IVA sobre diferencia de cambio al pricing.

### Para empresas exportadoras

Si exportás (cliente paga en USD), tu factura es exportación a tasa 0. Generalmente NO hay problema de diferencia de cambio para IVA (porque no había DF original).

### Para empresas con clientes locales en USD

Es el caso clásico de servicios profesionales B2B con clientes que prefieren cotizar en USD pero pagar en ARS:
- La diferencia de cambio puede ser significativa con la inflación argentina.
- Cada mes podés tener IVA adicional por la diferencia.

---

## Errores comunes

### Error 1 — Asumir que el IVA "original" es suficiente
NO. Si hay diferencia entre la moneda de facturación y la moneda de cobro, hay que reconocer IVA adicional sobre la diferencia.

### Error 2 — Calcular sobre el bruto (total con IVA)
La diferencia de cambio se calcula sobre el **neto** (precio sin IVA), no sobre el total facturado.

### Error 3 — Olvidar registrarlo en la DDJJ
Si no registrás el IVA por diferencia de cambio en la DDJJ del mes correspondiente, AFIP puede impugnar.

### Error 4 — Aplicar a operaciones en una sola moneda
Si facturás en USD y cobrás en USD, no hay diferencia de cambio. No apliques este tratamiento.

### Error 5 — Confundir con ajustes contables
Las diferencias de cambio para Ganancias son distintas (siguen normas contables y tributarias propias). Para IVA solo importa la diferencia entre moneda factura y moneda cobro.

---

## Conceptos relacionados

- [[IVA - Concepto y Logica]] — mecánica general
- [[IVA - Nacimiento del Hecho Imponible]] — cuándo se devenga
- [[Ganancias - Concepto y Optimizacion]] — las diferencias de cambio sí son negocio real para Ganancias
# IIBB — Concepto y Características

> Impuesto provincial al consumo. El más nocivo del sistema argentino. En cascada, siempre es costo.

---

## TL;DR

- **Impuesto provincial** sobre el ejercicio habitual de actividades a título oneroso.
- Grava el **precio de venta** (no la ganancia).
- Tasa: típicamente **3,5% a 5%** según actividad y provincia.
- ==**Siempre es costo**==. No es como el IVA neutro: el IIBB se carga al cliente y se suma al precio.
- Efecto **piramidación** o **en cascada**: cada etapa suma su IIBB sobre el precio que ya incluye IIBB anterior.
- Acumulado al final del proceso ≈ **6,66% del precio final**.

---

## Material de origen

- **Material de Lectura #5** — Impuesto sobre los Ingresos Brutos
- **Notas de clase**: 2026-05-08
- **Notas de Lauti (txt)**: sección extensa sobre IIBB

---

## Naturaleza del impuesto

### Impuesto provincial
Cada provincia (y CABA) tiene su propio régimen de IIBB. Las reglas básicas son similares, pero hay diferencias en tasas, exenciones y procedimientos.

### Por qué es provincial
Por la **Constitución Nacional** (Art. 121), las provincias retienen todos los poderes no delegados a la Nación. Los impuestos directos son provinciales, pero IIBB (a pesar de gravar el consumo, que es similar al IVA) **se sostiene como provincial**.

### Por qué se mantiene
Es la principal fuente de recursos propios de las provincias. Sin IIBB, dependerían 100% de la coparticipación federal. Por eso ninguna provincia quiere eliminarlo, aunque sea técnicamente "malo".

---

## El IVA es neutro, el IIBB es costo

### Comparación

| Aspecto | IVA | IIBB |
|---|---|---|
| Tipo | Indirecto, sobre valor agregado | Sobre ingresos brutos |
| Mecánica | DF - CF | Solo DF (alícuota × ventas) |
| Para el RI con cadena gravada | Neutro económicamente | **Siempre costo** |
| Acumulación en cadena | Solo el valor agregado | Se acumula (cascada) |
| Efecto sobre precios | El precio final = neto + IVA único | El precio final incluye varios "estratos" de IIBB |

### Por qué IIBB es costo
- El vendedor calcula IIBB sobre el precio de venta.
- No puede "computar" el IIBB pagado en sus compras (no hay equivalente al CF).
- ==El IIBB se suma al costo y se traslada al precio==.

---

## El efecto piramidación (en cascada)

### Qué es
Cuando un mismo bien pasa por varias etapas de comercialización, ==en cada etapa se calcula IIBB sobre el precio total== (que ya incluye el IIBB de etapas anteriores).

### Ejemplo: cadena de 3 etapas

```
Productor → Mayorista → Minorista → Consumidor final

Etapa 1: Productor vende a 100. IIBB 5% = 5. Precio facturado: 105.
Etapa 2: Mayorista vende a 105 + margen 30% = 136,5. IIBB 5% = 6,82. Precio: 143,32.
Etapa 3: Minorista vende a 143,32 + margen 30% = 186,32. IIBB 5% = 9,32. Precio: 195,63.

IIBB acumulado: 5 + 6,82 + 9,32 = 21,14
Precio final: 195,63

IIBB como % del precio: 21,14 / 195,63 = 10,8% del precio final
```

### El número típico

> En la práctica, con cadenas típicas de 3-5 etapas, ==el IIBB acumulado representa aproximadamente **6,66% del precio final**== (según el profesor).

Esto es mucho mayor que la alícuota nominal (3,5%-5%) porque la piramidación amplifica el efecto.

### Solución parcial: integración vertical
La piramidación se mitiga si todas las etapas son de la **misma empresa** (integración vertical). Ej: una empresa que produce, distribuye y vende, paga IIBB solo en la venta al consumidor final.

> Por eso muchas empresas argentinas tienden a integrarse verticalmente: una forma de minimizar IIBB. Es ineficiencia económica generada por el impuesto.

---

## Otras características nocivas

### Se paga aún con pérdida

==El IIBB se paga sobre **ingresos**, no sobre ganancias==. Aunque la empresa esté perdiendo plata, paga IIBB sobre lo que vende.

> Algunos lo llaman "**impuesto a la venta**" para destacar que no le importa si gano o pierdo.

### Es título oneroso, no lucrativo

La ley dice "**a título oneroso**" (NO lucrativo). Esto significa:
- No hace falta que la actividad sea lucrativa.
- Basta que sea retribuida (con cobro).
- Una fundación que cobra entradas (a título oneroso) paga IIBB, aunque no tenga fines de lucro.

---

## Por qué AMAZON no desembarcó en Argentina

### El caso paradigmático

==Mercado Libre tiene un modelo de **plataforma de terceros**== (los vendedores son terceros). MELI no compra ni vende, solo facilita.

==Amazon tiene un modelo de **compra y venta**== (compra a fabricantes, almacena, vende).

### Por qué Amazon no entra en AR
- Si Amazon comprara productos en AR para vender a consumidores AR, **pagaría IIBB en ambas operaciones**:
  - IIBB al fabricante (cuando le venden a Amazon).
  - IIBB de Amazon (cuando vende al consumidor).
- Con márgenes de eCommerce típicamente bajos (5-15%), ==pagar 5% + 5% = 10% sobre el precio de venta hace inviable el negocio==.

> El IIBB es la **razón principal** por la cual Amazon no entró en Argentina y MELI ganó el mercado con su modelo de plataforma.

---

## Comparación con Sales Tax (USA)

### Similitudes
- Ambos gravan el consumo.
- Ambos son a nivel sub-nacional (estatal en USA, provincial en AR).

### Diferencias clave

| Aspecto | Sales Tax (USA) | IIBB (AR) |
|---|---|---|
| Cuándo se cobra | **Solo al consumidor final** (1 sola vez) | **En cada etapa** (cascada) |
| Efecto sobre la cadena | Sin piramidación | Piramidación |
| Tasa típica | 5-10% según estado | 3,5%-5% por etapa |
| Costo final acumulado | ~7% | ~6,66% (depende de cadena) |

> Sales Tax es mucho más eficiente económicamente. IIBB es el peor diseño posible para un impuesto al consumo.

---

## Hecho imponible (4 elementos en IIBB)

| Elemento | Características en IIBB |
|---|---|
| **Objeto** | Ejercicio habitual de actividades, actos u operaciones a título oneroso |
| **Sujeto** | Cualquier sujeto que ejerza la actividad |
| **Espacio** | Provincial (lo ocurrido dentro de la provincia o CABA) |
| **Tiempo** | Devengado sobre ingresos brutos. Anual, pagado mensualmente |

> Ver [[IIBB - Hecho Imponible]] para detalle.

---

## Implicancias para decisiones empresariales

### Para empresas
- IIBB es **costo directo de ventas**: cada peso vendido paga IIBB.
- Hay que incluirlo siempre al armar precios y márgenes.
- Las cadenas integradas verticalmente sufren menos piramidación.

### Para el e-commerce
- Es el principal obstáculo de modelos donde alguien compra para revender.
- Las plataformas (marketplaces) tienen ventaja: solo pagan IIBB sobre su comisión, no sobre el precio total.

### Para decisiones de localización
- Las tasas varían entre provincias. Empresas grandes pueden elegir radicarse en provincia con tasa menor para ciertas actividades.
- El **Convenio Multilateral** distribuye el IIBB entre provincias cuando se opera en varias.

> Ver [[IIBB - Convenio Multilateral]] para detalle.

---

## Errores comunes

### Error 1 — Comparar IIBB con IVA
Son fundamentalmente distintos. IVA es neutro (con cadena gravada). IIBB es siempre costo.

### Error 2 — Olvidar la piramidación
Al estimar el costo total de IIBB, sumar todas las etapas de la cadena (no solo la última).

### Error 3 — Confundir habitualidad
La actividad **dentro del objeto social de una sociedad** es siempre habitual. Una sociedad no tiene "actividades accidentales" si están en su objeto.

### Error 4 — Asumir que la pérdida elimina IIBB
NO. IIBB se paga aunque la empresa esté perdiendo. Es sobre ventas, no sobre resultado.

### Error 5 — Aplicar tasa única
Las tasas varían según provincia y actividad. Hay que chequear la específica.

---

## Conceptos relacionados

- [[IIBB - Hecho Imponible]] — los 4 elementos en detalle
- [[IIBB - Base Imponible]] — qué integra y qué no
- [[IIBB - Exenciones y No Alcanzados]] — qué queda fuera
- [[IIBB - Convenio Multilateral]] — distribución entre provincias
- [[Sistema Tributario Argentino]] — contexto general
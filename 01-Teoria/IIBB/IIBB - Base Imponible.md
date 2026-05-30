# IIBB — Base Imponible

> Sobre qué se calcula el IIBB. Conceptos que NO integran la base imponible.

---

## TL;DR

- **Base imponible** = ingresos brutos devengados.
- **NO integran la base**:
  - Importes correspondientes a IVA y impuestos internos
  - Reintegros de capital (depósitos, préstamos)
  - Reintegros de gastos
  - Subsidios y subvenciones
  - Reintegros a exportadores
  - Ingresos por venta de **bienes de uso**

> ==Detalle clave==: IIBB se calcula **una vez sacado el IVA** de la venta (sobre el neto, no el bruto).

---

## Material de origen

- **Material de Lectura #5** — Base Imponible IIBB
- **Notas de clase**: 2026-05-08

---

## Concepto general

### Ingresos brutos devengados

Son **todos los ingresos** que la empresa genera, devengados en el período.

> Es **brutos** porque NO se descuentan costos ni gastos (a diferencia de Ganancias).

### Cálculo simplificado

```
Ingresos brutos del período (devengados)
- Conceptos que no integran la base
= Base imponible
× Alícuota (3,5%-5% según actividad)
= IIBB a ingresar
```

---

## Conceptos que NO integran la base imponible

### 1. Importes correspondientes a IVA y impuestos internos

==El IIBB se calcula sobre el **neto** de la venta, NO sobre el precio con IVA==.

```
Precio de venta total: $1.210
Neto: $1.000
IVA (21%): $210

IIBB se calcula sobre $1.000 (neto), no sobre $1.210.
```

> Esto es importante porque a primera vista uno podría pensar que IIBB grava todo el precio. Pero NO: se calcula sobre el neto, sin IVA.

### 2. Reintegros de capital

Cuando una empresa cobra **el reintegro de un préstamo o un depósito**, ese reintegro NO es ingreso (es recuperación de algo que era propio).

**Ejemplos**:
- Banco que cobra el capital de un préstamo otorgado → no es base.
- Empresa que cobra un depósito que había hecho → no es base.
- Adelanto que se recupera → no es base.

> Solo el **interés** (o el componente de servicio) es base imponible. El reintegro de capital no.

### 3. Reintegros de gastos

Cuando a una empresa le **reintegran gastos** que adelantó por cuenta del cliente, ese reintegro NO es ingreso propio.

**Ejemplo típico**: una consultora paga viáticos de sus empleados visitando a un cliente. El cliente le reintegra esos viáticos. NO es base imponible (no es ingreso propio, es recuperación de un gasto).

> Requisito: que esté documentado como reintegro y no como prestación de servicio.

### 4. Subsidios y subvenciones

Los **subsidios del Estado** (subsidios al transporte, a la electricidad, etc.) **NO** integran la base imponible.

> Coincide con el tratamiento de IVA: los subsidios no llevan ni IVA ni IIBB.

### 5. Reintegros a exportadores

Cuando un exportador recibe **reintegros o reembolsos** del fisco (por sus exportaciones), NO integran la base imponible.

### 6. Venta de bienes de uso

==Los ingresos por venta de **bienes de uso** (todo aquel bien con vida útil mayor a 1 año) NO integran la base imponible==.

**Lógica**: el bien de uso no es mercadería, no es la actividad habitual de la empresa, su venta es una salida del patrimonio (no una venta operativa).

**Restricción**: solo aplica si el bien es realmente de uso, no de cambio.

#### Ejemplo de la trampa

Una empresa de venta de muebles de oficina:
- **Para ellos**, los muebles son **bienes de cambio** (mercadería).
- Su venta SÍ integra la base imponible.

Una empresa industrial que vende un escritorio usado de su oficina:
- Es **bien de uso** (lo usó para administración, no era para vender).
- Su venta NO integra la base imponible.

> La distinción depende de la afectación, no del tipo de bien.

#### Trampa adicional: cambio de categoría

==Si un bien de uso pasa a ser "otros bienes" (cambio de afectación), empieza a pagar IIBB en su venta==. Por eso, conservar un bien como "bien de uso" hasta su venta es beneficioso fiscalmente.

---

## Caso aplicado — empresa con ingresos mixtos

### Situación
Empresa de consultoría con los siguientes ingresos mensuales:

```
Honorarios por servicios prestados: $1.000.000 + IVA $210.000
Reintegro de viáticos del cliente:    $50.000
Venta de un escritorio usado:         $100.000
Cobro de un préstamo otorgado al socio: $300.000
Intereses cobrados por ese préstamo:   $30.000
Subsidio estatal recibido:             $200.000
```

### Cálculo de base imponible

| Concepto | Monto | ¿Base? | Razón |
|---|---|---|---|
| Honorarios netos | $1.000.000 | ✅ Sí | Ingreso propio gravado |
| IVA cobrado | $210.000 | ❌ No | No integra base |
| Reintegro viáticos | $50.000 | ❌ No | Reintegro de gasto |
| Venta escritorio | $100.000 | ❌ No | Bien de uso |
| Cobro préstamo (capital) | $300.000 | ❌ No | Reintegro de capital |
| Intereses cobrados | $30.000 | ✅ Sí | Ingreso real |
| Subsidio | $200.000 | ❌ No | Subsidio |

**Base imponible**: $1.030.000.

Si la tasa para esta actividad es 5%:
- IIBB: $1.030.000 × 5% = **$51.500**.

---

## Supuestos especiales de base imponible

### Venta de inmuebles en cuotas

En las operaciones de venta de inmuebles en cuotas por plazos **superiores a 12 meses**, la base imponible está constituida por la **suma total de las cuotas o pagos que vencieran en cada período** (mes a mes).

> Lógica: el ingreso se devenga según los vencimientos de cada cuota, no en el momento de la escritura.

### Intermediarios

Para comisionistas, consignatarios, mandatarios, corredores, concesionarios, agentes oficiales de venta y representantes, o cualquier otro tipo de intermediario, la base imponible es la **diferencia entre los ingresos y los importes que corresponde transferir a los comitentes** por las operaciones realizadas en el período fiscal.

- No están gravados los ingresos obtenidos por cuenta y orden de terceros.
- Si el intermediario presta servicios con **recursos propios**: la base son los ingresos totales por esos servicios (tratamiento general).
- Los **franquiciados** que trabajan con precios regulados por el franquiciante NO se tratan como intermediarios, salvo que la mercadería se haya entregado en consignación.

### Diferencias entre precios de compra y de venta

En ciertos casos específicos, la base imponible es la **diferencia entre precios de compra y de venta** (no el precio de venta total):

1. Comercialización **mayorista y minorista de tabacos, cigarros y cigarrillos**.
2. Comercialización de **productos agrícola-ganaderos** por cuenta propia por acopiadores, en la parte adquirida directamente a los propios productores.
3. Comercialización **mayorista de medicamentos** para uso humano.
4. Distribución **mayorista y/o minorista de gas licuado de petróleo** en garrafas, cilindros o similares.

> En estos sectores con márgenes muy acotados, la base sobre el precio total sería confiscatoria, por eso se permite tomar solo el margen bruto.

---

## Casos puntuales

### Honorarios de directorio

Los honorarios de directorio NO tienen la problemática de Ganancias (no requieren ser "razonables"). Para IIBB, integran la base si son cobrados a título oneroso, pero **están exentos para PH** que ejercen como directores en relación de dependencia o similar.

### Intereses por mora

Se computan como base imponible (son ingresos reales).

### Indemnizaciones

Pueden o no estar gravadas según el tipo:
- Indemnización por daños → suele no estar gravada (es restitución).
- Indemnización por lucro cesante → puede estar gravada (compensa un ingreso esperado).

---

## Implicancias para decisiones empresariales

### Para el armado de precios

Si tu cliente paga el precio + IVA, el IIBB se calcula sobre el neto. Esto significa que tu carga real de IIBB es:
- 5% sobre el neto = ~4,13% sobre el bruto con IVA.

### Para reintegros

Cuidado con la documentación:
- Si está como "reintegro" → no es base.
- Si está como "servicio" → SÍ es base.

> La forma de facturarlo cambia el tratamiento fiscal.

### Para ventas de bienes propios

Vender activos fijos NO genera IIBB, pero hay que documentarlo bien para que AFIP no lo considere mercadería.

---

## Errores comunes

### Error 1 — Calcular sobre el bruto con IVA
El cálculo es sobre el neto. Aplicar IIBB sobre el precio total (con IVA) es error que infla la base un 21%.

### Error 2 — Incluir reintegros
Reintegros documentados (viáticos, gastos, capital) NO son base. Incluirlos es pagar de más.

### Error 3 — Tratar bien de cambio como bien de uso
Un mueble que la empresa vende como mercadería NO es bien de uso para esa empresa, aunque sea mueble.

### Error 4 — Confundir intereses con capital
En préstamos, solo el interés es base. El capital es reintegro.

### Error 5 — Olvidar la exención de transporte internacional
El transporte internacional de pasajeros (aéreo y por agua) está **exento** si hay convenio de reciprocidad con el país de origen de la compañía.

---

## Conceptos relacionados

- [[IIBB - Concepto y Caracteristicas]] — naturaleza del impuesto
- [[IIBB - Hecho Imponible]] — 4 elementos
- [[IIBB - Exenciones y No Alcanzados]] — qué está fuera del objeto o exento
- [[IIBB - Convenio Multilateral]] — distribución entre provincias
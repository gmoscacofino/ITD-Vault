# IIBB — Convenio Multilateral

> Método para distribuir el IIBB entre jurisdicciones cuando una empresa opera en varias provincias. No es un impuesto: es una distribución.

---

## TL;DR

- **Aplica a** contribuyentes con actividad en 2+ jurisdicciones (CABA y provincias).
- **No es un impuesto adicional**: solo distribuye el IIBB entre las jurisdicciones involucradas.
- **2 regímenes**:
  - **Especiales**: porcentajes fijos por actividad (ej. construcción 10/90, profesiones liberales 20/80).
  - **General**: análisis de ingresos y gastos (50/50).
- **eCommerce**: la jurisdicción es la del **cliente**.

---

## Material de origen

- **Material de Lectura #5** — Convenio Multilateral
- **Notas de clase**: 2026-05-08
- **Convenio Multilateral 18/8/77** (acuerdo entre provincias)

---

## Por qué existe

### El problema

Una empresa que opera en CABA y vende a clientes en Córdoba, Mendoza y Santa Fe. Sin convenio:
- Cada provincia querría cobrar IIBB sobre las ventas a sus residentes.
- La empresa quedaría sujeta a 4+ jurisdicciones simultáneamente, con tasas distintas.
- Conflictos entre provincias y carga administrativa enorme.

### La solución
Las provincias firmaron el **Convenio Multilateral** que establece reglas para **distribuir** el IIBB entre las jurisdicciones involucradas.

### Importante
El Convenio **NO crea un impuesto nuevo**. Solo distribuye lo que cobraría una provincia (5%) entre varias provincias.

> El monto total de IIBB no cambia. Lo que cambia es a quién va.

---

## A quién aplica

==Contribuyentes con IIBB cuyas actividades se ejercen en **una, varias o todas sus etapas** en **dos o más jurisdicciones**==.

### Ejemplos

| Empresa | ¿Aplica convenio? |
|---|---|
| Local en CABA que vende solo a clientes CABA | ❌ No (1 jurisdicción) |
| Local en CABA que vende a clientes en CABA y BA | ✅ Sí (2 jurisdicciones) |
| eCommerce que vende a todo el país | ✅ Sí (muchas jurisdicciones) |
| Empresa con oficina en CABA y planta en Córdoba | ✅ Sí (2 jurisdicciones) |
| Consultoría que viaja a varias provincias por proyectos | ✅ Sí |

### Quién NO necesita Convenio

Empresa que opera **en una sola jurisdicción** (oficina, clientes, gastos, todo en una provincia). Solo declara y paga en esa jurisdicción.

---

## Los regímenes del Convenio

### Régimen General
- Se aplica por **default** cuando NO hay régimen especial.
- Distribuye según una fórmula: **50% ingresos + 50% gastos**.

### Regímenes Especiales
- Aplican a actividades específicas con porcentajes fijos.
- Eliminan la necesidad de calcular ingresos/gastos.

---

## Regímenes Especiales

### 1. Construcción

==**10% al lugar donde tiene la oficina** del contribuyente, **90% al lugar donde se realiza la obra**==.

**Lógica**: la obra (donde se ejecuta la actividad principal) recibe la mayor parte. La oficina (donde se administra) recibe poco.

**Ejemplo**:
- Constructora con oficina en CABA realiza obra en Córdoba.
- 10% del IIBB va a CABA.
- 90% va a Córdoba.

### 2. Profesiones liberales e intermediarios

==**20% al lugar donde tiene la oficina**, **80% al lugar donde presta el servicio**==.

**Lógica**: similar a construcción. El lugar de la prestación tiene la mayor parte.

**Ejemplo**:
- Estudio jurídico con oficina en CABA defiende a cliente en Mendoza (viaja).
- 20% va a CABA.
- 80% va a Mendoza.

### Otros regímenes especiales

Existen otros para:
- Transporte.
- Entidades financieras.
- Compañías de seguros.
- Profesionales individuales.
- Etc.

Cada uno con su fórmula específica. No se desarrollan en detalle en el curso.

---

## Régimen General

### Cuándo aplica
Cuando la actividad **NO entra en ningún régimen especial**. La mayoría de las actividades (comercio, industria, ciertos servicios) caen acá.

### La fórmula 50/50

==Se calculan dos coeficientes basados en datos del año anterior==:

**Coeficiente Ingresos** (peso 50%):
- ¿Qué porcentaje de los ingresos totales proviene de cada jurisdicción?
- Se asigna ingreso a la jurisdicción donde se origina.

**Coeficiente Gastos** (peso 50%):
- ¿Qué porcentaje de los gastos totales se soporta en cada jurisdicción?
- Se asigna gasto a la jurisdicción donde se incurre.

### Cómo se asignan

#### Ingresos
==Se atribuyen a la **jurisdicción de la cual provienen**==.

> En el caso de eCommerce: jurisdicción del **cliente** (donde se entrega o se utiliza el servicio).

#### Gastos
==Se atribuyen a la **jurisdicción donde son soportados**==.

> Sueldos: jurisdicción donde trabaja el empleado.
> Alquiler: jurisdicción donde está la oficina.
> Compras: jurisdicción donde está el proveedor (generalmente).

### Cálculo aplicado

```
Una empresa total facturó: $1.000.000
  - CABA: $400.000 (40%)
  - Córdoba: $400.000 (40%)
  - Mendoza: $200.000 (20%)

Gastos totales: $700.000
  - CABA: $500.000 (71%)
  - Córdoba: $200.000 (29%)
  - Mendoza: $0 (0%)

Coeficiente final para cada jurisdicción:
  CABA: (40% × 0.5) + (71% × 0.5) = 55.5%
  Córdoba: (40% × 0.5) + (29% × 0.5) = 34.5%
  Mendoza: (20% × 0.5) + (0% × 0.5) = 10%

Total: 100% ✓
```

### Aplicación al IIBB

Una vez calculado el coeficiente, se aplica al impuesto a pagar:

```
IIBB total a pagar: $50.000 (5% sobre $1M)

A CABA: $50.000 × 55.5% = $27.750
A Córdoba: $50.000 × 34.5% = $17.250
A Mendoza: $50.000 × 10% = $5.000
```

> Cada provincia cobra según su coeficiente y aplica su propia tasa.

---

## El caso del eCommerce

### Por qué es especial

Antes, la regla era que el ingreso se atribuía al "domicilio del vendedor". Pero con el eCommerce, esto generaba que CABA o BA (donde están las grandes empresas) se llevaran todo el IIBB de ventas que iban a otras provincias.

### Reforma: jurisdicción del cliente

==Para eCommerce, los ingresos se atribuyen a la jurisdicción **donde se encuentra el cliente**==.

**Caso típico**:
- Mercado Libre o tienda online de CABA vende a un cliente en Tucumán.
- El ingreso se atribuye a **Tucumán** (no a CABA).
- Tucumán cobra IIBB sobre esa venta.

### Implicancia
Las provincias del interior recuperaron base imponible que antes "se les escapaba" a Buenos Aires y CABA.

---

## La administración del Convenio

### Comisión Arbitral
- Organismo permanente conformado por representantes de las provincias.
- Resuelve conflictos sobre aplicación del convenio.
- Sus dictámenes son obligatorios.

### Comisión Plenaria
- Se reúne periódicamente para modificar el convenio.
- Decide cambios en regímenes especiales, fórmulas, etc.

---

## Implicancias para decisiones empresariales

### Para empresas en expansión
- Antes de expandirse a otra jurisdicción, planificar la inscripción en Convenio.
- Mantener registros detallados de ingresos y gastos por jurisdicción.

### Para eCommerce
- Aprovechar que se atribuye al cliente puede simplificar (no hay que probar dónde "operás").
- Pero requiere capacidad de identificar la jurisdicción del cliente.

### Para grandes empresas
- Optimizar la distribución de actividades entre jurisdicciones con tasas distintas puede generar ahorro.
- Localizar costos donde hay alícuotas más bajas para esa actividad.

---

## Errores comunes

### Error 1 — Pensar que el Convenio crea más impuesto
NO. Solo distribuye lo que se pagaría en una sola jurisdicción entre varias. El monto total no cambia.

### Error 2 — Aplicar régimen general cuando hay régimen especial
Si tu actividad cae en régimen especial (construcción, profesiones liberales), aplicar régimen general es error.

### Error 3 — No incluir todas las jurisdicciones
Si vendés en CABA y Mendoza, tenés que inscribirte en Convenio Multilateral, no pagar solo en CABA.

### Error 4 — Atribuir mal los ingresos en eCommerce
Para eCommerce, la jurisdicción es la del cliente. No del vendedor ni del depósito.

### Error 5 — Olvidar revisar coeficientes anuales
Los coeficientes se actualizan según los datos del año anterior. Hay que rehacerlos cada año.

---

## Conceptos relacionados

- [[IIBB - Concepto y Caracteristicas]] — naturaleza del impuesto
- [[IIBB - Hecho Imponible]] — los 4 elementos
- [[IIBB - Base Imponible]] — sobre qué se calcula
- [[IIBB - Exenciones y No Alcanzados]] — qué queda fuera
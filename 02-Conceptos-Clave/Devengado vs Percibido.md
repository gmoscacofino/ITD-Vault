# Devengado vs Percibido

> Concepto transversal del Impuesto a las Ganancias. Define en qué ejercicio se imputa un ingreso o gasto.

---

## TL;DR

- **Devengado** = se imputa cuando nace el derecho a cobrar (o la obligación de pagar), sin importar si hubo flujo de caja.
- **Percibido** = se imputa cuando efectivamente se cobra (en efectivo, especie o capitalización).

| Categoría | Criterio |
|---|---|
| 1ra y 3ra (empresas, actividad comercial) | **Devengado** |
| 2da y 4ta (rentas del trabajo, ahorro PH) | **Percibido** |

---

## Material de origen

- **Material de Lectura #2** — Criterios de Imputación Temporal
- **Notas de clase**: 2026-03-20, 2026-04-10
- **Jurisprudencia clave**: Fallo CSJN "Cía. Tucumana de Refrescos"
- **Resumen Claude**: 2026-03-13 sección 9

---

## Definiciones precisas

### Devengado
Un ingreso o gasto se imputa cuando **nace el derecho a cobrarlo o la obligación de pagarlo**, independientemente de si el dinero se movió o no.

> La CSJN definió "devengar" como el **fenómeno del nacimiento u origen de un derecho de contenido patrimonial**. El ingreso se imputa al ejercicio en que ocurrieron los hechos sustanciales generadores, no al momento de firma del contrato ni al de cobro.

### Percibido
Un ingreso se imputa cuando efectivamente se **incorpora al patrimonio del titular**. Se considera percibido cuando:

- Se cobra en efectivo
- Se cobra en especie (un bien en lugar de dinero)
- Se acredita en cuenta del titular
- Se capitaliza, reinvierte, acumula o se pone en reserva con autorización del beneficiario

---

## Por qué importa

Determina **en qué año fiscal** se reconoce un ingreso o gasto, lo que impacta directamente en:

- Cuándo se paga el impuesto
- Cómo se planifica el ejercicio fiscal
- Si conviene adelantar o diferir operaciones

Este criterio es uno de los principales mecanismos de **optimización legal** del impuesto: diferir el reconocimiento de ingresos al próximo ejercicio mediante el manejo del momento de pago (en categorías que usan percibido) o de la prestación efectiva (en categorías que usan devengado).

---

## Aplicación práctica — Ejemplo de cobro encadenado

Una venta que se cobra después de varios años:

```
AÑO 1: Se realiza la venta y se emite factura.
AÑO 2: El cliente entrega cheque (vencerá año 3).
AÑO 3: El cheque rebota sin fondos. Se recibe pagaré (vencerá año 4).
AÑO 4: Se cobra efectivamente el pagaré.
```

**Bajo criterio DEVENGADO**: el ingreso se reconoce en **Año 1** (cuando se concretó la venta y nació el derecho).

**Bajo criterio PERCIBIDO**: el ingreso se reconoce en **Año 4** (cuando efectivamente entró el dinero).

> Nota sobre el cheque: el cheque se considera **especie**, no efectivo. Cuando lo recibís en pago, se entiende como percibido el ingreso. Pero si el cheque rebota, vuelve a no estar percibido hasta el cobro real.

---

## Reglas de imputación por categoría

| Categoría | Tipo de renta | Criterio |
|---|---|---|
| 1ra | Suelo, alquiler, usufructo | Devengado |
| 2da | Capital, venta de acciones (PH) | Percibido |
| 3ra | **Renta de sociedades**, empresarial unipersonal | **Devengado** |
| 4ta | Trabajo personal, dependencia, jubilaciones | Percibido |

> Regla práctica para sociedades: como una sociedad **solo puede tener renta de 3ra categoría**, usa siempre devengado para todo. Esto es así por definición legal, sin excepciones por tipo de operación.

---

## Excepciones y matices importantes

### Art. 24 LIG — Gastos con vinculadas del exterior (excepción al devengado)

Cuando una empresa argentina le paga a una **compañía vinculada del exterior** (o a una entidad en jurisdicción no cooperante / de baja o nula tributación), la deducción del gasto tiene una regla especial:

| Caso | Cuándo se puede deducir |
|---|---|
| Pago **antes** del vto. de la DDJJ del ejercicio devengado | Se deduce en el año de **devengamiento** |
| Pago **después** del vto. de la DDJJ | Se deduce en el año de **pago efectivo** |

> Lógica: evitar que se fabriquen facturas con vinculadas del exterior para diferir impuestos sin haber realmente pagado.

**Ejemplo**: empresa argentina recibe en diciembre 2024 una factura de su casa matriz en España por USD 500.000. Vto. DDJJ: junio 2025.
- Si paga en mayo 2025 → deduce en **2024** (devengamiento).
- Si paga en agosto 2025 → deduce en **2025** (año de pago).

### Obligaciones condicionales

El devengado se complica cuando hay una condición:

**Condición suspensiva**: la obligación NACE cuando ocurre la condición.
> Ejemplo: "Te pago la comisión si renovás el préstamo por 180 días". Hasta que renueve, no hay devengamiento.

**Condición resolutoria**: la obligación MUERE cuando ocurre la condición.
> Ya estaba devengada, pero se extingue si pasa lo previsto.

---

## Jurisprudencia clave — Fallo Cía. Tucumana de Refrescos (CSJN)

### Contexto
Una embotelladora actuaba en una campaña publicitaria:
- El productor de jarabe le entregaba TODA la bonificación (jarabe gratis) en el Año 1.
- La embotelladora tenía que entregar las bebidas bonificadas durante 2 años (Año 1 y Año 2).

### Problema impositivo
La asimetría temporal generaba resultados artificiales:

| | Año 1 | Año 2 |
|---|---|---|
| Ingreso por jarabe bonificado | +$100 | $0 |
| Pérdida por bebidas bonificadas | -$50 | -$50 |
| **Resultado** | **+$50** | **-$50** |

La campaña debería ser **neutra** (ni gana ni pierde), pero pagaba impuesto en Año 1 y generaba quebranto en Año 2 que tal vez no pudiera usar.

### Solución
La embotelladora devengó el ingreso del jarabe en 2 años, alineándolo con la duración real de la obligación:

| | Año 1 | Año 2 |
|---|---|---|
| Ingreso por jarabe (devengado 2 años) | +$50 | +$50 |
| Pérdida por bebidas | -$50 | -$50 |
| **Resultado** | **$0** | **$0** |

### Doctrina de la CSJN
> ==Devengar = nacimiento del derecho==, no la firma del contrato. Como la campaña se ejecutaba en 2 años, el ingreso se devenga en 2 años.

El error sería identificar el devengamiento con el momento de **firma del contrato** en lugar de hacerlo con el **período de cumplimiento de la obligación**.

---

## Errores comunes

### Error 1 — Confundir devengado con "factura emitida"
La factura **no** define el devengamiento. Lo que importa es el nacimiento del **derecho** (en ingresos) o de la **obligación** (en gastos). Podés facturar antes de devengar (anticipos) o devengar antes de facturar (servicios continuos sin facturación mensual).

### Error 2 — Olvidar la excepción del Art. 24
En cualquier caso que involucre una vinculada del exterior o una jurisdicción no cooperante, **siempre** chequear si el pago se hizo antes del vto. DDJJ. Es un error clásico que se evalúa en parciales.

### Error 3 — Aplicar percibido a empresas
Las sociedades **nunca** usan percibido. Aunque te tiente decir "no cobraron, no devengaron", el criterio para sociedades es siempre devengado. La excepción es solo la del Art. 24.

### Error 4 — Mezclar devengado de Ganancias con nacimiento HI de IVA
Son criterios distintos aunque suenan parecidos. Ver [[IVA - Nacimiento del Hecho Imponible]] para la diferencia. Una venta puede estar devengada para Ganancias en Año 1 pero generar IVA en Año 2.

### Error 5 — Asumir que un cheque rebotado sigue percibido
Si recibís un cheque (especie) y rebota, el ingreso **deja** de estar percibido hasta que se cobra efectivamente. Reentra al ciclo de cobro pendiente.

---

## Ejercicio aplicado — Fintech (Material 6)

Fintech, sociedad, cierre 31/12. Aplica devengado en todo. Cuatro situaciones:

**1. Comisiones a vendedores condicionadas a renovación de préstamo (180 días más)**
Hay condición suspensiva. La comisión no devenga hasta confirmar la renovación.
→ Se reconoce en el ejercicio en que **se cumple la condición**.

**2. Intereses de préstamos del 1er semestre, deudores que NO pagaron**
La sociedad usa devengado. El interés nació por el paso del tiempo.
→ Se reconoce como ingreso en el **año de devengamiento**, aunque no se haya cobrado.

**3. Venta de acciones de sociedad extranjera, cobro en 4 cuotas anuales**
La venta ya ocurrió, el derecho a cobrar nació.
→ Todo el resultado se reconoce en el año de la **venta**, no en cada cobro.

**4. Intereses devengados a vinculada uruguaya**
Aplica Art. 24 LIG.
→ Se deduce en el año de **pago efectivo** (salvo que se pague antes del vto. DDJJ).

---

## Conceptos relacionados

- [[IVA - Nacimiento del Hecho Imponible]] — criterio análogo pero específico de IVA
- [[Teoria de la Fuente vs Balance]] — qué está gravado
- [[Hecho Imponible (4 elementos)]] — Tiempo es uno de los 4 elementos
- [[Fallo Cia Tucumana]] — desarrollo completo del fallo

---

## Citas relevantes

> Fuente: **Lectura #2 — Criterios de imputación**: "1ra y 3ra categoría → devengado; 2da y 4ta → percibido. Una sociedad solo va a tener renta de 3ra categoría, las demás son para personas humanas."

> Fuente: **Notas 20/03/2026 — Fallo Cia Tucumana**: la CSJN definió devengar como "nacimiento del derecho", no la firma del contrato.

> Fuente: **Lectura #3 — Art. 24 último párrafo**: los gastos a vinculadas del exterior solo se deducen cuando efectivamente se paguen, salvo que se paguen antes del vencimiento de la DDJJ de ese ejercicio.

# Tax Credit (Crédito de Impuesto)

> Mecanismo para evitar la doble imposición: cuando un residente pagó impuesto análogo en el exterior, puede computarlo como crédito contra el impuesto local.

---

## TL;DR

Si un **residente argentino** tributa **en el exterior** por una renta de **fuente extranjera**:
- Puede computar ese impuesto pagado como **crédito** contra el impuesto argentino.
- Reduce o elimina la doble imposición.

**Requisitos**:
1. Impuesto **análogo** a Ganancias
2. **Efectivamente pagado** en el exterior
3. Originado en **renta de fuente extranjera**

---

## Material de origen

- **Material de Lectura #2** — Fuente y Tax Credit
- **Notas de clase**: 2026-03-13, 2026-04-24
- **Art. 1 LIG** (segundo párrafo)

---

## El problema que resuelve

### Sin tax credit
Un residente argentino que presta servicios en Francia:
- Francia retiene impuesto local sobre el servicio.
- Argentina grava la renta mundial (incluye Francia).
- → Doble imposición.

```
Renta en Francia:                  $100
Retención Francia (10%):           $10
Impuesto AR (30%):                 $30
Pago total impuestos:              $40 sobre $100 = 40%
```

### Con tax credit

Argentina permite computar los $10 pagados en Francia como crédito contra el impuesto argentino.

```
Renta en Francia:                  $100
Retención Francia (10%):           $10 (es tax credit)
Impuesto AR (30%):                 $30
Crédito por impuesto extranjero:   -$10
Impuesto AR neto:                  $20
Pago total impuestos:              $30 sobre $100 = 30% (igual que si fuera 100% AR)
```

---

## Los 3 requisitos para que sea tax credit

### Requisito 1: Impuesto análogo

El impuesto pagado en el exterior debe ser **similar a Ganancias** (sobre ingresos − gastos).

| Impuesto pagado afuera | ¿Es análogo? | Razón |
|---|---|---|
| Income Tax federal USA | ✅ Sí | Es sobre ingresos - gastos |
| Withholding Tax sobre servicios (varios países) | ✅ Sí | Es retención de impuesto sobre la renta |
| IVA del exterior | ❌ No | Es impuesto al consumo, no análogo |
| Aranceles aduaneros | ❌ No | No es impuesto a la renta |
| Sales Tax (USA estatal) | ❌ No | Es impuesto al consumo |

> Si no es análogo, no es tax credit. Se considera **costo**, no crédito.

### Requisito 2: Efectivamente abonado

No basta con que el impuesto haya sido retenido o liquidado. **Debe haber sido pagado al fisco extranjero**.

> Si la retención está pendiente o se reclamó y ganó la devolución, no se puede usar como tax credit.

### Requisito 3: Proveniente de renta de fuente extranjera

Este es el requisito más sutil y donde más se equivoca la gente:

==Si la renta es de **fuente argentina**, NO es tax credit. Es **costo**==.

#### Por qué este requisito

La lógica:
- Si la renta es de **fuente extranjera**: AR tiene que renunciar a parte de su recaudación para evitar doble imposición → permite tax credit.
- Si la renta es de **fuente argentina**: el otro país está cobrando algo que en realidad le correspondía a AR → AR no tiene por qué compensar al sujeto. Que el residente reclame al otro país.

---

## Aplicación práctica — Caso Francia (Material 7 Caso 3)

**Enunciado**: empresa argentina presta servicios técnicos a cliente en Francia.

### Escenario A: servicio prestado DESDE Argentina (remoto)

- Lugar de realización del servicio: AR.
- Por Art. 5 LIG → fuente argentina.
- Francia retiene 10% por su impuesto local.
- La retención francesa: **NO es tax credit** (renta es fuente argentina).
- Es **COSTO** para la empresa argentina.

### Escenario B: servicio prestado EN Francia (presencial)

- Lugar de realización del servicio: Francia.
- Por Art. 5 LIG → fuente extranjera (no se desarrolla en territorio AR).
- Francia retiene 10% por su impuesto local.
- La retención francesa: **SÍ es tax credit**.
- Se puede computar contra el impuesto argentino sobre fuente extranjera.

> Conclusión clave del caso: **dónde se presta el servicio físicamente** define si la retención es costo o crédito. Esto cambia totalmente la rentabilidad de la operación.

---

## Cuánto se puede computar

El tax credit tiene un **límite**: el impuesto argentino correspondiente a esa renta extranjera.

### Fórmula

```
Tax credit máximo = Renta de fuente extranjera × tasa argentina
```

### Ejemplo

Renta fuente extranjera: $1.000.000
Impuesto AR sobre esa renta: $300.000 (30%)

Si Francia retuvo $400.000 (40% en Francia):
- Tax credit usable: $300.000 (el menor entre $300K y $400K).
- $100.000 se pierden (no se pueden usar).

### Por qué este límite
AR no quiere "subsidiar" jurisdicciones de tributación alta. Solo permite recuperar hasta el impuesto que correspondería en AR.

---

## Aplicación en sentido inverso (cuando AR cobra a no residente)

El concepto opera al revés cuando AR es la jurisdicción que retiene:

- Si el no residente generó **fuente argentina** → AR retiene (Art. 93) → para él esa retención puede ser tax credit en su propio país (si su jurisdicción lo permite).
- Si el no residente generó **fuente extranjera** desde la perspectiva argentina → no hay retención AR.

> Es decir: el "tax credit" es relativo a la perspectiva del residente que reclama. Lo que para AR es retención al no residente, para él puede ser tax credit en su país.

---

## Casos especiales

### Convenios para evitar Doble Imposición (CDI)

Argentina tiene CDIs con varios países (Brasil, Chile, España, Italia, Alemania, Reino Unido, entre otros).

Los CDIs pueden:
- **Reducir** las tasas de retención.
- **Otorgar exenciones** específicas para ciertas rentas.
- **Definir reglas especiales** para residencia.

### Cómo saber si hay CDI

Lista oficial AFIP. Antes de cualquier operación internacional, chequear si hay CDI con la otra jurisdicción.

---

## Implicancias para decisiones de negocio

### Modo de prestación de servicios

Para empresas que prestan servicios al exterior, definir si se prestan **desde AR (remoto)** o **en el país del cliente** cambia totalmente el tratamiento:
- Remoto = fuente AR = retención extranjera es costo.
- En el lugar = fuente extranjera = retención extranjera es tax credit.

Esto puede llevar a estructurar operaciones de manera específica (ej. enviar empleados a trabajar afuera vs trabajar remoto desde AR).

### Localización de inversiones

Si invertís en el exterior, fijate la tasa local + si hay CDI con AR. Lo ideal es:
- Baja tasa local (para minimizar lo que pagás afuera).
- CDI con AR (para poder usar tax credit y reducir tasas).

### Estructuras de holding

Algunas estructuras (ej. holding en Uruguay para inversiones en latinoamérica) buscan optimizar la cadena de tax credits y retenciones.

---

## Errores comunes

### Error 1 — Asumir que cualquier impuesto pagado afuera es tax credit
NO. Tiene que ser análogo a Ganancias. IVA del exterior, sales tax, aranceles → NO son tax credit.

### Error 2 — Olvidar que la fuente debe ser extranjera
Si la renta es de fuente argentina, la retención extranjera es **costo**, no crédito. Es el error más típico en parciales.

### Error 3 — No conocer el límite
El tax credit tiene tope: el impuesto AR correspondiente. No se puede recuperar más de lo que pagás en AR por esa renta.

### Error 4 — Olvidar los CDIs
Si hay CDI, puede haber tasas reducidas o exenciones. No usar el CDI es perder plata.

### Error 5 — Computar tax credit antes de pagarlo
Solo se puede computar lo **efectivamente pagado**. Hasta que no haya ingreso al fisco extranjero, no es tax credit.

---

## Conceptos relacionados

- [[Renta Mundial vs Territorialidad]] — el concepto en el que se inserta
- [[Ganancias - Fuente]] — definir fuente AR vs extranjera
- [[Ganancias - Beneficiarios del Exterior]] — la otra cara (cuando AR retiene)
- [[Ganancias - Fuentes Especificas]] — Art. 5 y siguientes
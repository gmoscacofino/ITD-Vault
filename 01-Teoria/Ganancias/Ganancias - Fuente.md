# Ganancias — Fuente (Espacio)

> El elemento Espacio del Impuesto a las Ganancias. Define qué rentas grava Argentina y cuáles no.

---

## TL;DR

- Argentina aplica el principio de **Renta Mundial** (Art. 1 LIG).
- **Residentes argentinos** tributan por la **totalidad** de sus rentas (AR + exterior).
- **No residentes** tributan **EXCLUSIVAMENTE** sobre rentas de **fuente argentina**, via retención de pago único y definitivo.
- La definición general de fuente argentina está en el **Art. 5 LIG**.

---

## Material de origen

- **Material de Lectura #2** — Fuente del Ingreso
- **Notas de clase**: 2026-03-13, 2026-03-20
- **Resumen Claude**: 2026-03-13 sección 5

---

## Por qué importa

La fuente define **qué grava cada país**. Para una empresa que opera internacionalmente, identificar la fuente es lo primero porque determina:

- Si Argentina puede gravar la operación o no.
- Si una retención del exterior es **tax credit** (recuperable) o **costo** (perdido).
- Si la empresa argentina debe actuar como **agente de retención** ante un proveedor extranjero.

---

## Criterios de vinculación: los 2 grandes modelos

| Criterio | Lógica | Qué grava |
|---|---|---|
| **Territorialidad** | Solo importa el lugar donde ocurre el negocio | Negocios dentro del territorio, sin importar quién los hace |
| **Renta Mundial** | El residente tributa por todo, esté donde esté | Negocios en territorio + negocios de residentes en el exterior |

### Argentina = Renta Mundial

Argentina adoptó el principio de **Renta Mundial** (Art. 1 LIG). Esto significa que sus residentes tributan por todo lo que ganen, en cualquier parte del mundo, mientras que los no residentes solo tributan por lo que ganen en Argentina.

---

## ¿Quién es residente fiscal argentino?

La residencia fiscal NO es lo mismo que la nacionalidad. Se determina por:

- **Lugar donde vive** (centro de vida).
- **Dónde está la familia** (primer grado de parentesco).
- **Días que pasa en cada país** (típicamente +183 días en el año).

En caso de doble nacionalidad y residencia ambigua, los criterios se aplican en orden para desempatar. Puede haber casos de **doble residencia fiscal** que se resuelven por tratado bilateral (CDI = Convenio para evitar la Doble Imposición).

> **Atención**: la materia marca el concepto de "residentes fiscales argentinos" con una cruz roja, señalando que las nociones clásicas de residencia se vuelven complejas en economía digital.

---

## Implicancias del principio de renta mundial

### Para Residentes argentinos

Tributan por **toda su renta**, sin importar dónde se genere.

| Origen de la renta | Tratamiento |
|---|---|
| Fuente argentina | Gravada en AR como base local |
| Fuente extranjera | Gravada en AR como base extranjera |

**Tax credit**: si pagaron impuesto en el exterior por renta extranjera, pueden computar ese pago como crédito contra el impuesto argentino, **siempre que se cumplan los requisitos**:
1. El impuesto exterior debe ser **análogo** a Ganancias (de la misma naturaleza, sobre ingresos - gastos).
2. Debe estar **efectivamente abonado** (no basta con que esté retenido si después se anuló).
3. Debe **provenir de renta de fuente extranjera** (no aplica si la renta es de fuente argentina).

> Ver [[Tax Credit]] para desarrollo completo.

### Para No residentes

Tributan **EXCLUSIVAMENTE** sobre rentas de **fuente argentina**, via **retención de pago único y definitivo** efectuada por el residente argentino que los contrata.

El residente argentino que contrata al no residente actúa como **agente de retención**. La retención que practica es la única forma en que el fisco argentino le cobra al no residente.

> Ver [[Ganancias - Beneficiarios del Exterior]] para detalle de tasas y mecánica.

---

## Definición general de Fuente Argentina — Art. 5 LIG

Son ganancias de fuente argentina las que:

1. **Provienen de bienes** (materiales o inmateriales) **situados, colocados o utilizados económicamente en la República**.
2. De la **realización en territorio de cualquier acto o actividad** susceptible de producir beneficios.
3. De **hechos ocurridos dentro del límite** de la misma.

Y todo esto **sin tener en cuenta**:
- Nacionalidad
- Domicilio
- Residencia del titular o de las partes
- Lugar de celebración del contrato

### Ejemplos

**Hertz alquila autos en AR y Uruguay**
- Autos en AR → fuente argentina (bienes utilizados económicamente en AR).
- Autos en Uruguay → fuente extranjera (aunque la empresa sea argentina).

**Coldplay hace un show en Buenos Aires**
- Actividad realizada en territorio argentino.
- → Fuente argentina, aunque la banda sea británica.
- El contratante argentino debe retener el impuesto.

**Netflix factura desde el exterior a usuarios argentinos**
- Servicio digital utilizado en AR.
- → Fuente argentina (con reglas específicas para servicios digitales).
- Se cobra según la zona de residencia del cliente.

---

## Implicancias prácticas para negocios

### Vendo al exterior

- Ingreso de **fuente extranjera** (si el bien se produce y se exporta desde AR, ojo: en EXPO predomina el lugar de fabricación → fuente argentina).
- El cliente extranjero **puede retener** su impuesto local.
- Esa retención **puede ser tax credit** en AR si la renta es de fuente extranjera.

> **Ejercicio típico**: empresa argentina presta servicio a Francia. Si presta **desde AR (remoto)** → fuente argentina → la retención francesa es **costo**, no tax credit. Si presta **en Francia (presencial)** → fuente extranjera → la retención francesa **es tax credit**.

### Compro del exterior

- Si el servicio o bien genera fuente argentina (típicamente: servicios usados económicamente en AR) → la empresa argentina actúa como **agente de retención**.
- Si genera fuente extranjera → no hay retención.

---

## Discriminar fuente argentina vs extranjera

¿Importa? **SÍ**, mucho.

### Para residentes con rentas mixtas

Es importante discriminar porque:
- Las **retenciones del exterior** solo se computan como tax credit contra la **fuente extranjera**.
- Si las clasificás mal (decís que es fuente argentina cuando en realidad es extranjera, o viceversa), terminás pagando impuestos por demás o pagando lo que ya pagaste afuera.

### Para residentes que son agentes de retención

Si la fuente es argentina, tenés que retener. Si no retenés, sos solidariamente responsable. El error puede ser caro.

---

## Errores comunes

### Error 1 — Confundir lugar del contrato con fuente
El Art. 5 LIG dice expresamente que la fuente **no depende del lugar de celebración del contrato**. Lo que importa es dónde se desarrolla la actividad o dónde se utilizan los bienes.

### Error 2 — Asumir que "todo lo que cobro del exterior es fuente extranjera"
No. Si vos prestás un servicio desde Argentina a un cliente del exterior, el servicio se genera en AR. La fuente es argentina, no extranjera, aunque cobres del exterior.

### Error 3 — Olvidar que las exportaciones de bienes son fuente argentina
En **expo de bienes**, predomina el **lugar de fabricación** (Art. 9 LIG). Como AR es donde se fabrica, la renta es de fuente argentina, no extranjera.

### Error 4 — Asumir que el no residente no paga nada en AR
Falso. El no residente paga retención del Art. 93 sobre toda renta de fuente argentina. La retención es **pago único y definitivo** (no hay declaración jurada posterior).

### Error 5 — Pensar que la nacionalidad importa
La nacionalidad es irrelevante. Lo único que importa es la **residencia fiscal**, definida por centro de vida y días.

---

## Conceptos relacionados

- [[Renta Mundial vs Territorialidad]] — desarrollo completo
- [[Tax Credit]] — cómo computar retenciones del exterior
- [[Ganancias - Fuentes Especificas]] — Arts. 6-14 para casos especiales
- [[Ganancias - Beneficiarios del Exterior]] — retención a no residentes
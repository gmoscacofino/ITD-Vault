# Material #6 — Repaso I Ganancias

> Repaso integral de Ganancias: tax credit, fideicomisos, beneficiarios del exterior, Art. 24 (vinculadas), capital vs préstamo, condonación.

**Status**: ✅ Resoluciones validadas en clase / cátedra.

---

## Índice de casos

1. **[[#Caso 1 — Software Factory AR → Paraguay]]** — Tax credit cuando la fuente es argentina
2. **[[#Caso 2 — Fideicomiso de construcción al costo]]** — Quién tributa cuando hay residentes y no residentes
3. **[[#Caso 3 — CEO discográfica argentina]]** — Múltiples pagos al exterior y análisis de retención por concepto
4. **[[#Caso 4 — Filial multinacional electrodomésticos (vinculada China)]]** — Art. 24 LIG, devengo vs pago, inventario
5. **[[#Caso 5 — Capital vs préstamo (multinacional austríaca)]]** — Diferencias de cambio, condonación

---

## Caso 1 — Software Factory AR → Paraguay

### Enunciado

> Una compañía argentina de software brinda servicios de desarrollo de página web a una empresa residente en Paraguay. El servicio es prestado por un desarrollador Senior bajo el formato de Home Office (en Argentina). La empresa paraguaya aplicará una retención por impuesto a la renta de Paraguay.
>
> **¿Es correcto entender que dicha retención NO podrá ser computada como tax credit por la empresa argentina en su DDJJ de Ganancias?**

### Conceptos involucrados

- [[Tax Credit]] — requisito clave: renta de fuente extranjera
- [[Ganancias - Fuente]] — Art. 5 LIG
- [[Renta Mundial vs Territorialidad]]

### Resolución

**SÍ, es correcta esa afirmación.**

El desarrollador trabaja desde Argentina (home office en AR). El servicio se presta **desde territorio argentino** → ==fuente argentina== (Art. 5 LIG).

El tax credit solo aplica sobre rentas de **fuente extranjera** (Art. 1 LIG). Como este ingreso es de fuente argentina, la retención de Paraguay no puede computarse como pago a cuenta en la DDJJ argentina.

==La retención paraguaya es un **costo** para la empresa argentina, no un crédito.==

### Por qué este ejercicio

Es el caso emblema del requisito "fuente extranjera" del tax credit. Si el servicio se hubiera prestado **en Paraguay** (con el desarrollador viajando a Paraguay), la retención sí sería tax credit. La forma de prestación cambia totalmente el tratamiento. Ver [[Tax Credit#Caso Francia]] para el caso paralelo.

---

## Caso 2 — Fideicomiso de construcción al costo

### Enunciado

> Usted es el FIDUCIARIO en un fideicomiso de construcción al costo. Todos los FIDUCIANTES son BENEFICIARIOS: 80% residentes argentinos, 20% residentes uruguayos.
>
> **¿Qué sujeto debe ingresar el impuesto a las Ganancias?**

### Conceptos involucrados

- [[Fideicomiso]] — quién tributa según residencia del beneficiario
- [[Ganancias - Sujetos]]
- [[Renta Mundial vs Territorialidad]]

### Resolución

Hay fiduciantes = beneficiarios con **distinta residencia fiscal** → se aplican dos reglas distintas en paralelo:

| Caso | Quien tributa |
|---|---|
| Fiduciante = Beneficiario **residente** (80%) | El **FIDUCIANTE** directamente, en su DDJJ personal |
| Fiduciante = Beneficiario **no residente** (20% uruguayos) | El **FIDEICOMISO** (en cabeza del fiduciario) |

### Opción del régimen unificado

Cuando hay mezcla de residentes y no residentes, los fiduciantes-beneficiarios pueden **optar** (por un mínimo de **5 años**) por tributar todos como fideicomiso → en ese caso el sujeto sería el FIDEICOMISO en cabeza del fiduciario por la totalidad.

### Respuesta final

==Sin la opción: tributan ambos (fiduciantes residentes directamente; fideicomiso por los no residentes).==
Con opción 5 años: el fideicomiso paga por todos.

### Por qué este ejercicio

Aplica directamente la regla central de [[Fideicomiso]]: el régimen NO es uniforme, depende de quién es beneficiario y dónde reside. La opción 5 años es trampa de parcial: hay que recordar que existe y conocer el plazo.

---

## Caso 3 — CEO discográfica argentina

### Enunciado

> CEO de empresa discográfica argentina con los siguientes pagos al exterior:
> 1. USD 1.500 — libro Deluxe Rolling Stones en Amazon
> 2. USD 15.000 — pasaje + hotelería de Vicentico en México (empresa mexicana, viaje a promocionar disco)
> 3. USD 12.000 — derechos de autor de artistas extranjeros (Sociedad Española de Autores)
> 4. USD 60.000 — CDs adquiridos de Casa Matriz, importados de China
> 5. USD 7.500 — agasajo en Acapulco a Vicentico

### Conceptos involucrados

- [[Ganancias - Beneficiarios del Exterior]] — Art. 93 LIG
- [[Ganancias - Fuente]] — Art. 5 LIG
- [[Ganancias - Fuentes Especificas]] — Art. 9 (importaciones), Art. 13 (películas/derechos)

### Resolución por punto

**1. Libro Amazon — USD 1.500**
Bien importado (no servicio). Art. 9 LIG: la ganancia del exportador es de fuente extranjera. ==No hay retención.==

**2. Pasaje + hotel empresa México — USD 15.000**
Servicio prestado en el exterior (México), sin utilización económica en Argentina. No es fuente argentina (Art. 5). ==No hay retención.==

**3. Derechos de autor — USD 12.000 (Sociedad Española de Autores)**
Los derechos de autor se ==utilizan en Argentina== → fuente argentina.
Art. 93 inc. b LIG (obra inscripta): ganancia neta presumida 35% → retención efectiva = 35% × 35% = **12,25%**
→ Retención: USD 12.000 × 12,25% = **USD 1.470**. ==Sí hay retención.==

**4. CDs Casa Matriz, importados de China — USD 60.000**
Según las notas de clase: ==hay retención== porque el precio de los CDs lleva incorporado el valor de los derechos de los artistas, utilizados en Argentina → tratamiento análogo al punto 3.

> [!warning] Validar con la cátedra
> Este punto es contraintuitivo (parecería importación de bienes pura). Está marcado así en las notas de clase pero conviene confirmar el fundamento exacto.

**5. Agasajo en Acapulco — USD 7.500**
El servicio (agasajo, comida, hotel) lo presta una empresa en territorio mexicano → fuente extranjera → ==no hay retención.==

### Por qué este ejercicio

Practica la distinción operación-por-operación. Un mismo flujo de pagos al exterior tiene tratamientos completamente distintos según:
- ¿Es bien o servicio?
- ¿Dónde se presta/utiliza?
- ¿Hay derechos de autor involucrados?

Es típico de parcial: dar una lista de pagos y pedir análisis individual.

---

## Caso 4 — Filial multinacional electrodomésticos (vinculada China)

### Enunciado

> CEO de filial argentina (cierre 31/12). En 2021 se hicieron 3 compras a la vinculada de China:
> - **Compra #1**: USD 200.000 — pagada 31.05.2022 — vendida en 2021
> - **Compra #2**: USD 320.000 — pagada 31.10.2021 — existencia al cierre 2021
> - **Compra #3**: USD 75.000 — pagada 15.03.2022 — existencia al cierre 2021
>
> DDJJ 2021 vence 10.05.2022. **¿En qué período fiscal se deduce cada compra?**

### Conceptos involucrados

- [[Ganancias - Criterios de Imputacion]] — devengado vs percibido
- [[Ganancias - Concepto y Optimizacion]] — Art. 24 LIG (vinculadas del exterior)
- [[Devengado vs Percibido]]

### Regla aplicable

**Art. 24 último párrafo LIG** — gastos a vinculadas del exterior:
- Si se **paga antes del vencimiento de la DDJJ** del ejercicio en que se devengó → deduce en ese ejercicio.
- Si se **paga después del vto de la DDJJ** → deduce en el ejercicio de **pago efectivo**.

Además: como las compras son inventario, son costo solo cuando se **venden** (no cuando se compran).

### Resolución por compra

| Compra | ¿Vendida en 2021? | Pago | Relación con DDJJ 2021 (vto 10.05.2022) | Deducción |
|---|---|---|---|---|
| **#1** USD 200.000 | Sí | 31.05.2022 | **Después** del vto | ==**2022** (año de pago)== |
| **#2** USD 320.000 | No (existencia) | 31.10.2021 | — | Cuando se venda (pagada antes del año de venta) |
| **#3** USD 75.000 | No (existencia) | 15.03.2022 | **Antes** del vto | Cuando se venda |

### Análisis de la trampa

==Compra #1 se devengó como costo en 2021 (se vendió ese año) PERO al pagarse después del vto de la DDJJ, la deducción se corre a 2022.== Esto es el caso emblemático del Art. 24: rompe el principio de devengado puro.

Compras #2 y #3 no son costo en 2021 (siguen siendo inventario), entonces el Art. 24 se evalúa cuando se vendan.

### Por qué este ejercicio

Es el clásico del Art. 24. Combina:
- Devengo del costo (cuándo nace) vs imputación fiscal (cuándo se deduce).
- Vinculada del exterior (activa el Art. 24).
- Inventario vs gasto operativo.

Es ejercicio de parcial casi seguro en alguna variante.

---

## Caso 5 — Capital vs préstamo (multinacional austríaca)

### Enunciado

> CFO filial argentina de multinacional austríaca. La casa matriz enviará EUR 2.000.000. Se consulta:
> 1. ¿Forma más conveniente: aporte de capital o préstamo?
> 2. Si es préstamo: ¿tratamiento de diferencias de cambio en Ganancias?
> 3. Si la casa matriz condona el capital: ¿tratamiento en Ganancias de la filial?

### Conceptos involucrados

- [[Ganancias - Concepto y Optimizacion]] — financiamiento intra-grupo
- [[Ganancias - Criterios de Imputacion]] — Art. 24
- [[Teoria de la Fuente vs Balance]] — condonación como ingreso real

### 1. Capital vs Préstamo

| Aspecto | Aporte de capital | Préstamo |
|---|---|---|
| Recuperabilidad en moneda dura | No (queda como patrimonio) | Sí (puede exigir devolución en EUR) |
| Genera gasto deducible en GAN | No | Sí (intereses + diferencia de cambio) |
| Necesidad de devolver | No | Sí |
| Flexibilidad para la matriz | Baja | Alta |

==En Argentina conviene típicamente el **préstamo**==, porque genera **diferencia de cambio deducible** (el peso se deprecia → la deuda en EUR sube en pesos → pérdida deducible).

### 2. Diferencias de cambio del préstamo

**Sobre el CAPITAL**:
- Se deduce cuando se ==**devenga**==.
- La diferencia de cambio sobre el capital prestado NO genera renta de fuente argentina para la casa matriz (el capital no es renta).
- No aplica Art. 24 → deducción al devengar.

**Sobre los INTERESES**:
- Los intereses sí son renta de fuente argentina para la casa matriz vinculada.
- Aplica ==Art. 24 último párrafo== → se deduce cuando se ==**pague**== (salvo que se pague antes del vto de la DDJJ del ejercicio de devengo).

### 3. Condonación del capital

Si la casa matriz decide no cobrar el préstamo, la filial recibe un **ingreso por condonación de pasivos**. Es un negocio real → ==**gravado con Ganancias**==.

**Fundamento**: [[Teoria de la Fuente vs Balance]] aplicada a PJ: todo ingreso derivado de negocios reales está gravado. La condonación es un ingreso real (no contable puro), entonces paga.

### Por qué este ejercicio

Integra varios conceptos:
- Decisión de estructuración (capital vs deuda).
- Art. 24 aplicado a diferencias de cambio (capital vs intereses → tratamiento distinto).
- Teoría del balance aplicada a condonación.

Es ejercicio "trampa" porque la condonación pareciera "no ser ingreso" (no entra plata), pero económicamente sí lo es.

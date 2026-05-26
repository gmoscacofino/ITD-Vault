# Material #7 — Ejercitación Ganancias e IVA

> Casos integrados de Ganancias e IVA: gross-up para beneficiarios del exterior, reorganización libre de impuestos, fuente y tax credit, nacimiento del hecho imponible en IVA con efecto inflacionario.

**Status**: ✅ Resoluciones validadas en clase / cátedra.

---

## Índice de casos

1. **[[#Caso 1 — Empresa UK presta en Argentina (gross-up + IVA)]]**
2. **[[#Caso 2 — Reorganización libre de impuestos (Art. 77 LIG)]]**
3. **[[#Caso 3 — Big Data Argentina para gobierno francés: remoto vs presencial]]**
4. **[[#Caso 4 — Shopping center + empresa francesa de retail (IVA — nacimiento HI)]]**

---

## Caso 1 — Empresa UK presta en Argentina (gross-up + IVA)

### Enunciado

> El dueño de una empresa de tecnología residente fiscal argentina contrata una empresa residente fiscal de UK para procesar información de redes sociales. El contrato indica expresamente que el servicio **NO comprende asesoramiento**. La empresa de UK enviará 2 empleados que trabajarán **en Argentina** durante 3 meses. Presupuesto: **USD 175.000**. La empresa argentina debe hacerse cargo de los impuestos que correspondan.
>
> **¿Cuál será el costo final del servicio?**

### Conceptos involucrados

- [[Ganancias - Beneficiarios del Exterior]] — Art. 93 LIG
- [[Ganancias - Fuentes Especificas]] — inc. h) servicios técnicos sin asesoramiento
- [[Gross-up]]
- [[IVA - Importacion de Servicios]] — responsable sustituto

### Resolución — Impuesto a las Ganancias

Los empleados trabajan **físicamente en Argentina** → ==fuente argentina== (Art. 5 LIG).
La empresa de UK es no residente → tributa solo sobre fuente argentina. La empresa argentina actúa como **agente de retención** con carácter de **pago único y definitivo**.

El contrato dice que NO hay asesoramiento → **Art. 93 inc. h) LIG** (servicios técnicos sin asesoramiento):
- Ganancia neta presumida: **90%**
- Tasa efectiva: 90% × 35% = ==**31,5%**==

Como la empresa argentina asume los impuestos, hay que hacer **gross-up** para que UK reciba USD 175.000 netos:

| Concepto | Cálculo | Resultado |
|---|---|---|
| Monto bruto (gross-up) | 175.000 / (1 - 0,315) | **USD 255.474,45** |
| Retención Ganancias | 255.474,45 × 31,5% | **USD 80.474,45** |
| Neto recibido por UK | 255.474,45 - 80.474,45 | **USD 175.000** ✓ |

### Resolución — IVA

Los empleados prestan el servicio físicamente en Argentina → NO es "importación de servicios" (que requiere prestación desde el exterior). Es un **servicio prestado en el país por sujeto del exterior**.

**Art. 4 inc. h) Ley IVA**: la empresa argentina es **responsable sustituto** → debe ingresar el IVA.
El IVA ingresado se computa como **crédito fiscal** al mes siguiente → es ==económicamente neutro== (solo genera costo financiero por el adelanto de ~30 días).

| Concepto | Cálculo | Resultado |
|---|---|---|
| Base imponible | USD 255.474,45 | |
| IVA (21%) | 255.474,45 × 21% | **USD 53.649,63** |
| Efecto económico | Se recupera como CF al mes siguiente | ==**NEUTRO**== |

### Respuesta final

| Concepto | Monto |
|---|---|
| Pago neto a UK | USD 175.000 |
| Retención Ganancias (a cargo empresa AR) | USD 80.474,45 |
| ==**Costo económico real**== | ==**USD 255.474,45**== |
| IVA responsable sustituto | USD 53.649,63 → NEUTRO (se recupera como CF) |

> El costo final es **USD 255.474,45**, más un costo financiero por el adelanto del IVA que se recupera al mes siguiente.

### Por qué este ejercicio

Integra los 3 conceptos críticos para operaciones con beneficiarios del exterior:
1. Identificar la **fuente** (acá: argentina, porque trabajan en AR).
2. Aplicar la **tasa efectiva correcta** del Art. 93 (no 35% pleno, sino 31,5% por la presunción del 90%).
3. **Gross-up** correcto cuando se pacta neto (dividir por (1 - tasa), no sumar).
4. Reconocer el **responsable sustituto** del IVA cuando hay un sujeto del exterior prestando en AR.

==Error típico==: aplicar 35% en vez de 31,5%, o sumar la retención al neto en vez de hacer gross-up. Ambos infralizan/sobreestiman el costo final.

---

## Caso 2 — Reorganización libre de impuestos (Art. 77 LIG)

### Enunciado

> Emprendedor tecnológico: **60% de Sociedad X** (servicios digitales) y **60% de Sociedad Y** (sociedad inversora). El otro 40% de X lo tiene JCG; el 40% de Y, NAO. Ambas sociedades tienen **5 años de antigüedad** y siempre los mismos accionistas.
>
> 1. **¿Las sociedades X e Y pueden reorganizarse libre de impuestos?**
> 2. **En caso negativo, ¿qué modificaciones propone?**

### Conceptos involucrados

- [[Ganancias - Reorganizacion Libre de Impuestos]] — Art. 77 LIG
- [[Ganancias - Sujetos]] — sociedades del mismo grupo
- [[Sociedad de Capital vs Sociedad de Personas]]

### Resolución

**Tipos de reorganización libre de impuestos (Art. 77 LIG)**:
1. **Fusión**: una o más sociedades se disuelven y transfieren patrimonio a otra.
2. **Escisión**: una sociedad se divide.
3. **Conjunto económico**: transferencia entre empresas del mismo grupo económico.

**Vía natural**: Conjunto Económico.
**Requisito específico del DR**: el controlante debe tener al menos **80%** del capital y votos de **AMBAS** entidades, por al menos **2 años** previos.

| Requisito | Situación actual | ¿Cumple? |
|---|---|---|
| Antigüedad ≥ 2 años | 5 años | ✅ Sí |
| Control ≥ 80% en X | Emprendedor tiene 60% | ❌ ==No== |
| Control ≥ 80% en Y | Emprendedor tiene 60% | ❌ ==No== |

#### 1. ==NO puede reorganizarse libre de impuestos== en el estado actual

Con 60% < 80% no se configura el conjunto económico.

#### 2. Para que sea libre de impuestos

El emprendedor debe adquirir al menos **20% adicional** de cada sociedad y **mantener ese 80% durante 2 años** antes de ejecutar la reorganización.

| | Sociedad X | Sociedad Y |
|---|---|---|
| Situación actual | Emprendedor 60%, JCG 40% | Emprendedor 60%, NAO 40% |
| Situación requerida | Emprendedor ≥ 80% | Emprendedor ≥ 80% |
| Acción necesaria | Comprar ≥ 20% a JCG | Comprar ≥ 20% a NAO |
| Plazo de espera | Mantener ≥ 80% por **2 años** | Mantener ≥ 80% por **2 años** |

==Recién cumplidos los 2 años, la reorganización califica como libre de impuestos bajo Art. 77 LIG.==

### Por qué este ejercicio

Practica los requisitos cuantitativos del Art. 77:
- **80%** de participación: si no se cumple → NO aplica el régimen.
- **2 años** previos de control: no se puede "armar" el control el día anterior a la reorganización.

==Error típico==: pensar que con "los mismos accionistas hace 5 años" alcanza. NO. Lo que cuenta es el **porcentaje de control de un mismo dueño**, no la estabilidad del paquete accionario.

---

## Caso 3 — Big Data Argentina para gobierno francés: remoto vs presencial

### Enunciado

> Sociedad argentina de Big Data contratada por organismo gubernamental de **Francia**. Valor: **USD 1.000.000**. Trabajo de **3 meses en 10 ciudades de Francia**. Francia aplicará retención de Ganancias del **10%**. Ganancia antes de impuestos: USD 400.000 (ingresos 1.000.000 - gastos 600.000).
>
> Opción: prestar **remoto** (desde Argentina) o **enviar personal a Francia** (costo adicional USD 12.000/mes).
>
> **Asesorar sobre el lugar de prestación considerando Ganancias.**

### Conceptos involucrados

- [[Tax Credit]] — el requisito de fuente extranjera
- [[Ganancias - Fuente]]
- [[Renta Mundial vs Territorialidad]]
- [[IVA - Exportaciones]] (mención al final)

### Resolución

**Costo adicional de ir a Francia**: USD 12.000 × 3 meses = **USD 36.000**

**Diferencia clave**: la fuente determina el tratamiento de la retención francesa:

- **Remoto desde Argentina** → actividad en territorio argentino → ==fuente argentina== → retención Francia = **COSTO irrecuperable** (no deducible como tax credit).
- **Personal en Francia** → actividad en territorio francés → ==fuente extranjera== → retención Francia = **TAX CREDIT** (Art. 1 LIG, computable contra IG argentino).

### Comparación numérica

| Concepto | Argentina (remoto) | Francia (presencial) |
|---|---|---|
| Fuente del ingreso | Argentina | **Extranjera** |
| Ingresos brutos | 1.000.000 | 1.000.000 |
| Retención Francia 10% (descontada del cobro) | (100.000) | (100.000) |
| Cash recibido de Francia | 900.000 | 900.000 |
| Gastos operativos | (600.000) | (636.000) |
| Cash antes de IG | 300.000 | 264.000 |
| Base imponible IG | 400.000 | 364.000 |
| IG bruto (30%) | (120.000) | (109.200) |
| Tax credit (retención Francia) | **No aplica** | **+100.000** |
| **IG neto a pagar a AFIP** | (120.000) | (9.200) |
| ==**Resultado neto final**== | ==**USD 180.000**== | ==**USD 254.800**== |

### Respuesta final

**Recomendación: prestar servicios en Francia (presencial).**
==USD 74.800 adicionales== a pesar del costo de traslado de USD 36.000. La retención francesa de USD 100.000 pasa de ser un costo irrecuperable a un tax credit, ahorrando USD 100.000 de IG menos el costo incremental.

### Nota IVA

En ambos escenarios es exportación de servicios (cliente del exterior, utilización económica fuera de Argentina) → ==tasa 0%==. La sociedad puede recuperar el crédito fiscal vinculado (devolución, compensación o transferencia a AFIP).

### Por qué este ejercicio

Es el caso emblema del impacto económico del concepto **fuente**. La diferencia entre prestar remoto vs presencial no es de logística — es de USD 74.800 reales. Practica:

1. Aplicación de [[Tax Credit]] (requisito fuente extranjera).
2. Decisión de estructuración basada en fiscalidad (no en operativa).
3. Distinguir el costo adicional (viaje) del beneficio fiscal (tax credit).

==Error típico==: comparar solo los flujos operativos sin considerar el efecto del tax credit. Sin él, el remoto parece más conveniente (menos costo). Con él, la realidad se invierte.

---

## Caso 4 — Shopping center + empresa francesa de retail (IVA — nacimiento HI)

### Enunciado

> Sociedad argentina que construye y alquila shoppings. Tiene terrenos en CABA, Santa Fe, Mendoza y Córdoba (adquiridos en 2010). Una **empresa francesa de retail** propone:
>
> - **Alternativa 1**: Pagar anticipado **USD 1,5M + IVA** de alquiler, para que la sociedad argentina construya las tiendas en sus terrenos.
> - **Alternativa 2**: La empresa francesa **construye las tiendas** en los terrenos argentinos (USD 1,5M) y las **cede a la sociedad argentina** a cambio del valor del alquiler de los próximos 10 años.
>
> 1. ¿Cuál de las 2 opciones aceptaría?
> 2. ¿Cuáles son los temas/problemas del caso?

### Conceptos involucrados

- [[IVA - Nacimiento del Hecho Imponible]]
- [[IVA - Empresa Constructora]]
- [[IVA - Concepto y Logica]] — neutralidad y costo financiero
- Efecto de la inflación sobre el crédito fiscal en pesos

### Tema central del caso

==Nacimiento del hecho imponible en IVA y el efecto inflacionario sobre el crédito fiscal==.

### Análisis Alternativa 1

La empresa francesa paga **USD 1,5M + IVA por adelantado = USD 1,815M** (1,5 × 1,21).

La sociedad argentina:
- Recibe USD 1,815M → genera un ==**débito fiscal**== al momento del cobro/HI.
- A lo largo de 10 años emite facturas de alquiler mes a mes → paga IVA (DF) sobre cada alquiler mensual.
- El IVA de los materiales/construcción genera un **crédito fiscal en pesos** que se mantiene **fijo en términos nominales**.
- El DF de los alquileres mensuales, con el tiempo y la inflación, va **manteniéndose en valor real** (porque se ajusta por TC) pero el CF de construcción ==se devalúa==.

==Problema: el CF en pesos se devalúa. La constructora puede terminar poniendo plata de su bolsillo para pagar IVA neto a lo largo de los 10 años.==

### Análisis Alternativa 2

La empresa francesa construye (USD 1,5M) y cede las tiendas. El HI del "precio de ceder la obra" y el DF del "pago equivalente de 10 años de alquiler" ocurren en el **mismo momento** → es ==**neutro en IVA**==.

> ==La alternativa 2 es más neutra en IVA porque los débitos y créditos nacen en el mismo momento.==

### Respuesta final

**Aceptar Alternativa 2**, porque:
- No hay riesgo de descalce temporal entre CF (fijo en pesos) y DF (10 años de alquileres).
- El IVA es neutro: el CF de la cesión y el DF del equivalente de alquileres se compensan al momento.
- En inflación alta como Argentina, adelantar IVA en la alternativa 1 ==genera una pérdida real al accionista==.

### Temas/problemas del caso

- Nacimiento del hecho imponible (cuándo nace el HI en cada alternativa).
- Efecto inflacionario sobre el crédito fiscal en bienes de uso.
- Devaluación del CF en pesos en el tiempo.

### Por qué este ejercicio

Es el más conceptual del material. No se resuelve con un cálculo, se resuelve **viendo la asimetría temporal** entre el momento del DF y el del CF:
- En Alt 1: DF hoy (todo de golpe), CF distribuido en 10 años de alquileres → **descalce malo en inflación**.
- En Alt 2: DF y CF al mismo tiempo → **simetría**.

Practica el concepto de **neutralidad económica del IVA** y cómo la inflación argentina **rompe** esa neutralidad cuando hay desfasaje temporal.

==Error típico==: pensar que las dos alternativas son equivalentes porque "el monto total de IVA es el mismo". Lo que importa es **cuándo** se reconoce, no cuánto.

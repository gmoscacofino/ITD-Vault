# Material #11 — Ejercitación Ganancias, IVA, IIBB, IDyCB

> Casos integrales con los 4 impuestos. Foco: franquicia internacional y exportación de servicios.

**Status**: ✅ Caso I validado en clase. ⏳ Caso II pendiente de resolución de cátedra.

---

## Índice de casos

1. **[[#Caso I — Franquicia DETROIT en Brasil]]** — ✅ Resuelto
2. **[[#Caso II — Empresa de telefonía IP: efecto de la exención de IVA]]** — ⏳ Pendiente (solo enunciado)

---

## Caso I — Franquicia DETROIT en Brasil

### Enunciado

> CFO de **American Food SA** (residente fiscal argentina), cadena de gastronomía americana **DETROIT**. Modelo de negocios: 2 restaurants propios + 28 franquiciados en Argentina. Las franquicias incluyen: i) servicios de asesoramiento (decoración, atención al cliente, gastronomía), y ii) cesión de uso de la marca DETROIT por 5 años.
>
> Un grupo económico brasilero ofrece **USD 600.000/año por todo concepto, neto de la retención del Impuesto a la Renta de Brasil del 10%** del valor de la franquicia.
>
> Se solicita: indicar el monto de **ingresos netos anuales** que obtendrá American Food (ingresos menos el efecto de Ganancias, IVA, IIBB e IDyCB). Considerar: posibilidad de tax credit, si el negocio está gravado con IVA y con IIBB.
>
> Tasas: Ganancias 30%, IVA 21%, IIBB 5%, IDyCB 1,2% total (0,6% débito o crédito).

### Conceptos involucrados

- [[Gross-up]] — para llegar del neto cobrado al bruto declarable
- [[Tax Credit]] — retención brasilera como crédito de impuesto
- [[IVA - Exportaciones]] — exportación de servicios, tasa 0%
- [[IVA - Controversias del Objeto]] — franquicia gravada
- [[IIBB - Exenciones y No Alcanzados]] — exportación de servicios exenta
- [[IDyCB]] — sobre el crédito bancario al cobrar

### Resolución

#### Paso 1: Gross-up del valor de la franquicia

USD 600.000 es lo que recibe American Food **neto** de la retención brasilera del 10%:

- X = valor bruto de la franquicia
- X − 10% × X = 600.000
- 0,90 × X = 600.000
- **X = USD 666.667** (valor bruto)
- **Retención Brasil = USD 66.667**
- American Food cobra efectivamente: **USD 600.000**

Para Ganancias Argentina, el residente debe declarar la **renta mundial al valor bruto** (USD 666.667). La retención brasilera es tax credit.

#### Paso 2: IVA — Exportación de servicios, tasa 0%

La franquicia incluye cesión temporal de marca + servicios de asesoramiento.

> ==**Material 4 — Controversias del Objeto, Franquicia**==: la franquicia está gravada con IVA porque incluye el derecho de uso más la prestación de servicios asociados.

Sin embargo, el cliente es brasilero (no residente) y los restaurants estarán en Brasil → ==utilización económica en el exterior==.

| Requisito exportación de servicios | Cumplimiento |
|---|---|
| Lugar de prestación: Argentina | ✅ Sí (American Food opera desde AR) |
| Cliente no residente | ✅ Sí (grupo brasilero) |
| Utilización económica en el exterior | ✅ Sí (restaurants en Brasil) |

→ ==**Exportación de servicios → tasa 0%**==.

American Food **no cobra IVA** al grupo brasilero y puede recuperar el CF vinculado a la prestación de la franquicia.

#### Paso 3: IIBB — Exenta (exportación de servicios)

La franquicia se presta a un cliente del exterior para ser utilizada en Brasil.

> ==**Material 8 — IIBB Exenciones**==: están exentos los ingresos obtenidos por la exportación de servicios que se efectivicen en el exterior.

==**IIBB = 0**==

#### Paso 4: IDyCB

Al cobrar el ingreso, American Food acredita en su cuenta bancaria USD 600.000:
- Crédito bancario: 600.000 × 0,6% = ==**USD 3.600**==

*(El IDyCB por débitos dependerá de los costos pagados, pero el ejercicio pide solo el efecto de impuestos sobre los ingresos.)*

#### Paso 5: Ganancias — con tax credit Brasil

| Concepto | Monto |
|---|---|
| Ingreso bruto devengado | 666.667 |
| Ganancias AR bruta (30%) | 200.000 |
| (-) Tax credit Brasil (retención de fuente extranjera) | (66.667) |
| ==**Ganancias AR neta**== | ==**133.333**== |

**Límite del tax credit**: la retención del exterior es computable hasta el límite de la alícuota argentina aplicada sobre esa renta.
- Límite: 666.667 × 30% = 200.000
- Tax credit disponible: 66.667 < 200.000 → ==**se computa la totalidad**==.

> ==**Material 2 — Ganancias residentes Art. 168**==: los residentes argentinos pueden computar como crédito los impuestos análogos al Impuesto a las Ganancias abonados en el exterior sobre rentas de fuente extranjera, hasta el límite de la alícuota argentina.

#### Paso 6: Resultado — monto de ingresos netos

| Impuesto | Monto |
|---|---|
| IVA | 0 (tasa 0%, exportación) |
| IIBB | 0 (exento, exportación) |
| IDyCB | 3.600 |
| Ganancias neta | 133.333 |
| ==**Total impuestos**== | ==**136.933**== |

| Concepto | Flujo de caja | Base devengada |
|---|---|---|
| Cobro efectivo | 600.000 | — |
| Ingreso bruto devengado | — | 666.667 |
| (-) Ganancias neta | (133.333) | (133.333) |
| (-) IDyCB | (3.600) | (3.600) |
| ==**Ingresos netos**== | ==**463.067**== | **529.734** |

==La diferencia entre ambas columnas (USD 66.667) es la retención brasilera: American Food la declara como ingreso en AR (por renta mundial) y la usa como tax credit, pero **no la cobra en efectivo**. El monto de ingresos netos en términos de caja es **USD 463.067**.==

### Variante: ¿qué pasa si NO se pudiera computar el tax credit?

> [!note]
> Si Argentina no tuviera convenio con Brasil o el impuesto no fuera "análogo", no se podría computar el tax credit. En ese caso:
> - Ganancias AR bruta: 200.000 (sin crédito)
> - Ingresos netos en caja: 600.000 - 200.000 - 3.600 = ==**USD 396.400**==
> - La doble imposición (paga impuesto en Brasil + en Argentina) cuesta USD 66.667 adicionales.
>
> ==El tax credit vale **USD 66.667** de diferencia en el resultado==.

### Por qué este ejercicio

Es el caso integral más completo del curso. Practica simultáneamente:

1. ==Gross-up al revés== (a partir del neto cobrado, calcular el bruto declarable).
2. ==Tax credit== con el límite de la alícuota argentina.
3. ==Identificación de exportación de servicios== en IVA (tasa 0%) y en IIBB (exenta).
4. ==IDyCB sobre el crédito bancario== al cobrar.
5. ==Distinción flujo de caja vs base devengada== (el resultado fiscal no coincide con el cash que recibís).

==Error típico 1==: olvidar el gross-up. Calcular Ganancias sobre USD 600.000 en vez de USD 666.667. Subestima el impuesto y el tax credit.

==Error típico 2==: pensar que la exportación está "exenta" de IVA. ==No==. Está gravada a tasa 0%, que es distinto: permite recuperar CF. Conceptualmente importa.

==Error típico 3==: olvidar el IDyCB. Es un impuesto chico (0,6%) pero presente en todos los cobros bancarios. En un parcial, no incluirlo te baja puntos.

---

## Caso II — Empresa de telefonía IP: efecto de la exención de IVA

### Status

⏳ **Solo enunciado disponible. Resolución de la cátedra pendiente.**

### Enunciado

> CFO de empresa de telefonía IP (residente fiscal argentina). Estructura de costos directos del servicio mensual:
>
> | Tipo de costo | Costo | IVA por importación de servicios | IVA |
> |---|---|---|---|
> | Proveedores del exterior | 50 | 10,50 | — |
> | Proveedores locales | 50 | — | 10,50 |
> | Sueldos | 600 | — | — |
> | **Total costos** | **700** | | |
>
> Hasta junio 2022: precio de venta = **USD 945 + IVA = USD 1.143,45**.
> La compañía aplica **35% adicional** sobre costos directos (costos indirectos + margen).
>
> En **julio 2023**: una ley exime de IVA a los servicios de telefonía IP → la empresa **deja de ser Responsable Inscripta en IVA**.
>
> **Pregunta**: Manteniendo el 35% de markup sobre costos directos, ¿el nuevo precio de venta a consumidor final debe ser USD 945? En caso negativo, calcule el precio correcto.

### Conceptos involucrados (preview)

- [[IVA - Exenciones]] — pérdida del derecho a computar CF
- [[IVA - Concepto y Logica]] — cuando el IVA deja de ser neutro y se vuelve costo
- [[IVA - Importacion de Servicios]] — responsable sustituto y CF

> Cuando esté la resolución de la cátedra, va acá.

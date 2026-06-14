# Material 12 — Caso II: Asesoramiento tributario a empresa rumana (ERP)

> Impuestos: [[IVA - Exportaciones]], [[IIBB - Exenciones y No Alcanzados]], [[Concepto - Utilizacion Economica]]
> Status: ⚠️ Generado por Claude — pendiente de validación. Basado en los hints del xlsx cátedra (no resuelto allí) y CLAUDE.md del vault.

---

## Enunciado (resumen)

CFO de una **sociedad argentina** dedicada a **asesoramiento tributario**.

Una compañía **rumana** creadora de un **ERP** (software de finanzas, RRHH, compras, ventas, etc.) los contacta para conocer los aspectos tributarios argentinos que su ERP debería contener **si decide comercializarlo en Argentina** (hoy el ERP no está en el mercado argentino).

- **Presupuesto disponible**: USD 15.000 totales, "por todo concepto", facturados a Rumania.
- **El cliente rumano aún no decidió** si va a entrar al mercado argentino — el asesoramiento sirve precisamente para **tomar esa decisión**.

Se consulta:
1. Tratamiento de los servicios en IVA e IIBB.
2. En caso de corresponder, alternativa/estrategia para evitar la gravabilidad en IVA e IIBB.

---

## Razonamiento — antes del tratamiento

La pregunta clave en exportación de servicios es **dónde se utiliza económicamente** el servicio. El cliente está en Rumania, pero **el contenido del servicio es sobre el sistema tributario argentino**. Eso genera una **tensión**:

- **Por contenido**: el asesoramiento es sobre normativa AR → "sirve" para operar en AR → utilización económica en AR → **gravado**.
- **Por destino**: el resultado (el informe) lo recibe y usa la empresa rumana en Rumania para decidir si entrar o no → utilización económica en Rumania → **exportación**.

==**La clave del ejercicio**: la utilización económica se define por **dónde se toma la decisión** y **dónde se aprovecha el resultado**, no por la **materia** del asesoramiento.==

> Analogía con [[Material 11 - Caso I — Franquicia DETROIT en Brasil]]: el saber-hacer es argentino, pero la utilización económica está en Brasil → exportación. Acá el saber tributario es argentino, pero quien lo usa para decidir está en Rumania.

### Estado fáctico al momento de emitir factura

El servicio se presta **antes** de que el cliente decida si entra al mercado argentino. Al cierre del trabajo (cuando se factura), **el cliente todavía no ha decidido instalar el ERP en AR**. La utilización inmediata del informe es la **toma de decisión en Rumania**.

Esto abre la posibilidad de tratarlo como **exportación de servicios**:
- IVA: tasa 0% (no exento — permite recuperar CF vinculado).
- IIBB: exento por exportación de servicios.

---

## Pregunta 1 — Tratamiento por defecto en IVA e IIBB

### Análisis sin estrategia adicional

Si no se toma ninguna precaución contractual, el riesgo es que AFIP/ARBA encuadre el servicio como **utilizado económicamente en AR** porque el contenido es íntegramente sobre normativa argentina y "previsiblemente" se aprovechará en AR si el ERP se comercializa allí.

| Impuesto | Tratamiento por defecto (sin precaución contractual) |
|---|---|
| **IVA** | Riesgo de **gravado al 21%** por utilización económica argentina (contenido sobre AR, fin instrumental: comercializar en AR). |
| **IIBB** | Riesgo de **gravado al 3%** por mismo criterio. Sociedad → siempre alcanzada (no aplica exención de profesiones liberales). |
| **Ganancias** | Renta de fuente AR para residente AR → 30% (no se discute). |

### Implicancias económicas si se considera gravado

USD 15.000 es **por todo concepto** (total facturado, IVA incluido):

| Concepto | USD |
|---|---:|
| Total facturado | 15.000,00 |
| Neto gravado (15.000 / 1,21) | 12.396,69 |
| IVA débito (21%) | 2.603,31 |
| IIBB (3% s/12.396,69) | 371,90 |
| **Ingreso neto antes de costos y IIGG** | **12.024,79** |

==**Si se trata como gravado, USD 2.975,21 (~19,8%) se evapora en IVA + IIBB** (incluso antes de IIGG sobre la utilidad).==

---

## Pregunta 2 — Estrategia para evitar la gravabilidad

### La estrategia: cláusula contractual de "no desembarco en Argentina"

Incluir en el contrato una **cláusula expresa** donde el cliente rumano declare que **el asesoramiento es un estudio de factibilidad / feasibility study** y que, **al momento de contratar y facturar, NO ha decidido comercializar el ERP en Argentina**. Más fuerte aún: que el resultado del trabajo será utilizado **en Rumania** para tomar una decisión que aún no está tomada.

==**Con esta cláusula, el servicio se encuadra como exportación de servicios**:==
- **IVA: tasa 0%** (no exenta — permite recuperar CF vinculado al período).
- **IIBB: exento** por exportación de servicios efectivizada en el exterior.

### Por qué funciona la estrategia

1. **Utilización económica = donde se toma la decisión**. Al momento de la factura, la decisión se toma en Rumania. El informe se *consume* allá.
2. **No basta con el cliente del exterior**: la cátedra (y el vault) ya advierten que el domicilio del cliente no define la exportación — define el lugar de utilización. La cláusula sirve para **documentar/probar** la utilización en el exterior.
3. **Si después el rumano entra a Argentina**, esa es una **decisión posterior**; el servicio originalmente prestado (feasibility) ya fue consumido en Rumania.

### Requisitos para que la estrategia sea defendible

| Requisito | Detalle |
|---|---|
| Cláusula contractual explícita | Declaración del cliente: "el servicio se utilizará exclusivamente en Rumania para evaluar la conveniencia/factibilidad" |
| Naturaleza del entregable | Informe/análisis (feasibility), no implementación ni configuración de un ERP en producción AR |
| Documentación de respaldo | Conservar emails, minutas, informes que prueben el carácter analítico y la entrega al cliente en Rumania |
| Facturación correcta | Factura de exportación (E), receptor en Rumania, cobro del exterior |
| Trazabilidad del cobro | Cobro por banco con identificación de origen exterior |

### Comparación económica con/sin estrategia

| Concepto | Sin estrategia (gravado) | Con estrategia (exportación) |
|---|---:|---:|
| Facturado | 15.000 | 15.000 |
| Neto gravado | 12.396,69 | 15.000 |
| IVA débito | 2.603,31 | 0 (tasa 0%) |
| IIBB | 371,90 | 0 (exento) |
| **Ingreso neto antes IIGG** | **12.024,79** | **15.000** |
| Diferencia | — | **+2.975,21 (+24,7%)** |

==**La estrategia bien implementada salva ~USD 2.975 (~25% más de ingreso neto antes de IIGG).**==

---

## Riesgos y zonas grises

| Riesgo | Mitigación |
|---|---|
| **AFIP/ARBA reclamen IVA/IIBB ex-post** alegando que el ERP terminó comercializándose en AR | Cláusula contractual + naturaleza analítica del entregable + documentación. Si la entrada al mercado AR ocurre, fue una decisión posterior; el servicio originalmente prestado fue feasibility consumido en Rumania. |
| **Interpretación restrictiva**: si AFIP toma postura agresiva ("efectivización exterior" = no basta la entrega del informe, requiere uso productivo offshore) | Argumentar que toda la decisión empresarial se evalúa y toma desde Rumania, y que el informe es input directo a esa decisión |
| **Si el cliente rumano sí desembarca en AR poco tiempo después** | Distinguir: el servicio "feasibility" se consumió en Rumania al decidir. El "implementación" sería un nuevo contrato (que sí sería gravado AR) |

---

## Respuesta resumen al CFO

**Pregunta 1** — Tratamiento por defecto:

> En sentido estricto, si no estructuramos nada, hay alto riesgo de que IVA e IIBB consideren el servicio **utilizado económicamente en Argentina** (porque el contenido es íntegramente sobre normativa AR y la finalidad implícita es comercializar el ERP acá). Bajo ese encuadre: **IVA 21% gravado e IIBB 3% gravado** — perdés ~USD 2.975 sobre los USD 15.000 totales.

**Pregunta 2** — Estrategia:

> Sí. **Incluir en el contrato una cláusula** donde el cliente rumano declare que el asesoramiento es un **estudio de factibilidad** ("feasibility") que se utilizará **exclusivamente en Rumania** para **decidir si entra o no al mercado argentino**, y que al momento de contratar **no ha tomado esa decisión**.
>
> Con esa cláusula + entregable de naturaleza analítica + factura de exportación, el servicio se trata como **exportación de servicios**: **IVA tasa 0%** (recuperás CF vinculado) e **IIBB exento**. Te quedan los USD 15.000 enteros antes de IIGG y costos directos.

---

## Por qué este ejercicio

1. ==**La utilización económica no es el contenido del servicio**==: aunque hablemos de normativa AR, lo que define el lugar de utilización es **dónde se aprovecha** el resultado (Rumania para decidir).
2. ==**El contrato es la herramienta de planificación fiscal**==: la cláusula no inventa una realidad — documenta y refuerza la que ya existe (decisión aún no tomada).
3. ==**Diferencia tasa 0% (IVA) vs exento**==: tasa 0% permite recuperar CF vinculado; exento no. En exportación de servicios, IVA es tasa 0%.
4. ==**Sociedad en IIBB**==: siempre alcanzada; la exención aplica por la **exportación**, no por la naturaleza profesional del asesoramiento.
5. ==**Timing del análisis**==: al momento de la factura, la utilización es Rumania. Decisiones posteriores del cliente no recalifican el servicio ya prestado.

**Error típico 1**: pensar que por hablar de normativa AR el servicio es "para AR" → ignora la distinción contenido vs utilización.
**Error típico 2**: confundir tasa 0% (exportación, IVA) con exento — son distintos: tasa 0% recupera CF, exento no.
**Error típico 3**: no estructurar contractualmente la situación — el caso depende totalmente de la cláusula que documente la utilización en el exterior.
**Error típico 4**: aplicar la exención de profesiones liberales en IIBB — no aplica: el contribuyente es una sociedad.

---

## Notas del vault usadas

- [[IVA - Exportaciones]] — tasa 0%, recupero CF
- [[IIBB - Exenciones y No Alcanzados]] — exportación efectivizada en el exterior
- [[Concepto - Utilizacion Economica]] — criterio rector en servicios
- CLAUDE.md — "Exportación de servicios exenta: el servicio debe efectivizarse en el exterior, no basta que el cliente sea del exterior"
- xlsx cátedra Material 12 (Caso 2 — hints): "exportación de servicio", "es un servicio aun no utilizado en argentina y los rumanos aun no toman la decisión", "si pido en nuestro contrato que declaren que no van a desembarcar en argentina: NO lleva IVA porque NO hay utilización económica en argentina, NO grava IIBB"

> **Nota de validación**: estoy resolviendo este caso sin haber visto la solución oficial de cátedra. Los hints del xlsx van en la dirección de "exportación con cláusula contractual", lo cual coincide con mi razonamiento. Conviene confirmar con el profe si la cláusula contractual es suficiente o si hay requisitos adicionales (ej: dictamen de un estudio, registro en algún padrón especial).

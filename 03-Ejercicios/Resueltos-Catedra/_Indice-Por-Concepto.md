# Índice de casos resueltos — por concepto

> Usar este índice al resolver un ejercicio nuevo: identificar qué conceptos ya aparecieron, en qué casos y con qué resolución. Distinguir lo que es **patrón conocido** de lo que es **novedad**.

> **Nota**: los Materiales 06, 07 y 09 fueron archivados en `03-Ejercicios/_Archivo-Menor-Relevancia/` (menor relevancia para el parcial actual, que prioriza Materiales 10+). Sus precedentes siguen siendo válidos y los links de abajo apuntan a la ubicación nueva.

---

## Tax Credit

| Caso | Aplica | Clave |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 06/Caso 1 - Software Factory AR Paraguay\|Mat 06 · Caso 1]] | ❌ NO | Home office en AR → fuente argentina → retención del exterior es COSTO |
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 07/Caso 3 - Big Data Argentina Gobierno Frances\|Mat 07 · Caso 3]] | ✅ SÍ | Personal en Francia → fuente extranjera → retención es tax credit |
| [[Material 10/Caso III - DevArg CRM Empresa Peruana\|Mat 10 · Caso III]] | ✅ SÍ (parcial) | Solo se puede usar si hay Ganancias a pagar; con pérdida se pierde |
| [[Material 11/Caso I - Franquicia Detroit Brasil\|Mat 11 · Caso I]] | ✅ SÍ | Fuente extranjera + gross-up previo + límite alícuota AR (30%) |
| [[../../04-Parciales-Anteriores/Diciembre 2025/Resolucion\|Parcial Dic 2025]] | A1 ❌ / A2-A3 ✅ | A1 prestado en AR = fuente AR = costo. A2/A3 en BR = fuente extranjera = tax credit que se cancela contra retención |
| [[../../04-Parciales-Anteriores/Recuperatorio 2do Cuatrim 2025/Resolucion\|Recuperatorio 2025]] | A1 ❌ / A2 ✅ | Filmado en AR = fuente AR = retenciones CDI son costo. Filmado en Chile = fuente extranjera = tax credit |

**Patrón:** el tax credit depende de la **fuente** del ingreso. Y solo sirve si hay impuesto argentino contra el cual imputarlo. Cuando tax credit = costo retención exterior, el efecto neto en caja es neutro (no hay doble imposición).

---

## Gross-up

| Caso | Dirección | Clave |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 07/Caso 1 - Empresa UK Presta en Argentina\|Mat 07 · Caso 1]] | Neto → Bruto (empresa AR asume impuestos) | `Bruto = Neto / (1 − tasa efectiva)` |
| [[Material 11/Caso I - Franquicia Detroit Brasil\|Mat 11 · Caso I]] | Neto cobrado → Bruto declarable (retención extranjera) | `Bruto = Neto / (1 − tasa retención)` |
| [[../../04-Parciales-Anteriores/Recuperatorio 2do Cuatrim 2025/Resolucion\|Recuperatorio 2025]] | Neto en mano Gordon → Bruto base retención CDI + IVA sustituto | `Retención: 160k/0,90 = 177.777,78` / `IVA: 160k × 21/79 = 42.531,65` |

**Patrón:** siempre dividir por `(1 − tasa)`, nunca sumar la tasa al neto.

---

## Ganancias — Fuente (AR vs extranjera)

| Caso | Fuente | Criterio determinante |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 06/Caso 1 - Software Factory AR Paraguay\|Mat 06 · Caso 1]] | Argentina | Desarrollador trabaja desde AR (home office) |
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 07/Caso 3 - Big Data Argentina Gobierno Frances\|Mat 07 · Caso 3]] | Extranjera | Personal viaja y trabaja físicamente en Francia |
| [[Material 10/Caso I - Software Cadbury UK Argentina Uruguay\|Mat 10 · Caso I]] | Extranjera (desde UK) | Equipo trabaja físicamente en UK |
| [[Material 11/Caso I - Franquicia Detroit Brasil\|Mat 11 · Caso I]] | Extranjera | Utilización económica en Brasil |
| [[../../04-Parciales-Anteriores/Recuperatorio 2do Cuatrim 2025/Resolucion\|Recuperatorio 2025]] | A1: AR / A2: Extranjera | Filmado en AR → fuente AR. Filmado en Chile → fuente extranjera |

**Patrón:** la fuente la define **dónde se ejecuta la actividad**, no dónde está el cliente ni dónde se cobra.

---

## Ganancias — Beneficiarios del exterior / Art. 93

| Caso | Inc. aplicable | Tasa efectiva | Clave |
|---|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 06/Caso 3 - CEO Discografica Argentina\|Mat 06 · Caso 3]] | b) derechos de autor | 12,25% | Obra inscripta: 35% × 35% |
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 07/Caso 1 - Empresa UK Presta en Argentina\|Mat 07 · Caso 1]] | h) servicios técnicos sin asesoramiento | 31,5% | Presunción 90% × 35% |
| [[Material 10/Caso II - ARGSecurity Consultoria BMV Argentina\|Mat 10 · Caso II]] | h) empresa uruguaya | 31,5% | Renta de fuente AR → retención como agente |

**Patrón:** identificar el inciso correcto del Art. 93 antes de calcular. El 35% pleno casi nunca aplica directamente.

---

## Art. 24 LIG — Vinculadas del exterior

| Caso | Tipo de gasto | Regla |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 06/Caso 4 - Filial Multinacional Electrodomesticos\|Mat 06 · Caso 4]] | Inventario comprado a vinculada | Deduce cuando se vende Y si el pago fue antes del vto de DDJJ |
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 06/Caso 5 - Capital vs Prestamo Multinacional Austriaca\|Mat 06 · Caso 5]] | Intereses a vinculada | Art. 24 aplica → deducción al pago |
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 06/Caso 5 - Capital vs Prestamo Multinacional Austriaca\|Mat 06 · Caso 5]] | Diferencia de cambio sobre capital | Art. 24 NO aplica → deducción al devengo |

**Patrón:** Art. 24 solo activa cuando la renta **es fuente AR para el acreedor** (intereses sí; capital no).

---

## Reorganización libre de impuestos (Art. 77)

| Caso | Cumple | Requisito crítico |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 07/Caso 2 - Reorganizacion Libre de Impuestos\|Mat 07 · Caso 2]] | ❌ NO (60% < 80%) | Control ≥ 80% del capital por **2 años previos** en AMBAS entidades |

**Patrón:** el porcentaje (80%) y el plazo (2 años previos) son los dos filtros. Si falla uno, no aplica el régimen.

---

## Fideicomiso — quién tributa

| Caso | Situación | Regla |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 06/Caso 2 - Fideicomiso Construccion al Costo\|Mat 06 · Caso 2]] | Mezcla residentes + no residentes | Residentes: como fiduciantes. No residentes: el fideicomiso. Opción unificada: 5 años mínimo |

---

## Condonación de deuda / Diferencias de cambio

| Caso | Concepto | Tratamiento |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 06/Caso 5 - Capital vs Prestamo Multinacional Austriaca\|Mat 06 · Caso 5]] | Condonación de capital | Ingreso gravado (teoría del balance: negocio real) |
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 06/Caso 5 - Capital vs Prestamo Multinacional Austriaca\|Mat 06 · Caso 5]] | Diferencia de cambio sobre capital | Deducible al devengar (Art. 24 no aplica al capital) |

---

## IVA — Exportación de servicios (tasa 0%)

| Caso | Requisitos verificados | Consecuencia |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 07/Caso 3 - Big Data Argentina Gobierno Frances\|Mat 07 · Caso 3]] | Prestación en AR, cliente no residente, uso en el exterior | Tasa 0%, CF vinculado recuperable |
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 09/Caso IV - IVA IIBB Venta Marca Plataforma Digital\|Mat 09 · Caso IV (b)]] | Prestado en exterior, uso parcial en AR (60%) | Solo el 40% es exportación; 60% gravado al 21% |
| [[Material 10/Caso I - Software Cadbury UK Argentina Uruguay\|Mat 10 · Caso I]] | Prestación en AR, uso 80% AR / 20% UY | Porción AR: 21%; porción UY: tasa 0% |
| [[Material 10/Caso III - DevArg CRM Empresa Peruana\|Mat 10 · Caso III]] | Cliente no residente, uso en Perú | Tasa 0%, CF del proveedor recuperable |
| [[Material 11/Caso I - Franquicia Detroit Brasil\|Mat 11 · Caso I]] | Ídem + cesión temporal de marca | Tasa 0%, no cobra IVA al cliente brasilero |
| [[Material 12/Caso II - Asesoramiento Tributario Rumania\|Mat 12 · Caso II]] | ERP no disponible en AR → utilización no verificada en AR al momento del HI | Tasa 0%; si hay duda, firmar declaración del cliente |

**Patrón:** tasa 0% ≠ exento. Permite recuperar CF. Y puede aplicarse parcialmente según % de uso en el exterior. **El análisis de utilización se hace al momento del hecho, no sobre usos futuros hipotéticos.**

---

## IVA — CF de exportaciones (saldo a favor recuperable)

| Caso | Situación | Clave |
|---|---|---|
| [[Material 10/Caso III - DevArg CRM Empresa Peruana\|Mat 10 · Caso III]] | Proveedor AR factura con IVA, DevArg exporta | CF es activo recuperable (devolución/compensación AFIP), NO costo |

**Patrón:** en exportaciones a tasa 0%, el IVA que te cobra el proveedor local es **recuperable**. No tratarlo como costo es la clave de la opción a.1.

---

## IVA — Responsable sustituto

| Caso | Condición de la empresa AR | Consecuencia del IVA |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 07/Caso 1 - Empresa UK Presta en Argentina\|Mat 07 · Caso 1]] | RI en IVA | Ingresa IVA como sustituto → CF al mes siguiente → **NEUTRO** |
| [[Material 10/Caso II - ARGSecurity Consultoria BMV Argentina\|Mat 10 · Caso II]] | RI en IVA, contrata empresa UY | Sustituto → CF 17.850 > DF 17.355 → saldo a favor |
| [[Material 10/Caso III - DevArg CRM Empresa Peruana\|Mat 10 · Caso III]] | RI, contrata empresa peruana | Sustituto por IVA AR (neutro) + IVA peruano irrecuperable (costo) |
| [[Material 11/Caso II - Telefonia IP Exencion IVA\|Mat 11 · Caso II]] | Deja de ser RI (exención) | Obligación de sustituto desaparece → IVA del exterior **no es costo** |

**Patrón clave:** el IVA del exterior (responsable sustituto) es una obligación propia del RI. Si dejás de ser RI, esa obligación desaparece. El IVA de proveedores locales está dentro del precio del proveedor → sí se vuelve costo al perder la condición de RI.

---

## IVA — Exención y pérdida de neutralidad

| Caso | Qué se vuelve costo | Qué no |
|---|---|---|
| [[Material 11/Caso II - Telefonia IP Exencion IVA\|Mat 11 · Caso II]] | IVA de proveedores locales (dentro del precio del proveedor) | IVA de importación de servicios (obligación propia que desaparece) |

---

## IVA — Nacimiento del HI y diferencias de cambio

| Caso | Problema | Consecuencia |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 07/Caso 4 - Shopping Center Empresa Francesa IVA\|Mat 07 · Caso 4]] | Descalce temporal CF/DF en inflación | CF en pesos se devalúa; estructurar para que nazcan al mismo tiempo |
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 09/Caso V - IVA IIBB Automotriz Cuotas USD\|Mat 09 · Caso V]] | HI nace al entregar el bien; cuotas se cobran después | Pago inicial mínimo = IVA neto + IIBB al momento de la venta |
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 09/Caso V - IVA IIBB Automotriz Cuotas USD\|Mat 09 · Caso V]] | Diferencias de cambio al cobrar cuotas en pesos a TC mayor | Gravadas con IVA (teoría unicidad) → comprobante adicional por cada cuota |

---

## IVA — Empresa constructora

| Caso | ¿Es empresa constructora? | Clave |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 09/Caso III - IVA IIBB Planta Industrial Barracas\|Mat 09 · Caso III]] | ❌ NO | Construyó para uso propio, no con propósito de lucro por venta |

**Patrón:** el propósito al momento de construir define si hay HI. Construir para uso propio ≠ empresa constructora.

---

## IVA — Ajuste CF inmueble (Art. 11 DR, período 10 años)

| Caso | ¿Hay reintegro? | Clave |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 09/Caso III - IVA IIBB Planta Industrial Barracas\|Mat 09 · Caso III]] | ❌ NO | CF computado en 1998; período de 10 años venció en 2008; venta en 2022 |

**Patrón:** verificar si los 10 años desde la finalización de la obra ya pasaron. Si sí → no hay reintegro.

---

## IVA — Cesión definitiva de marca

| Caso | Tratamiento | Certeza |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 09/Caso IV - IVA IIBB Venta Marca Plataforma Digital\|Mat 09 · Caso IV (a)]] | NO gravada | Sin ambigüedad — ni Ley ni DR incluyen la transferencia definitiva de derechos |

---

## IIBB — Alcance, exención y habitualidad

| Caso | Alcanzada | Clave |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 09/Caso I - IIBB Consultora Sistemas\|Mat 09 · Caso I]] | ✅ SÍ (sociedad) | Exención de profesiones liberales solo aplica a profesional individual, no a empresa |
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 09/Caso IV - IVA IIBB Venta Marca Plataforma Digital\|Mat 09 · Caso IV (a)]] | ❌ NO (venta de marca) | Hecho aislado, no corresponde al objeto habitual; marca nunca afectada al ciclo comercial |

**Patrón:** sociedad → siempre alcanzada. La exención de profesiones liberales requiere ejercicio individual y sin estructura empresarial.

---

## IIBB — Convenio Multilateral (CM)

| Caso | Régimen | Clave |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 09/Caso I - IIBB Consultora Sistemas\|Mat 09 · Caso I]] | CM — Régimen General (50/50) | Gastos E ingresos en más de una jurisdicción → CM. Sociedad → no aplica régimen especial |

**Patrón:** el CM requiere gastos **Y** ingresos en más de una jurisdicción. No alcanza con tener clientes en otras provincias. Las sociedades van siempre al Régimen General (50% gastos / 50% ingresos).

---

## IIBB — Bien de uso: categoría al momento de la venta

| Caso | Categoría al vender | IIBB |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 09/Caso III - IVA IIBB Planta Industrial Barracas\|Mat 09 · Caso III]] | "Otros Bienes" (desafectada en 2020) | ✅ SÍ gravada |
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 09/Caso II - IIBB Grupo Economico Recupero Gastos\|Mat 09 · Caso II]] | Bien de cambio (para el vendedor) | ✅ SÍ gravada |

**Patrón:** si el bien se desafecta de "Bienes de Uso" antes de la venta → paga IIBB. Recomendación: no cambiar la categoría aunque el bien no se use.

---

## IIBB — Recupero de gastos / intermediarios

| Caso | Tratamiento | Clave |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 09/Caso II - IIBB Grupo Economico Recupero Gastos\|Mat 09 · Caso II]] | NO gravado | Pago por cuenta y orden de tercero → no es ingreso propio |

---

## IIBB — Exención por exportación de servicios

| Caso | Aplica exención | Requisito |
|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 09/Caso IV - IVA IIBB Venta Marca Plataforma Digital\|Mat 09 · Caso IV (b)]] | Parcial (40% exportación) | Solo la porción efectivizada en el exterior está exenta |
| [[Material 10/Caso I - Software Cadbury UK Argentina Uruguay\|Mat 10 · Caso I]] | Parcial (20% UY exento, 80% AR gravado) | La porción utilizada en AR no es exportación |
| [[Material 10/Caso III - DevArg CRM Empresa Peruana\|Mat 10 · Caso III]] | ✅ SÍ (100%) | Servicio que se efectiviza íntegramente en el exterior |
| [[Material 11/Caso I - Franquicia Detroit Brasil\|Mat 11 · Caso I]] | ✅ SÍ (100%) | Servicio que se efectiviza íntegramente en el exterior |
| [[../../04-Parciales-Anteriores/Recuperatorio 2do Cuatrim 2025/Resolucion\|Recuperatorio 2025]] | ✅ SÍ (100%) | Derechos de exhibición utilizados 100% en Chile, Brasil, México |
| [[Material 12/Caso II - Asesoramiento Tributario Rumania\|Mat 12 · Caso II]] | ✅ SÍ (100%) | ERP no disponible en AR al momento del HI → sin utilización verificada en AR |

**Patrón:** no alcanza con que el cliente sea del exterior. El servicio debe efectivizarse afuera. Si hay uso parcial en AR, la exención aplica solo a la porción exterior. **El análisis se hace al momento del hecho, no sobre destinos futuros inciertos.**

---

## Contrato de no uso — protección ante utilización económica futura incierta

| Caso | Situación | Consecuencia según contrato |
|---|---|---|
| [[Material 12/Caso II - Asesoramiento Tributario Rumania\|Mat 12 · Caso II]] | Cliente extranjero podría usar el asesoramiento en Argentina en el futuro | Sin contrato: AFIP cobra IVA si se verifica uso en AR. Con contrato de no uso: respaldo para mantener tasa 0%; responsabilidad recae en el cliente |

**Patrón:** cuando la utilización económica futura en Argentina es incierta, la estrategia de planificación es obtener una declaración/contrato firmado por el cliente extranjero comprometiéndose a no usar el servicio en Argentina. Si más adelante igual lo usa: sin contrato → paga IVA la empresa argentina; con contrato → tiene respaldo y la responsabilidad es del cliente.

---

## IDyCB

| Caso | Momento | Monto |
|---|---|---|
| [[Material 10/Caso I - Software Cadbury UK Argentina Uruguay\|Mat 10 · Caso I]] | Débitos (sueldos) + créditos (cobro) | (500K + 350K) × 0,6% = USD 5.100 |
| [[Material 10/Caso II - ARGSecurity Consultoria BMV Argentina\|Mat 10 · Caso II]] | Débitos + créditos por opción | Varía según si el costo genera débito bancario |
| [[Material 11/Caso I - Franquicia Detroit Brasil\|Mat 11 · Caso I]] | Al acreditar cobro en cuenta bancaria | 600K × 0,6% = USD 3.600 |
| [[../../04-Parciales-Anteriores/Recuperatorio 2do Cuatrim 2025/Resolucion\|Recuperatorio 2025]] | Ingresos (cobro neto) + egresos (incl. IVA recuperable) | Régimen Resto: 2/3 pérdida + 1/3 crédito Ganancias |

**Patrón:** presente en toda operación que cobra/paga por cuenta bancaria. Siempre incluirlo.

---

## IVA — Precio "todo incluido" → gross-down

| Caso | Situación | Cálculo |
|---|---|---|
| [[../../04-Parciales-Anteriores/Diciembre 2025/Resolucion\|Parcial Dic 2025]] | Precio pactado incluye IVA → hay que descontar | Neto = precio / 1,21; IVA incluido = precio − neto |

**Patrón:** cuando el precio es "por todo concepto" o "impuestos incluidos", el ingreso neto gravado es menor que el precio. No hacer el gross-down sobreestima el ingreso en un 21%.

---

## IDyCB — Egresos que generan débito bancario

| Caso | Egreso incluido | Clave |
|---|---|---|
| [[../../04-Parciales-Anteriores/Diciembre 2025/Resolucion\|Parcial Dic 2025]] | IVA a ingresar a AFIP + IVA sustituto | Son egresos bancarios reales aunque sean neutros en el resultado → generan IDyCB |
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 09/Caso V - IVA IIBB Automotriz Cuotas USD\|Mat 09 · Caso V]] | IVA neto a pagar | Egreso real → pago inicial mínimo para cubrirlo |

**Patrón:** IDyCB se calcula sobre los movimientos bancarios reales, incluyendo pagos a AFIP por IVA. Aunque el IVA sea neutro en el P&L, el movimiento de caja existe.

---

## Rentabilidad sobre costos como criterio de decisión

| Caso | Umbral | Consecuencia |
|---|---|---|
| [[../../04-Parciales-Anteriores/Recuperatorio 2do Cuatrim 2025/Resolucion\|Recuperatorio 2025]] | ≥ 30% | A1 = 16,15% → RECHAZA; A2 = 30,83% → ACEPTA |

**Patrón:** resultado positivo no alcanza. Siempre calcular `rentabilidad = resultado / costos totales` y comparar con el umbral pedido.

---

## IVA sustituto — Necesidad financiera vs costo en P&L

| Caso | ¿Costo P&L? | ¿Necesidad financiera? | Clave |
|---|---|---|---|
| [[_Archivo-Menor-Relevancia/Resueltos-Catedra/Material 07/Caso 1 - Empresa UK Presta en Argentina\|Mat 07 · Caso 1]] | ❌ NO (CF recuperable) | ✅ SÍ (egreso hasta recupero) | El sustituto es transitorio; el CF vuelve el mes siguiente |
| [[../../04-Parciales-Anteriores/Recuperatorio 2do Cuatrim 2025/Resolucion\|Recuperatorio 2025]] | ❌ NO (CF recuperable) | ✅ SÍ (42.531,65) | IVA Gordon: no impacta resultado pero sí el dinero necesario |

**Patrón:** al calcular "cuánto dinero necesito", incluir el IVA sustituto aunque sea recuperable. Al calcular resultado (P&L), excluirlo.

---

## Mapa de conceptos por caso

| Caso | Conceptos principales |
|---|---|
| Mat 06 · Caso 1 | Tax credit ❌, Fuente AR |
| Mat 06 · Caso 2 | Fideicomiso, residentes vs no residentes |
| Mat 06 · Caso 3 | Art. 93 (múltiples incisos), Fuente por tipo de pago |
| Mat 06 · Caso 4 | Art. 24, Inventario, Devengo vs pago |
| Mat 06 · Caso 5 | Capital vs deuda, Diferencias de cambio, Condonación |
| Mat 07 · Caso 1 | Gross-up, Art. 93 inc. h, IVA sustituto RI |
| Mat 07 · Caso 2 | Reorganización Art. 77, 80% / 2 años |
| Mat 07 · Caso 3 | Tax credit ✅, Fuente extranjera, IVA tasa 0% |
| Mat 07 · Caso 4 | IVA nacimiento HI, Inflación + CF |
| Mat 09 · Caso I | IIBB sociedad alcanzada, CM Régimen General |
| Mat 09 · Caso II | IIBB recupero gastos, bienes de cambio vs uso |
| Mat 09 · Caso III | IVA empresa constructora ❌, Ajuste CF 10 años, IIBB bien de uso desafectado |
| Mat 09 · Caso IV | IVA cesión definitiva marca ❌, IIBB habitualidad, Exportación parcial |
| Mat 09 · Caso V | IVA nacimiento HI + cuotas, Diferencias de cambio, Pago inicial mínimo |
| Mat 10 · Caso I | Exportación parcial (AR/UY), Desde AR vs UK, Porcentajes de uso |
| Mat 10 · Caso II | IVA utilización económica en AR ≠ exportación, Sustituto, Retención 31,5% |
| Mat 10 · Caso III | CF exportaciones recuperable, Tax credit parcial, IVA local vs exterior |
| Mat 11 · Caso I | Gross-up, Tax credit ✅, IVA tasa 0%, IIBB exenta, IDyCB |
| Mat 11 · Caso II | IVA exención, pérdida neutralidad, sustituto desaparece |
| Parcial Dic 2025 | Precio todo incluido (gross-down), Tax credit vs costo, Exportación parcial, IDyCB sobre egresos AFIP |
| Recuperatorio 2025 | Exportación total (distribución por ventas), Tax credit A1 ❌/A2 ✅, Gross-up Gordon, IVA sustituto ≠ costo, Rentabilidad mínima 30% |
| Mat 12 · Caso II | Exportación de servicios (utilización incierta al momento del HI), Contrato de no uso como respaldo, IVA tasa 0%, IIBB exento |

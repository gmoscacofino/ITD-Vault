# Índice de casos resueltos — por concepto

> Usar este índice al resolver un ejercicio nuevo: identificar qué conceptos ya aparecieron, en qué casos y con qué resolución. Distinguir lo que es **patrón conocido** de lo que es **novedad**.

---

## Tax Credit

| Caso | Aplica | Clave |
|---|---|---|
| [[Material 06/Caso 1 - Software Factory AR Paraguay\|Mat 06 · Caso 1]] | ❌ NO | Home office en AR → fuente argentina → retención del exterior es COSTO |
| [[Material 07/Caso 3 - Big Data Argentina Gobierno Frances\|Mat 07 · Caso 3]] | ✅ SÍ | Personal en Francia → fuente extranjera → retención es tax credit |
| [[Material 11/Caso I - Franquicia Detroit Brasil\|Mat 11 · Caso I]] | ✅ SÍ | Fuente extranjera + gross-up previo + límite alícuota AR (30%) |

**Patrón:** el tax credit depende exclusivamente de la **fuente** del ingreso, no de quién paga la retención.

---

## Gross-up

| Caso | Dirección | Clave |
|---|---|---|
| [[Material 07/Caso 1 - Empresa UK Presta en Argentina\|Mat 07 · Caso 1]] | Neto → Bruto (empresa AR asume impuestos) | `Bruto = Neto / (1 − tasa efectiva)` |
| [[Material 11/Caso I - Franquicia Detroit Brasil\|Mat 11 · Caso I]] | Neto cobrado → Bruto declarable (retención extranjera) | `Bruto = Neto / (1 − tasa retención)` |

**Patrón:** siempre dividir por `(1 − tasa)`, nunca sumar la tasa al neto.

---

## Ganancias — Fuente (AR vs extranjera)

| Caso | Fuente | Criterio determinante |
|---|---|---|
| [[Material 06/Caso 1 - Software Factory AR Paraguay\|Mat 06 · Caso 1]] | Argentina | Desarrollador trabaja desde AR (home office) |
| [[Material 07/Caso 3 - Big Data Argentina Gobierno Frances\|Mat 07 · Caso 3]] | Extranjera | Personal viaja y trabaja físicamente en Francia |
| [[Material 11/Caso I - Franquicia Detroit Brasil\|Mat 11 · Caso I]] | Extranjera | American Food opera desde AR pero la utilización es en Brasil |

**Patrón:** la fuente la define **dónde se ejecuta la actividad**, no dónde está el cliente ni dónde se cobra.

---

## Ganancias — Beneficiarios del exterior / Art. 93

| Caso | Inc. aplicable | Tasa efectiva | Clave |
|---|---|---|---|
| [[Material 06/Caso 3 - CEO Discografica Argentina\|Mat 06 · Caso 3]] | b) derechos de autor | 12,25% | Obra inscripta: 35% × 35% |
| [[Material 07/Caso 1 - Empresa UK Presta en Argentina\|Mat 07 · Caso 1]] | h) servicios técnicos sin asesoramiento | 31,5% | Presunción 90% × 35% |

**Patrón:** identificar primero el inciso correcto del Art. 93 antes de calcular. El 35% pleno casi nunca aplica directamente.

---

## Art. 24 LIG — Vinculadas del exterior

| Caso | Tipo de gasto | Regla |
|---|---|---|
| [[Material 06/Caso 4 - Filial Multinacional Electrodomesticos\|Mat 06 · Caso 4]] | Inventario comprado a vinculada | Se deduce cuando se vende Y si el pago fue antes del vto de DDJJ |
| [[Material 06/Caso 5 - Capital vs Prestamo Multinacional Austriaca\|Mat 06 · Caso 5]] | Intereses a vinculada | Art. 24 aplica → deducción al pago (no al devengo) |
| [[Material 06/Caso 5 - Capital vs Prestamo Multinacional Austriaca\|Mat 06 · Caso 5]] | Diferencia de cambio sobre capital | Art. 24 NO aplica → deducción al devengo |

**Patrón:** Art. 24 solo activa cuando la renta **es fuente AR para el acreedor** (intereses sí; devolución de capital no).

---

## Reorganización libre de impuestos (Art. 77)

| Caso | Cumple | Requisito crítico |
|---|---|---|
| [[Material 07/Caso 2 - Reorganizacion Libre de Impuestos\|Mat 07 · Caso 2]] | ❌ NO (60% < 80%) | Control ≥ 80% del capital por **2 años previos** en AMBAS entidades |

**Patrón:** el porcentaje (80%) y el plazo (2 años previos) son los dos filtros. Si falla uno, no aplica el régimen.

---

## Fideicomiso — quién tributa

| Caso | Situación | Regla |
|---|---|---|
| [[Material 06/Caso 2 - Fideicomiso Construccion al Costo\|Mat 06 · Caso 2]] | Mezcla residentes + no residentes | Residentes: tributan como fiduciantes. No residentes: tributa el fideicomiso. Opción unificada: 5 años mínimo |

---

## Condonación de deuda / Diferencias de cambio

| Caso | Concepto | Tratamiento |
|---|---|---|
| [[Material 06/Caso 5 - Capital vs Prestamo Multinacional Austriaca\|Mat 06 · Caso 5]] | Condonación de capital | Ingreso gravado (teoría del balance: negocio real) |
| [[Material 06/Caso 5 - Capital vs Prestamo Multinacional Austriaca\|Mat 06 · Caso 5]] | Diferencia de cambio sobre capital | Deducible al devengar (Art. 24 no aplica al capital) |

---

## IVA — Exportación de servicios (tasa 0%)

| Caso | Requisitos verificados | Consecuencia |
|---|---|---|
| [[Material 07/Caso 3 - Big Data Argentina Gobierno Frances\|Mat 07 · Caso 3]] | Prestación en AR, cliente no residente, uso en el exterior | Tasa 0%, CF vinculado recuperable |
| [[Material 11/Caso I - Franquicia Detroit Brasil\|Mat 11 · Caso I]] | Ídem + cesión temporal de marca | Tasa 0%, no cobra IVA al cliente brasilero |

**Patrón:** tasa 0% ≠ exento. La diferencia: tasa 0% permite recuperar CF; exento no.

---

## IVA — Responsable sustituto

| Caso | Condición de la empresa AR | Consecuencia del IVA |
|---|---|---|
| [[Material 07/Caso 1 - Empresa UK Presta en Argentina\|Mat 07 · Caso 1]] | RI en IVA | Ingresa IVA como sustituto → CF al mes siguiente → **NEUTRO** |
| [[Material 11/Caso II - Telefonia IP Exencion IVA\|Mat 11 · Caso II]] | Deja de ser RI (exención) | Obligación de sustituto desaparece → IVA del exterior **no es costo** |

**Patrón clave:** el IVA del exterior (responsable sustituto) es una obligación propia del RI. Si dejás de ser RI, esa obligación desaparece. El IVA de proveedores locales, en cambio, está dentro del precio del proveedor → sí se vuelve costo al perder la condición de RI.

---

## IVA — Exención y pérdida de neutralidad

| Caso | Qué se vuelve costo | Qué no |
|---|---|---|
| [[Material 11/Caso II - Telefonia IP Exencion IVA\|Mat 11 · Caso II]] | IVA de proveedores locales (dentro del precio del proveedor) | IVA de importación de servicios (obligación propia que desaparece) |

---

## IVA — Nacimiento del HI y efecto inflacionario

| Caso | Problema | Solución |
|---|---|---|
| [[Material 07/Caso 4 - Shopping Center Empresa Francesa IVA\|Mat 07 · Caso 4]] | CF en pesos se devalúa si hay descalce temporal con el DF | Estructurar para que CF y DF nazcan al mismo tiempo (Alt. 2) |

---

## IIBB — Exención por exportación de servicios

| Caso | Aplica exención | Requisito |
|---|---|---|
| [[Material 11/Caso I - Franquicia Detroit Brasil\|Mat 11 · Caso I]] | ✅ SÍ | Servicio que **se efectiviza en el exterior** (restaurants en Brasil) |

**Patrón:** no alcanza con que el cliente sea del exterior. El servicio debe efectivizarse afuera.

---

## IDyCB

| Caso | Momento | Monto |
|---|---|---|
| [[Material 11/Caso I - Franquicia Detroit Brasil\|Mat 11 · Caso I]] | Al acreditar cobro en cuenta bancaria | 0,6% sobre el crédito bancario |

**Patrón:** presente en toda operación que cobra por cuenta bancaria. Chico pero siempre aparece.

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
| Mat 11 · Caso I | Gross-up, Tax credit ✅, IVA tasa 0%, IIBB exenta, IDyCB |
| Mat 11 · Caso II | IVA exención, pérdida neutralidad, sustituto desaparece |

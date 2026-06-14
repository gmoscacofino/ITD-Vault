# Material 13 — Caso II: Tesoria S.A. — Equipo propio vs. subcontratación Uruguay

> Impuestos: [[Ganancias - Beneficiarios del Exterior]], [[Gross-up]], [[IVA - Importacion de Servicios]], [[IIBB - Hecho Imponible]], [[IDyCB]]
> Status: ✅ Validado en clase

---

## Enunciado (resumen)

Tesoria S.A. (residente argentina, RI en IVA). Contrato con **BancoRegional Argentina** (AR, RI): implementar módulo de tesorería en 8 sucursales. **Precio fijo: USD 200.000**.

Dos formas de ejecutar:
- **Opción 1 — Equipo propio**: USD 130.000 en sueldos y viáticos.
- **Opción 2 — Subcontratar a FinTech Uruguay S.R.L.**: trabajo íntegro desde Montevideo, remoto. **USD 110.000**, **libre de retenciones argentinas** (Tesoria absorbe la retención).

El comercial dice: *"con la Opción 2 ahorramos USD 20.000 — claramente conviene subcontratar"*.

Tasas: Ganancias 30%, IVA 21%, IIBB 3%, IDyCB 1,2% (0,6%+0,6%), Ret. benef. exterior 31,5%, TC $1.000/USD, IDyCB vs Ganancias 33%.

---

## Razonamiento — antes de los números

El comercial compara **USD 130.000 vs USD 110.000** y concluye "ahorra 20.000". El error: ignora que la Opción 2 dispara **importación de servicios** con dos efectos que la Opción 1 no tiene:

1. **Retención IIGG benef. exterior**: 31,5%, absorbida por Tesoria (porque FinTech exige "libre de retenciones") → encarece el costo con **gross-up**.
2. **IVA-RS sobre USD 110.000**: 21% pagado a AFIP, recuperable como CF el mes siguiente (neutro económico pero **costo financiero importante**).

Adicionalmente, los **sueldos y viáticos locales (Opción 1) no llevan IVA-RS ni retención benef. exterior**.

### Ingresos del proyecto — iguales en ambas opciones

| Concepto | Importe (ARS) |
|---|---:|
| Precio neto facturado a BancoRegional | 200.000.000 |
| IVA débito (21%) | 42.000.000 |
| **Facturación total** | **242.000.000** |
| IIBB (3% sobre 200M) | 6.000.000 |

---

## Opción 1 — Equipo propio (USD 130.000 en sueldos y viáticos)

### Estado de Resultados

| Concepto | Importe |
|---|---:|
| Ingreso | 200.000.000 |
| (−) IIBB | (6.000.000) |
| (−) Sueldos y viáticos | (130.000.000) |
| (−) IDyCB (67% costo) | (1.688.400) |
| **Resultado antes IIGG** | **62.311.600** |
| (−) IIGG (30%) | (18.693.480) |
| ==**Resultado final**== | ==**43.618.120**== |

### Cashflow

| Concepto | Importe |
|---|---:|
| Ingresos cobrados (con IVA) | 242.000.000 |
| (−) IIBB | (6.000.000) |
| (−) Sueldos y viáticos | (130.000.000) |
| (−) IVA saldo a pagar (débito 42M − crédito 0) | (42.000.000) |
| (−) IDyCB | (2.520.000) |
| **Cashflow antes IIGG** | **61.480.000** |
| (−) IIGG | (18.693.480) |
| (+) Crédito IIGG por IDyCB 33% | 831.600 |
| ==**Cashflow del período**== | ==**43.618.120**== |

**IDyCB Opción 1**:
- Créditos bancarios: 242.000.000 × 0,6% = 1.452.000
- Débitos bancarios (6M IIBB + 130M sueldos + 42M IVA): 178.000.000 × 0,6% = 1.068.000
- Total: **2.520.000** → costo 67% (1.688.400) + crédito IIGG 33% (831.600)

---

## Opción 2 — Subcontratar a FinTech Uruguay (USD 110.000 libre de retenciones)

### Importación de servicios — gross-up de la retención

FinTech cobra **USD 110.000 netos** (no acepta retenciones). Tesoria absorbe la retención.

**Criterio de cátedra** (presunción de margen 90%):

```
Retención = Neto × 90% × 31,5%
Retención = 110.000.000 × 0,9 × 0,315 = 31.185.000

Costo bruto (a deducir como costo en IIGG) = Neto + Retención
Costo bruto = 110.000.000 + 31.185.000 = 141.185.000
```

> Comparación con el gross-up "puro" (Bruto = Neto / (1 − tasa efectiva 31,5%) = 160.583.941,6): la cátedra usa la versión simplificada arriba. Aquí seguimos el criterio cátedra.

**IVA-RS** (responsable sustituto, neutro económicamente pero outflow inmediato):
- IVA-RS = 110.000.000 × 21% = **23.100.000** → CF mes siguiente.

### Estado de Resultados

| Concepto | Importe |
|---|---:|
| Ingreso | 200.000.000 |
| (−) IIBB | (6.000.000) |
| (−) Costo subcontratación (gross-up: 110M + 31.185.000 retención) | (141.185.000) |
| (−) IDyCB (67% costo) | (1.826.225,7) |
| **Resultado antes IIGG** | **50.988.774,3** |
| (−) IIGG (30%) | (15.296.632,29) |
| ==**Resultado final**== | ==**35.692.142,01**== |

### Cashflow

| Concepto | Importe |
|---|---:|
| Ingresos cobrados (con IVA) | 242.000.000 |
| (−) IIBB | (6.000.000) |
| (−) Costo subcontratación con IVA (141.185.000 + IVA-RS 23.100.000) | (164.285.000) |
| (−) IVA débito (42M, saldo a pagar) | (42.000.000) |
| (−) IDyCB | (2.725.710) |
| **Cashflow antes IIGG** | **26.989.290** |
| (−) IIGG | (15.296.632,29) |
| (+) Crédito IIGG por IDyCB 33% | 899.484,3 |
| ==**Cashflow del período**== | ==**12.592.142,01**== |

**IDyCB Opción 2**:
- Créditos bancarios: 242.000.000 × 0,6% = 1.452.000
- Débitos bancarios (6M + 164,285M + 42M = 212,285M) × 0,6% = 1.273.710
- Total: **2.725.710** → costo 67% (1.826.225,7) + crédito IIGG 33% (899.484,3)

### Encuadre de impuestos sobre FinTech Uruguay

| Impuesto | ¿Aplica? | Comentario |
|---|---|---|
| IVA-RS | **SÍ** | Servicio del exterior usado en AR → 21% s/110M = 23.100.000 |
| IIBB | **NO** | FinTech no tiene actividad gravada en AR (presta desde Montevideo) |
| Ret. Ganancias benef. exterior | **SÍ, gross-up** | Tesoria absorbe → costo deducible 141.185.000 |

---

## Comparación final

| | **Opción 1 — Equipo propio** | **Opción 2 — FinTech Uruguay** | Diferencia |
|---|---:|---:|---:|
| Resultado EERR | 43.618.120 | 35.692.142 | **(7.925.978)** |
| Cashflow del período | 43.618.120 | 12.592.142 | **(31.025.978)** |
| Plata necesaria (egresos del período) | 178.000.000 | 212.285.000 | **+34.285.000** |

### Por qué la Opción 2 NO es más barata

1. **Retención absorbida (gross-up)**: 31.185.000 que no existían en Opción 1.
2. **IVA-RS upfront**: 23.100.000 que recupera el mes siguiente pero requiere caja hoy.
3. Resultado EERR: Opción 2 deja **~ARS 7,9M menos** (≈ USD 7.900 menos).
4. Cashflow del mes: Opción 2 deja **~ARS 31M menos** (la diferencia con EERR es el IVA-RS de 23,1M que es timing).

---

## Conclusión — qué le decís al comercial

> *"No, la Opción 2 no es más barata. El supuesto 'ahorro de USD 20.000' se evapora cuando ponés los impuestos: la cláusula 'libre de retenciones' nos obliga a absorber un gross-up de ARS 31 millones, y arriba pagamos IVA-RS de ARS 23 millones (que recuperamos el mes siguiente, pero hoy nos sale del bolsillo)."*
>
> *"En P&L, la Opción 1 nos deja ARS 7,9M más. En caja, la diferencia es de ARS 31M en el mes. Y necesitamos USD 34k extra disponibles para ejecutar la Opción 2. Si todo es exactamente lo descrito, conviene Opción 1."*

---

## Por qué este ejercicio

1. ==**El "ahorro pre-impuestos" engaña**==: el gross-up de la retención benef. exterior puede dar vuelta una comparación.
2. ==**Gross-up cátedra simplificado**==: Retención = Neto × 90% × 31,5% → Bruto = Neto + Retención. No es la fórmula algebraica pura, pero es lo que se usa.
3. ==**IVA-RS es neutro económicamente pero NO en caja**==: timing de 1 mes, impacto fuerte si el proyecto es grande.
4. ==**Distinción EERR vs. cashflow**==: la Opción 2 deja peor cashflow por la suma de gross-up + IVA-RS upfront.
5. ==**IDyCB siempre Resto**== (regla CLAUDE.md): 67% costo + 33% crédito IIGG.

**Error típico 1**: comparar solo USD 130k vs USD 110k → ignora gross-up e IVA-RS.
**Error típico 2**: aplicar 31,5% sobre el bruto (1.890.000) en lugar de la fórmula cátedra (90% × 31,5% × neto = 1.701.000... acá USD 6k Caso I; análogo en este Caso II).
**Error típico 3**: olvidar que IVA-RS es outflow inmediato aunque se recupere mes siguiente.
**Error típico 4**: cargar IIBB sobre FinTech Uruguay (no aplica — presta desde Montevideo, sin actividad en AR).

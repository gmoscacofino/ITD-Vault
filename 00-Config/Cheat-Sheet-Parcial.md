# Cheat-Sheet — Parcial ITD

> Una sola página. Lo que SÍ o SÍ tenés que recordar. Si algo no está acá, está en las notas largas.

---

## Grilla universal — encuadre de CUALQUIER caso

Antes de calcular, **siempre** identificar los 4 elementos del Hecho Imponible. Si falta uno, no hay impuesto.

| Elemento | Pregunta clave |
|---|---|
| **Objeto** | ¿Qué operación está alcanzada? |
| **Sujeto** | ¿Quién es el contribuyente? ¿PH o PJ? |
| **Espacio** | ¿Argentina (fuente AR) o exterior (fuente extranjera)? |
| **Tiempo** | ¿Devengado (PJ) o percibido (PH 2da y 4ta)? |

---

## Tasas vigentes (memorizar)

| Impuesto | Tasa |
|---|---|
| **Ganancias - Sociedad** | Escalonada **25% / 30% / 35%** según ingreso |
| **Ganancias - Socio** (sobre dividendos) | **7%** retención |
| **Ganancias - Juegos azar / gaming digital** | **41,5%** |
| **IVA - General** | **21%** |
| **IVA - Reducida** (carne, computadoras, vivienda única, agro) | **10,5%** |
| **IVA - Incrementada** (servicios públicos a RI) | **27%** |
| **IIBB** | **5%** servicios / **3-3,5%** comercio (varía jurisdicción) |
| **IDyCB** | **0,6%** débito + **0,6%** crédito = **1,2%** |

---

## Art. 93 LIG — Beneficiarios del Exterior (las que vienen seguro)

| Concepto | % renta presumida | Tasa efectiva |
|---|---|---|
| Servicios técnicos **CON asesoramiento** (Art. 93.a) | 60% | **21%** |
| Servicios técnicos **SIN asesoramiento** (Art. 93.h residual 90%) | 90% | **31,5%** |
| Cesión de derechos / marcas (Art. 93.a) | 80% | **28%** |
| Derechos de autor (obra inscripta) | 35% | **12,25%** |
| Intereses con **vinculadas del exterior** | 100% | **35%** |
| Locación de cosas muebles (leasing) | 40% | **14%** |
| Alquileres inmuebles | 60% | **21%** |
| Venta de bienes en AR por no residentes | 50% | **17,5%** |
| Imagen/sonido (cable, video) | 50% | **17,5%** |
| Agencias internacionales de noticias | 10% | **3,5%** |

---

## Fórmulas críticas

### Gross-up (cuando el AR asume el impuesto del exterior)
```
Bruto = Neto / (1 - tasa efectiva)
```
Ejemplo: USD 175.000 netos al 31,5% → 175.000 / 0,685 = **USD 255.474,45 brutos**.

### Precio "todo incluido" → gross-down del IVA
```
Neto gravado = Precio total / 1,21
IVA incluido = Precio total - Neto gravado
```
==Cuando el precio es "por todo concepto" e IVA aplica, el ingreso neto es MENOR al precio. No hacer el gross-down sobreestima el ingreso en un 21%.==

### Exportación parcial — distribución de uso
```
% uso en jurisdicción X = Ventas en X / Ventas totales en todas las jurisdicciones
```
La proporción de IVA (0% vs 21%), IIBB (exento vs gravado) y fuente (AR vs extranjera) se aplican sobre esos porcentajes.

### Rentabilidad sobre costos (criterio de aceptación)
```
Rentabilidad = Resultado neto / Costos totales
```
==Si la consigna pide "mínimo X% sobre costos", el denominador son los COSTOS, no el ingreso. Errores típicos: dividir por ingreso o no verificar el umbral.==

### IDyCB — Régimen Resto
```
IDyCB total = movimientos bancarios × 0,6%
  → 2/3 = pérdida (costo P&L)
  → 1/3 = crédito a cuenta de Ganancias
```
El IDyCB se calcula sobre TODOS los movimientos bancarios reales, incluyendo pagos de IVA a AFIP, aunque el IVA sea neutro en el P&L.

### Tax credit — límite
```
Tax credit aplicable = min(retención del exterior, alícuota AR × renta de fuente extranjera)
```
**Solo aplica sobre renta de fuente EXTRANJERA**. Si trabajaste desde AR (home office) y te retuvo el exterior → la retención es **costo**, no crédito.

### IIBB sobre base imponible
```
Base = Ventas - IVA - reintegros de gastos - reintegros de capital (préstamos) - venta de bienes de uso
```
==El IVA NO integra la base (calculo sobre 100, no sobre 121).==

---

## Reglas críticas por impuesto

### Ganancias

- **Teoría de la fuente (PH)**: requiere periodicidad + permanencia + habilitación, **las 3 juntas**.
- **Teoría del balance (PJ)**: todo ingreso de negocio real está gravado. Incluye condonación de pasivos, diferencias de cambio, indemnizaciones.
- **Art. 24 — vinculadas del exterior**: si paga ANTES del vto DDJJ → deduce devengado. Si paga DESPUÉS → deduce en año de pago. **Solo aplica si la renta es fuente AR para el acreedor**.
- **Reorganización libre Art. 77/80**: control ≥ **80% durante 2 años previos** (para trasladar quebrantos) + actividad mantenida 2 años después + actividades vinculadas en 12 meses previos + cese ≤ 18 meses.
- **Salidas no documentadas**: 35% adicional sobre el gasto + gasto NO deducible. El IVA nunca es costo.
- **Diferencias de cambio**: ==**Art. 164 DR**: NO se admite diferencia de cambio por transformar deuda a otra moneda, salvo al pago o novación==.

### IVA

- **Responsable sustituto (Art. 4.h)**: si proveedor del exterior presta servicio EN AR, el RI ingresa el IVA en su nombre. Es **neutro económicamente** (CF mes siguiente).
- **Empresa constructora**: el requisito es **propósito de lucro con la ejecución o venta**, NO el objeto social. Tasa 10,5% si es vivienda única.
- **Ajuste CF inmueble (Art. 11 DR)**: si vendés/desafectás **dentro de los 10 años** desde finalización de obra, hay que devolver el CF computado.
- **Cesión definitiva de marca**: ==NO gravada==. Cesión temporal: gravada (zona gris).
- **Exportación de servicios**: gravada a tasa **0%** (NO exenta). Permite recuperar CF.
- **Servicios digitales B2C** (cliente AR consumidor final): aplica criterio de **utilización económica** (no lugar de prestación).
- **Diferencias de cambio**: gravadas por **teoría de la unicidad** (siguen lo accesorio a lo principal).

### IIBB

- **Sociedad → siempre alcanzada**, aunque sea de profesionales universitarios. La exención de profesiones liberales es solo para profesional individual no organizado en empresa.
- **Habitualidad** se presume siempre para sociedades. **Onerosidad NO lucratividad**: se paga aunque pierda.
- **Bien de uso**: la categoría al momento de la **venta** determina si aplica la exclusión. Si desafectaste antes (a "Otros Bienes"), paga IIBB.
- **Convenio Multilateral**: requiere gastos E ingresos en más de una jurisdicción. No alcanza con tener clientes en otras provincias.
- **Régimen Especial 20/80** (profesiones liberales / intermediarios): 20% oficina, 80% donde se presta. **Solo para individuos**.
- **Régimen Especial 10/90** (construcción): 10% oficina, 90% obra.
- **Exportación de servicios exenta**: el servicio debe **efectivizarse en el exterior**, no basta cliente del exterior.

### IDyCB

- **Cómputo**: Microempresas 30% contra patronales (70% costo) · Pequeñas MiPyME 100% contra Ganancias · Resto 33% contra Ganancias (⅔ costo + ⅓ crédito).

---

## Errores típicos que aparecen en parciales

1. ==Aplicar 35% pleno en vez de tasa efectiva del Art. 93== (90% × 35% = 31,5%, etc.).
2. ==Olvidar el gross-up cuando el AR asume el impuesto.==
3. ==Confundir fuente AR vs fuente extranjera en home office==. Home office = fuente AR = NO hay tax credit.
4. ==No hacer gross-down cuando el precio es "todo incluido" y aplica IVA==. Precio / 1,21 ≠ Precio.
5. ==Asumir que cesión temporal de marca es como cesión definitiva== (la temporal está gravada, la definitiva no).
6. ==Olvidar IDyCB== en cálculos integrales (es chico pero está siempre).
7. ==Incluir el IVA sustituto (recuperable) como costo en el P&L==. No lo es, pero SÍ es necesidad financiera.
8. ==Pensar que exportación de servicios está "exenta" de IVA==. NO: tasa 0% (distinto: permite computar CF).
9. ==Aplicar Régimen Especial 20/80 a una sociedad==. NO: solo individuos.
10. ==No verificar el período del Art. 24== en pagos a vinculadas del exterior.
11. ==Olvidar la teoría de la unicidad== cuando hay intereses asociados a una venta principal.
12. ==Asumir que el bien de uso siempre está fuera de IIBB==. Si lo desafectaste antes de venderlo, no.
13. ==Calcular rentabilidad sobre el ingreso en vez de sobre los costos==. El denominador es costos totales.

---

## Pirámide jurídica (cuando hay conflicto entre normas)

```
1. Constitución Nacional
2. Tratados internacionales (CDI - convenios doble imposición)
3. Leyes especiales (ej. Régimen Incentivo RIGI)
4. Leyes generales (LIG, Ley IVA, etc.)
5. Decretos Reglamentarios
6. Resoluciones AFIP
```

Si el DR contradice a la Ley → prevalece la Ley. Si la Resolución contradice al DR → prevalece el DR.

---

## Conceptos a tener en la lengua

- **Tax credit**: requiere impuesto análogo + abonado + sobre renta de fuente extranjera.
- **Gross-up**: calcular el bruto del cual descontando la retención queda el neto pactado.
- **Devengado vs percibido**: PJ devengado, PH 2da/4ta percibido, PH 1ra/3ra devengado.
- **Renta mundial vs territorialidad**: residente AR tributa por renta mundial; no residente solo por fuente AR.
- **Manifestaciones de riqueza**: renta, patrimonio, consumo.

---

## Notas relacionadas (para profundizar)

- [[Hecho Imponible (4 elementos)]]
- [[Tax Credit]]
- [[Gross-up]]
- [[Teoria de la Fuente vs Balance]]
- [[Renta Mundial vs Territorialidad]]
- [[Fallo Angulo - Teoria Unicidad]]
- [[Fallo Red Hotelera]]
- [[Fallo Cia Tucumana]]

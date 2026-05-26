# Material 10 — Caso I: Software de facturación para Cadbury UK (Argentina y Uruguay)

> Impuestos: [[IVA - Exportaciones]], [[IIBB - Exenciones y No Alcanzados]], [[IDyCB]], [[Ganancias - Fuente]]
> Status: ✅ Validado en clase

---

## Enunciado

CFO de empresa argentina de desarrollo de software a medida. Cadbury UK solicita el desarrollo de un software de facturación que será utilizado por Cadbury ARG (ventas USD 4M/año) y Cadbury UY (ventas USD 1M/año).

Propuesta: USD 500.000 por todo concepto, factura a Cadbury UK, sin retención de UK. Posibilidad de trabajar en oficinas de UK. Costo: USD 350.000 en sueldos. Si trabajan en UK: costo adicional USD 10.000/mes × 5 meses = USD 50.000.

Tasas: Ganancias 30%, IVA 21%, IIBB 5%, Débitos 0,6%, Créditos 0,6%.

1. ¿Aceptaría el trabajo?
2. ¿Desde Argentina o desde UK?
3. ¿Conviene especificar el porcentaje de uso en el contrato?
4. ¿Qué porcentajes incluir?

---

## Conceptos involucrados

- [[IVA - Exportaciones]] — exportación parcial: porción AR gravada 21%, porción UY tasa 0%
- [[IVA - Objeto]] — servicio prestado en el exterior: fuera del objeto IVA argentino
- [[IIBB - Exenciones y No Alcanzados]] — exportación de servicios al exterior: exenta
- [[IDyCB]] — sobre débitos y créditos bancarios
- [[Ganancias - Fuente]] — fuente extranjera al prestar desde UK

---

## Resolución

### Pregunta 1: ¿Aceptaría el trabajo?

**SÍ, en ambas opciones hay utilidad.** Ver comparación en Pregunta 2.

---

### Pregunta 2: ¿Desde Argentina o desde UK?

**Desde Argentina:**

El software se usa 80% en AR (4M/5M) y 20% en UY → exportación parcial:

| Porción | Uso | IVA |
|---|---|---|
| 80% = USD 400.000 | Cadbury ARG (en AR) | 21% — utilización económica en AR |
| 20% = USD 100.000 | Cadbury UY (en UY) | 0% — exportación de servicios |

Precio "todo concepto" → IVA incluido en la porción AR:
- Porción AR: 400.000 / 1,21 = USD 330.579 neto + USD 69.421 IVA
- Porción UY: USD 100.000 (tasa 0%)
- **Ingreso neto IVA = USD 430.579**

IIBB: porción AR gravada al 5% → 330.579 × 5% = USD 16.529

IDyCB: (cobro 500K × 0,6%) + (pago sueldos 350K × 0,6%) = 3.000 + 2.100 = **USD 5.100**

| Concepto | Monto |
|---|---|
| Ingreso neto IVA | 430.579 |
| (−) Sueldos | (350.000) |
| (−) IIBB | (16.529) |
| (−) IDyCB | (5.100) |
| Resultado antes Ganancias | 58.950 |
| Ganancias (30%) | (17.685) |
| **Resultado neto desde AR** | **41.265** |

---

**Desde UK:**

Servicio prestado en el exterior → fuera del objeto del IVA argentino. Prestación efectivizada en el exterior → exenta de IIBB.

IDyCB: (cobro 500K × 0,6%) + (pago 400K × 0,6%) = 3.000 + 2.400 = **USD 5.400**

| Concepto | Monto |
|---|---|
| Ingreso neto (sin IVA) | 500.000 |
| (−) Sueldos | (350.000) |
| (−) Alojamiento + comida | (50.000) |
| (−) IDyCB | (5.400) |
| Resultado antes Ganancias | 94.600 |
| Ganancias (30%) | (28.380) |
| **Resultado neto desde UK** | **66.220** |

---

**Comparación:**

| | Desde Argentina | Desde UK |
|---|---|---|
| Ingreso neto IVA | 430.579 | 500.000 |
| IVA a ingresar | 69.421 | 0 |
| IIBB | 16.529 | 0 |
| Costo operativo total | 350.000 | 400.000 |
| Resultado antes Ganancias | 58.950 | 94.600 |
| Ganancias (30%) | 17.685 | 28.380 |
| **Resultado neto** | **41.265** | **66.220** |

==**CONVIENE TRABAJAR DESDE UK**: USD 66.220 vs USD 41.265. El costo adicional de USD 50.000 queda más que compensado por el ahorro impositivo (~USD 86.000 en IVA + IIBB).==

> [!note] La clave es el objeto del IVA
> Trabajando desde Argentina, el 80% del ingreso está gravado con IVA (todo incluido → el prestador absorbe el IVA reduciendo su neto efectivo). Trabajando desde UK, el IVA argentino no aplica → el precio íntegro es ingreso.

---

### Pregunta 3: ¿Conviene especificar porcentajes en el contrato?

**SÍ**, especialmente si se trabaja desde Argentina.

Sin especificación: AFIP podría considerar que toda la utilización económica es en Argentina → toda la prestación gravada con IVA y IIBB → mayor costo impositivo y riesgo de contingencia.

Con especificación documentada: se distingue con claridad la porción de exportación (Uruguay) y la porción local (Argentina), con sustento jurídico ante cualquier fiscalización.

### Pregunta 4: ¿Qué porcentajes incluir?

| Jurisdicción | Entidad | Ventas anuales | % |
|---|---|---|---|
| Argentina | Cadbury ARG | USD 4.000.000 | **80%** |
| Uruguay | Cadbury UY | USD 1.000.000 | **20%** |

==Incluir en el contrato: 80% del software se utilizará en Argentina y 20% en Uruguay. El ratio de ventas es la métrica más objetiva y defensible ante AFIP.==

> [!warning] Riesgo de sobreestimar la porción uruguaya
> Se podría intentar asignar más porcentaje a Uruguay para reducir IVA/IIBB, pero debe ser razonable y justificable. AFIP puede impugnar un porcentaje que no guarde relación con la actividad económica real de cada entidad.

---

## Por qué este ejercicio

Caso integral que combina:
1. **Exportación parcial en IVA**: el mismo servicio puede ser tasa 0% en una porción y 21% en otra según dónde se utilice económicamente.
2. **Decisión de localización**: prestar desde el exterior puede salir más barato en términos netos incluso con costos adicionales.
3. **Documentación contractual**: especificar porcentajes de uso es una herramienta de planificación fiscal defensiva.

==Error típico==: asumir que porque el cliente facturado es Cadbury UK (no residente), toda la operación es exportación de servicios. Lo que importa es dónde se **usa** el resultado del servicio, no quién paga.

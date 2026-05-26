# Ganancias — Gastos Deducibles

> Regla general de qué gastos se pueden deducir en Ganancias y qué no.

---

## TL;DR

**Regla general** (Art. 80 LIG): son deducibles los **gastos necesarios para obtener, mantener y conservar las ganancias gravadas**.

Esto implica 3 condiciones:
1. **Vinculados** con la generación de renta gravada.
2. **Documentados** correctamente.
3. **Devengados** (criterio temporal).

---

## Material de origen

- **Material de Lectura #2 y #3** — Gastos Deducibles
- **Notas de clase**: 2026-04-10
- **Art. 80 LIG (regla general)**, **Art. 88 LIG (limitaciones)**

---

## Regla general — Art. 80 LIG

Son deducibles los **gastos necesarios para obtener, mantener y conservar las ganancias gravadas**.

> Conceptualmente: si el gasto contribuye a generar ingresos que tributan, el gasto va contra esos ingresos.

### Condiciones acumulativas

| Condición | Significado |
|---|---|
| **Necesario** | Vinculado con la generación de la renta gravada |
| **Devengado** | Imputado al período correcto (regla general, excepto Art. 24) |
| **Documentado** | Respaldado con factura válida del proveedor |
| **Razonable en monto** | El precio debe ser de mercado (sino, posible dividendo ficto) |
| **Genuino** | La operación debe ser real (sino, salida no documentada por apócrifa) |

---

## Tipos de gasto deducibles

### Gastos vinculados directamente al negocio

- Costo de ventas (CMV)
- Sueldos y cargas sociales del personal afectado al negocio
- Alquileres de inmuebles afectados a la actividad
- Servicios públicos del local
- Insumos, suministros
- Honorarios profesionales (contador, abogado, consultores)
- Publicidad y marketing
- Mantenimiento de equipos y bienes de uso

### Gastos indirectos

- Sueldos de gerentes, administrativos
- Servicios generales
- Gastos de oficina
- Logística

### Amortizaciones

- Bienes de uso: amortización lineal sobre la vida útil
- Inmuebles: típicamente 50 años (2% anual)
- Equipos industriales: 10 años (10% anual)
- Vehículos: 5 años (20% anual)
- Computadoras: 3 años (33% anual)

### Intereses

- Intereses por préstamos comerciales: deducibles si los préstamos son para la actividad gravada.
- Intereses por préstamos a vinculadas del exterior: aplica Art. 24 (deducción al pago).
- Intereses sobre saldos a favor del fisco: NO deducibles.

#### Límite del Art. 85 inc. a — Intereses con vinculadas

==**Las deducciones de intereses por deuda financiera con compañías vinculadas** (locales o del exterior) tienen un tope: **30% del EBITDA**== del ejercicio.

##### Cálculo del EBITDA

```
Resultado del ejercicio
+ Amortizaciones (las que se restaron arriba)
+ Intereses (todos)
+ Impuesto a las Ganancias
= EBITDA
```

##### Aplicación

```
Intereses con vinculadas deducibles = min(intereses pagados, 30% × EBITDA)
```

==El **excedente NO se pierde**: se puede trasladar a ejercicios siguientes== (típicamente 5 años) para deducir cuando la empresa tenga "espacio" en el tope del 30%.

##### Ejemplo

```
Ingresos por ventas:                    10.000.000
Costo de servicios:                    (7.600.000)
Resultado bruto:                        2.400.000

Gastos administración:                   (120.000)
  ├ De los cuales amortizaciones:          40.000
Gastos comercialización:                 (280.000)
  ├ De los cuales amortizaciones:          80.000
Intereses bancarios (no vinculadas):  (1.000.000)
Intereses con vinculadas:                (650.000) ← bajo Art. 85.a
Resultado del ejercicio:                  350.000

EBITDA = Resultado + Amortizaciones + Intereses
EBITDA = 350.000 + (40.000 + 80.000) + (1.000.000 + 650.000) = 2.120.000

Límite 30% EBITDA = 636.000

Intereses con vinculadas pagados: 650.000
Intereses deducibles:             636.000 (al límite)
Excedente que pasa a años siguientes: 14.000
```

> El excedente no se pierde, pero queda "trabado" hasta que haya margen de deducción futuro.

### Pérdidas

- Pérdidas por incobrables (con criterios estrictos)
- Pérdidas por siniestros (no cubiertos por seguro)
- Quebrantos de ejercicios anteriores (ver [[Ganancias - Quebrantos]])

---

## Gastos NO deducibles — Art. 88 LIG

### Gastos personales o de subsistencia del contribuyente o su familia
- Comidas personales (no en concepto de "viáticos")
- Vestimenta no específica del trabajo
- Gastos del hogar
- Educación de hijos

### Gastos sin documentación
- Salidas no documentadas (Art. 40) — ver [[Ganancias - Salidas No Documentadas]]

### Gastos en relación con renta no gravada/exenta
- Si un gasto está vinculado con una renta exenta, NO es deducible.
- En la práctica, hay reglas de **proporcionalidad** cuando hay rentas mixtas.

#### Prorrateo de gastos mixtos

==Cuando un gasto está asociado **simultáneamente a rentas gravadas y no gravadas/exentas**, hay dos métodos==:

**1. Asignación directa** (preferido)
Si se puede determinar qué parte del gasto corresponde a cada tipo de renta, se asigna directamente y se deduce solo la parte vinculada a renta gravada.

**2. Prorrateo sobre la base de ingresos**
Si no se puede hacer asignación directa, se prorratea según la proporción de ingresos gravados/no gravados.

##### Ejemplo numérico

```
Ingresos del ejercicio:
  Gravados:    $800.000  (80,65% del total)
  No gravados: $192.000  (19,35% del total)
  Total:       $992.000

Gastos comunes (no asignables directamente):
  Sueldo del cadete:      $50.000
  Sueldo de la secretaria: $150.000
  Total mixto:            $200.000

Prorrateo:
  Deducible (80,65%):
    Cadete:    50.000 × 80,65% = 40.325
    Secretaria: 150.000 × 80,65% = 120.975
    Total:                      161.300

  NO deducible (19,35%):
    Cadete:    50.000 × 19,35% = 9.675
    Secretaria: 150.000 × 19,35% = 29.025
    Total:                       38.700
```

> ==**Solo se deduce la parte proporcional vinculada a renta gravada**==. Si no se hace el prorrateo, AFIP impugna el total como no deducible.

### Bienes situados en el exterior con relación con renta de fuente extranjera
- Hay reglas específicas.

### Sumas otorgadas a accionistas / socios
- Si la "remuneración" en realidad es distribución de utilidades disfrazada → dividendo ficto.

### Sanciones e intereses fiscales
- Multas administrativas: NO deducibles.
- Intereses resarcitorios y punitorios del fisco: NO deducibles.

### Donaciones (con limitaciones)
- Donaciones a instituciones reconocidas son deducibles **hasta 5% del resultado fiscal**.
- Donaciones a otras entidades: NO deducibles.

### Honorarios de directores (con tope)
- Limitados al **mayor entre**: 25% de la utilidad o $12.500 por director (cifras a actualizar).
- El exceso NO es deducible para la sociedad.

---

## Casos especiales

### Diferencias de cambio

| Caso | Deducción |
|---|---|
| Operación en moneda extranjera (compra a proveedor en USD) | Diferencia de cambio = gasto/ganancia deducible (devengado) |
| Préstamo a vinculada del exterior | Diferencia de cambio = aplica Art. 24 (al pago) |

### Provisiones

- **Provisión para incobrables**: deducible con criterios estrictos (historial, intentos de cobro, antigüedad).
- **Provisión para juicios**: NO deducible hasta que el juicio se cierre (no se considera devengado).

### Gastos relacionados con bienes de uso
- Adquisición: NO es gasto, se activa y amortiza.
- Mantenimiento: gasto deducible.
- Mejora: se activa al bien (no es gasto inmediato).

### Reorganización empresarial
Bajo el régimen del Art. 77, hay tratamientos especiales que permiten preservar atributos fiscales (quebrantos, amortizaciones) sin gravar la reorganización.

> Ver [[Ganancias - Reorganizacion Libre de Impuestos]].

---

## Implicancias para decisiones empresariales

### Identificar gastos no deducidos

Muchas empresas no deducen gastos que efectivamente podrían:
- Servicios profesionales recibidos sin factura formal (corregible).
- Amortizaciones no calculadas correctamente.
- Costos de viajes y representaciones bien documentados.

> Una de las "5 herramientas" de optimización es **maximizar el reconocimiento de gastos** legítimos.

### Documentación adecuada

Cada gasto debe tener:
- Factura del proveedor (no consumidor final si es operación B2B).
- Vinculación con la actividad (visible en el objeto, en el destinatario, en la causa).
- Pago documentado (transferencia, cheque, etc. — el efectivo es alta señal).

### Separar patrimonio personal de patrimonio empresarial

No mezclar gastos personales con la empresa. Genera riesgos de:
- Salida no documentada.
- Dividendo ficto.
- Litigios fiscales.

---

## Errores comunes

### Error 1 — Deducir gastos sin documentación
Aunque conceptualmente sean gastos del negocio, sin factura no son deducibles + posibles 35% adicional. Ver [[Ganancias - Salidas No Documentadas]].

### Error 2 — Deducir gastos en relación a renta exenta
Si tenés ingresos no gravados (ej. dividendos recibidos exentos), los gastos asociados no son deducibles. Hay regla de proporcionalidad.

### Error 3 — Asumir que toda compra de bien es gasto
Bienes de uso (con vida útil > 1 año) NO son gasto al comprarlos, sino que se amortizan. Tratarlos como gasto inmediato es error.

### Error 4 — Confundir mantenimiento con mejora
- Mantenimiento (mantiene la vida útil): gasto.
- Mejora (extiende vida útil o capacidad): se activa al bien, no es gasto.

### Error 5 — No identificar honorarios de directores como gasto deducible
Hay tope, pero hasta ese tope son deducibles. Muchas empresas no usan el tope o no documentan adecuadamente.

---

## Conceptos relacionados

- [[Ganancias - Concepto y Optimizacion]] — los gastos son palanca de optimización
- [[Ganancias - Salidas No Documentadas]] — qué pasa si no hay factura
- [[Ganancias - Dividendo Ficto y Disposicion de Fondos]] — gastos del socio que no son deducibles
- [[Ganancias - Criterios de Imputacion]] — cuándo se imputan los gastos
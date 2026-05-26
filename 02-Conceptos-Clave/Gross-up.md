# Gross-up

> Cálculo del monto bruto que hay que pagar para que, después de la retención, el beneficiario reciba un monto neto pactado.

---

## TL;DR

Cuando un contrato dice "el proveedor recibe **netos** X" → la empresa debe calcular cuánto pagar **bruto** para que la retención no afecte el monto neto.

**Fórmula**: `Bruto = Neto / (1 − tasa efectiva)`

Aparece típicamente en pagos a beneficiarios del exterior cuando el contrato fija un neto.

---

## Material de origen

- **Material de Lectura #2** — Beneficiarios del Exterior
- **Notas de clase**: 2026-03-13
- **Caso clave**: Material 7 Caso 1 — Empresa UK servicios técnicos

---

## El problema

Una empresa argentina contrata un proveedor del exterior. Acuerdan **USD 175.000 netos** (es decir: 175.000 después de impuestos que retenga AR).

La tasa de retención por Art. 93 inc. h (servicios técnicos sin asesoramiento) es **31,5%**.

**Pregunta**: ¿cuánto bruto debe pagar la empresa argentina para que, después de la retención, queden USD 175.000 al proveedor?

### Aproximación INCORRECTA

```
Bruto = 175.000 + (31,5% × 175.000) = 175.000 + 55.125 = 230.125 ❌
```

Si pagás 230.125 y retenés 31,5% de ese monto → retenés 72.490 → quedan 157.635 (no 175.000). **No alcanza**.

### Aproximación CORRECTA

```
Bruto = Neto / (1 − tasa)
Bruto = 175.000 / (1 − 0,315)
Bruto = 175.000 / 0,685
Bruto = USD 255.474,45 ✓
```

Verificación:
```
Bruto: 255.474,45
Retención (31,5%): 80.474,45
Neto: 175.000 ✓
```

---

## La lógica matemática

### Por qué la división

Pagamos un monto bruto $B$. Retenemos sobre el bruto a tasa $t$.

```
Neto = Bruto - Retención
Neto = B - (B × t)
Neto = B × (1 - t)
B = Neto / (1 - t)
```

### Por qué NO funciona sumar la retención al neto

Si simplemente sumamos $N × t$ al neto:
```
Bruto = N + (N × t) = N × (1 + t)
```

Pero la retención se aplica sobre el bruto, no sobre el neto. Entonces:
```
Retención real = Bruto × t = N × (1 + t) × t = N × t + N × t²
```

Esto retiene MÁS de lo que sumamos. El neto resultante es menos que N.

---

## Fórmula general

```
Bruto = Neto / (1 − tasa efectiva)
```

### Tabla de gross-up para tasas comunes (Art. 93)

| Tasa efectiva | Factor multiplicador del neto | Ejemplo: neto = $100 |
|---|---|---|
| 12,425% (intereses) | 1 / (1 - 0,12425) ≈ 1,1419 | Bruto = $114,19 |
| 14% (alquiler muebles) | 1 / 0,86 ≈ 1,1628 | Bruto = $116,28 |
| 17,5% (películas) | 1 / 0,825 ≈ 1,2121 | Bruto = $121,21 |
| 21% (regalías) | 1 / 0,79 ≈ 1,2658 | Bruto = $126,58 |
| 24,5% (sueldos) | 1 / 0,755 ≈ 1,3245 | Bruto = $132,45 |
| 31,5% (servicios técnicos) | 1 / 0,685 ≈ 1,4599 | Bruto = $145,99 |
| 35% (intereses 100%) | 1 / 0,65 ≈ 1,5385 | Bruto = $153,85 |

---

## Aplicación con IVA en paralelo

Cuando además del gross-up de Ganancias hay IVA por responsable sustituto (importación de servicios), el cálculo se hace en paralelo, no encadenado:

```
Bruto Ganancias = Neto / (1 - tasa GAN) — ya calculado
IVA = Bruto × 21% (calculado sobre el monto bruto antes de retener)
```

> **Atención**: el IVA NO entra en el gross-up. Es un cálculo independiente.

### Ejemplo completo — empresa UK (Caso 1)

**Datos**:
- Neto pactado al proveedor UK: USD 175.000
- Retención Ganancias (Art. 93 inc. h): 31,5%
- IVA importación de servicios: 21%

**Cálculo**:

```
Bruto Ganancias = 175.000 / (1 - 0,315) = 255.474,45

Retención GAN = 255.474,45 × 0,315 = 80.474,45
Neto al proveedor = 175.000 ✓

IVA (calculado sobre el bruto): 255.474,45 × 0,21 = 53.649,63
  (este IVA es responsable sustituto: lo paga la AR, pero al mes siguiente
   lo computa como crédito fiscal → neutro económicamente)
```

**Costo total para la empresa AR**:
- Sin contar IVA: 255.474,45 (paga 175.000 al proveedor + 80.474,45 a AFIP).
- IVA es neutro económicamente (lo paga pero lo recupera).

---

## Cuándo NO aplica gross-up

### Cuando el contrato pacta un BRUTO

Si el contrato dice "el proveedor cobra USD 200.000 brutos" → NO hay gross-up. Se aplica la retención directamente sobre el bruto:

```
Bruto pactado: 200.000
Retención (31,5%): 63.000
Neto al proveedor: 137.000
```

### Cuando no hay retención

Si la operación no tiene retención (ej. importación de bienes), no hay gross-up.

---

## Errores comunes

### Error 1 — Sumar la retención al neto
El error más típico. La retención NO se suma al neto, hay que **dividir** por (1 - tasa).

### Error 2 — Confundir gross-up de Ganancias con gross-up de IVA
El IVA se calcula sobre el bruto resultante del gross-up de Ganancias. NO se debe hacer un gross-up de IVA encima del de Ganancias.

### Error 3 — Aplicar gross-up cuando el contrato pacta bruto
Si el cliente está acostumbrado a contratos en "brutos", aplicar gross-up duplica el costo. Hay que **leer bien el contrato**.

### Error 4 — Olvidar verificar
Siempre verificar: bruto calculado × (1 - tasa) = neto pactado.

### Error 5 — Usar tasas mal
La tasa que se usa es la **efectiva** del Art. 93 (que incluye la presunción de ganancia neta), NO el 35% nominal. Para servicios técnicos sin asesoramiento es 31,5%, no 35%.

---

## Implicancia para decisiones de negocio

### Costos efectivos de contratación al exterior

El gross-up es un costo real que muchas empresas no consideran al negociar. Si vas a contratar un servicio con un proveedor extranjero por USD 100K netos, asumiendo que pagás retenciones, te va a costar realmente USD 145K (a tasa 31,5%).

> Esto es relevante al comparar proveedores locales vs extranjeros: el extranjero puede parecer más barato en bruto pero más caro después de gross-up.

### Negociación de contratos internacionales

Si tenés poder de negociación, conviene pactar **brutos** (no netos) para evitar absorber el costo de la retención. Es habitual que los proveedores extranjeros del primer mundo pacten netos (no saben/quieren saber de retenciones argentinas).

---

## Conceptos relacionados

- [[Ganancias - Beneficiarios del Exterior]] — donde aplica gross-up
- [[Ganancias - Fuentes Especificas]] — Art. 13 (asesoramiento)
- [[IVA - Importacion de Servicios]] — el IVA paralelo
- [[Tax Credit]] — la otra cara cuando AR es el que cobra
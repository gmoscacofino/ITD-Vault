# Ganancias — Venta y Reemplazo

> Mecanismo legal para diferir el pago de impuesto sobre la ganancia de venta de un bien de uso, cuando se reinvierte en otro bien de uso.

---

## TL;DR

- Permite **diferir** (no exonerar) el impuesto sobre la ganancia de venta de un bien de uso.
- La ganancia se aplica al **costo del bien nuevo**, que se amortiza sobre un costo reducido.
- **Plazo**: venta y reemplazo deben ocurrir dentro del mismo ejercicio fiscal o el inmediato (anterior/posterior). Para inmuebles con construcción: hasta 4 años.
- **NO aplica para bienes de cambio** (esos no se amortizan).

---

## Material de origen

- **Material de Lectura #3** — Venta y Reemplazo
- **Notas de clase**: 2026-04-10
- **Art. 71 LIG** y **Art. 72 LIG**

---

## El problema que resuelve

### Sin venta y reemplazo

Una empresa vende una máquina vieja por encima de su valor residual (ganancia) para comprar una nueva. **Sin esta figura**, tiene que pagar el impuesto sobre la ganancia de la venta hoy, lo que reduce el dinero disponible para comprar la nueva máquina.

```
Máquina vieja: valor residual $0 (totalmente amortizada)
Precio de venta: $100.000.000
Ganancia: $100.000.000
Impuesto (30%): $30.000.000
Dinero disponible para reinversión: $70.000.000

Si la máquina nueva cuesta $300.000.000 y financiás:
  $70.000.000 propio
  $230.000.000 préstamo
```

### Con venta y reemplazo

La ganancia de $100M no se grava de una vez. Se "guarda" para afectar al costo del bien nuevo, generando menor amortización a lo largo de los años.

```
Máquina nueva: $300.000.000
Ganancia diferida: $100.000.000
Costo fiscal del bien nuevo: $300.000.000 - $100.000.000 = $200.000.000
Amortización anual sobre $200M (menor que sobre $300M)
```

> El total de impuesto pagado a lo largo del tiempo es el mismo, pero **se difiere**. En contexto inflacionario y considerando el valor del dinero en el tiempo, esto es una **ventaja significativa**.

---

## Requisitos para aplicar venta y reemplazo

### Requisito 1: Tipo de bien
- Debe ser un **bien de uso** (que se amortiza)
- ==NO aplica a **bienes de cambio**== (esos no se amortizan, sino que son costo cuando se venden)

> Un bien de uso es aquel con vida útil mayor a 1 año, afectado a la actividad. Ejemplos: máquinas, vehículos, inmuebles afectados, computadoras.

### Requisito 2: Reemplazo
El bien vendido debe ser **reemplazado por otro bien de uso afectado a la misma actividad**.

### Requisito 3: Plazo
La venta y la compra del bien de reemplazo deben ocurrir:
- Dentro del **mismo ejercicio fiscal**, o
- Dentro del **ejercicio inmediato anterior o posterior** (plazo total ~1 año)
- Para **inmuebles con construcción**: hasta **4 años**

### Requisito 4: Comunicación al fisco
Se debe informar a AFIP el uso del beneficio (formulario específico).

---

## Mecánica del diferimiento

### Cálculo

```
Precio de venta del bien viejo:    $V
Valor residual del bien viejo:     $R
Ganancia de venta:                 $G = V - R

Costo del bien nuevo:              $N
Costo fiscal ajustado:             $N - $G

Amortización anual:                $N - $G / vida útil
```

### Comparación

| Concepto | Sin V&R | Con V&R |
|---|---|---|
| Ganancia gravada en año 1 | $G | $0 |
| Impuesto en año 1 | $G × 30% | $0 |
| Costo amortizable | $N | $N - $G |
| Amortización anual | $N/n | ($N-$G)/n |
| Impuesto total a lo largo del tiempo | Mismo | Mismo |
| Timing | Concentrado al inicio | Diferido en n años |

---

## Caso aplicado del profesor

**Datos**:
- Máquina vieja totalmente amortizada (valor residual $0)
- Precio de venta: $100M
- Precio de máquina nueva: $300M
- Banco le presta: $200M
- Vida útil máquina nueva: 30 años

**Análisis sin V&R**:
- Ganancia: $100M
- Impuesto (30%): $30M
- Resultado del ejercicio (asumiendo otras operaciones neutras): pierde $30M de caja en impuestos.

**Análisis con V&R**:
- Ganancia diferida: $100M
- Costo fiscal de la máquina nueva: $300M - $100M = $200M
- Amortización anual: $200M / 30 = $6,67M/año
- En vez de pagar $30M de impuesto hoy, paga menos amortización (pierde escudo fiscal) por 30 años.

> Diferencia clave: el impuesto total es similar a largo plazo, pero **financieramente** la empresa retiene los $30M para invertir en la máquina nueva, reduciendo necesidad de préstamo.

---

## Por qué NO aplica a bienes de cambio

Los **bienes de cambio** (inventario, mercadería) NO se amortizan, sino que son costo cuando se venden.

Si un supermercado vende muebles de oficina como mercadería (ej. Tisera), esos muebles son bien de cambio para el supermercado. La venta de un mueble usado del propio supermercado en cambio sería bien de uso.

> La distinción es por la afectación, no por el tipo de bien en abstracto.

---

## Implicancias para decisiones empresariales

### Cuándo usar V&R

- Tenés un bien de uso muy amortizado o con ganancia alta de venta.
- Vas a comprar un bien de uso para reemplazo.
- Necesitás liquidez (preferís el diferimiento al pago inmediato).

### Cuándo NO usar V&R

- Estás en quebranto (no tenés impuesto a diferir, no hay ventaja).
- El bien nuevo tiene vida útil corta (poco escudo fiscal futuro).
- Vas a vender el bien nuevo pronto (perdés el diferimiento al venderlo).

### Casos clásicos
- Empresas en expansión que renuevan flota o maquinaria.
- Empresas inmobiliarias que cambian de oficinas.
- Empresas que mejoran instalaciones (edificio viejo por edificio nuevo).

---

## Errores comunes

### Error 1 — Aplicar a bienes de cambio
Los bienes de cambio NO se amortizan, no aplica V&R. Si una mercadería tiene utilidad, paga impuesto normal.

### Error 2 — Olvidar el plazo
Si no comprás el reemplazo dentro del plazo (1 año, 4 para inmuebles), pierdes el beneficio retroactivamente y pagás el impuesto.

### Error 3 — Asumir que es exoneración
NO es exoneración, es **diferimiento**. El impuesto total a lo largo del tiempo es prácticamente el mismo. Solo cambia el timing.

### Error 4 — No comunicar a AFIP
Si no notificás el uso del beneficio en tiempo y forma, perdés la opción.

### Error 5 — Vender el bien de reemplazo pronto
Si vendés el bien nuevo poco tiempo después, perdés el diferimiento porque ya no hay "reemplazo" sostenido en el tiempo. La AFIP puede reclamar el impuesto diferido.

---

## Conceptos relacionados

- [[Ganancias - Quebrantos]] — alternativa para diferir impuesto en años de pérdida
- [[Ganancias - Concepto y Optimizacion]] — V&R es una herramienta de optimización
- [[Ganancias - Sujetos]] — quién puede usar V&R
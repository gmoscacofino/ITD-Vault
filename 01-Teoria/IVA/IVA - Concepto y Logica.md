# IVA — Concepto y Lógica

> Marco general del Impuesto al Valor Agregado. Quién lo paga, cómo funciona la mecánica de DF/CF, y cuándo deja de ser neutro.

---

## TL;DR

- IVA grava el **consumo**. Lo paga el **consumidor final**, pero lo recaudan los empresarios (RI).
- Funciona por **diferencia**: Débito Fiscal (DF) − Crédito Fiscal (CF) = monto a ingresar al fisco.
- Para un RI con toda la cadena gravada, el IVA es **neutro económicamente**.
- Se vuelve **costo** cuando alguna etapa de la cadena no está gravada (rompe la neutralidad).
- Es **mensual** y se debe calcular sobre **devengado**.

---

## Material de origen

- **Material de Lectura #4** — Impuesto al Valor Agregado
- **Notas de clase**: 2026-04-17
- **Resumen Claude**: 2026-04-17 IVA
- **Notas de Lauti (txt)**: sección extensa sobre IVA

---

## Concepto general

### Qué grava
El IVA grava el **consumo**. Es un impuesto **indirecto**:
- Quien lo **liquida** (RI) NO es el mismo que quien lo **paga económicamente** (consumidor final).
- El RI funciona como **agente de recaudación** del fisco.

### Comparación con Ganancias

| Aspecto | Ganancias | IVA |
|---|---|---|
| Manifestación gravada | Renta | Consumo |
| Quién lo paga económicamente | Contribuyente (la empresa) | Consumidor final |
| Quién lo liquida | Contribuyente | Empresa (RI) |
| Tipo de impuesto | Directo | Indirecto |
| Frecuencia | Anual (con anticipos) | Mensual |

---

## Mecánica del IVA — Débito Fiscal y Crédito Fiscal

### Débito Fiscal (DF)
- Es el IVA contenido en las **VENTAS** del RI.
- El RI lo **cobra** al cliente.
- Debe **ingresarlo al fisco**.

### Crédito Fiscal (CF)
- Es el IVA contenido en las **COMPRAS** del RI.
- El RI lo **paga** a sus proveedores.
- Puede **computarlo contra el DF**.

### Cálculo mensual

```
DF (IVA cobrado en ventas)         $100
CF (IVA pagado en compras)         -$50
                                  ─────
A ingresar al fisco                $50

Si DF > CF → ingreso al fisco la diferencia
Si CF > DF → saldo a favor (técnico)
```

### Ejemplo simple

Una empresa vende $1.000 (+ $210 IVA) y compró por $600 (+ $126 IVA) en el mes:

| Concepto | Monto |
|---|---|
| Ventas | $1.000 |
| DF (21% sobre ventas) | $210 |
| Compras | $600 |
| CF (21% sobre compras) | $126 |
| A ingresar al fisco (DF - CF) | $84 |

> $84 es el 21% sobre el **valor agregado** ($1.000 − $600 = $400 → 21% × $400 = $84). De ahí el nombre "Impuesto al Valor Agregado".

---

## La neutralidad del IVA

### Cuándo es NEUTRO

El IVA es **neutro económicamente para el empresario** si:
- Toda la cadena de valor está gravada.
- El empresario es RI (puede computar CF).
- Las ventas y compras están sincronizadas (sin retraso de cobranza).

> En esa situación, el empresario **no soporta** el IVA. Lo cobra al cliente y lo paga al fisco (o lo recupera vía CF).

### Cuándo se vuelve COSTO

El IVA deja de ser neutro y se vuelve costo cuando:

1. **La etapa propia NO está gravada** (exenta o no alcanzada).
   - El empresario paga IVA en sus compras (CF) pero no cobra IVA en sus ventas (no hay DF).
   - El CF no se puede usar → es costo.

2. **El empresario NO es RI** (monotributista o consumidor final).
   - No puede computar CF.
   - Todo el IVA pagado en compras es costo.

3. **La cadena se "rompe" en alguna etapa**.
   - Si en el medio hay alguien exento, el IVA se acumula y encarece el producto.

### Ejemplo de pérdida de neutralidad

```
Etapa 1: Productor agrícola (vende a 100 + 10,5% IVA)
Etapa 2: Distribuidor EXENTO (vende a 150, sin IVA)
Etapa 3: Comerciante RI (vende a 250 + 21% IVA = 302,5)

El distribuidor exento NO puede recuperar el CF de la etapa 1.
Su costo real es 110,5 (no 100), porque el IVA es costo.
Esto encarece toda la cadena.
```

---

## Aspectos financieros: efecto en el flujo de caja

### El problema típico

El RI **emite la factura** y reconoce el DF inmediatamente (mes de la factura).
El RI **cobra al cliente** típicamente a 30/60/90 días.

Pero el RI debe ingresar el IVA del DF **el mes siguiente** al de la factura, aunque no haya cobrado.

```
Mes 1: Empresa factura $1.000 + $210 IVA. Cobra en mes 4.
Mes 2: Debe ingresar al fisco $210 (DF del mes 1) − CF del mes 1.
Mes 4: Cobra los $1.210 del cliente.

Problema: del mes 2 al mes 4, la empresa tiene plata "estacionada" en AFIP.
```

> ==El IVA es financieramente regresivo para empresas con plazos largos de cobranza==. Es costo de oportunidad significativo.

---

## La cuestión del precio

### Cómo definir el precio incluyendo IVA

```
Precio de costo:                  X
Costos directos:                  +Y
Costos indirectos:                +Z
Margen de utilidad:               +M
Precio NETO:                       N
+ IVA 21%:                        +N × 0,21
Precio FINAL:                      P = N × 1,21
```

> El empresario calcula su margen sobre el **neto**. El IVA es un "adicional" que se cobra al cliente.

### Mito común: "Pago mucho IVA"

Empresarios suelen quejarse de "pagar mucho IVA" en la DDJJ mensual. En realidad:
- No es un costo propio.
- Recaudaron ese dinero a nombre del fisco.
- Su único costo es el **financiero** (entre facturación y cobranza, mantienen el dinero como pasivo).

---

## Período fiscal: mensual

El IVA es un impuesto **mensual**. Cada mes se hace una DDJJ y se ingresa el saldo (si DF > CF).

> Se diferencia de Ganancias (anual) y de IIBB (anual pero pagado mensual con anticipos).

---

## Saldos a favor: técnico vs libre disponibilidad

### Saldo técnico
- Surge cuando en un mes el CF > DF.
- **Solo se puede aplicar contra DF futuro** del mismo impuesto.
- No se puede usar para pagar otros impuestos ni pedir devolución.

### Saldo de libre disponibilidad
- Surge de regímenes específicos (retenciones, percepciones).
- Se puede aplicar contra **otros impuestos** o pedir compensación.

> Ver [[IVA - Saldos a Favor]] para detalle.

---

## Tasas

| Tasa | Cuándo aplica |
|---|---|
| 21% | General (la mayoría de bienes y servicios) |
| 10,5% | Reducida: alimentos básicos, carne, productos agropecuarios, obra para vivienda única |
| 27% | Incrementada: servicios públicos (electricidad, gas, agua, etc.) |

> Ver [[IVA - Tasas]] para detalle.

---

## Errores comunes

### Error 1 — Asumir que el IVA es costo siempre
Para un RI con cadena gravada, el IVA es neutro económicamente. Solo es costo si rompe la neutralidad.

### Error 2 — Olvidar el efecto financiero
Aunque sea neutro, financieramente impacta porque hay retraso entre facturación e ingreso al fisco.

### Error 3 — Aplicar IVA a operaciones no gravadas
Una exportación, una operación financiera, ciertas operaciones específicas pueden no estar gravadas. Hay que chequear.

### Error 4 — Confundir saldos técnico y libre disponibilidad
El técnico es restrictivo. El de libre disponibilidad es flexible. No mezclarlos.

### Error 5 — Olvidar que el responsable sustituto cumple ambos roles
En importación de servicios, la empresa argentina es responsable sustituto del IVA: paga el IVA por el proveedor extranjero, pero al mes siguiente lo computa como CF (es neutro económicamente).

---

## Conceptos relacionados

- [[IVA - Objeto]] — qué está alcanzado
- [[IVA - Sujeto]] — quiénes son contribuyentes
- [[IVA - Nacimiento del Hecho Imponible]] — cuándo se devenga
- [[IVA - Saldos a Favor]] — técnico vs libre disponibilidad
- [[IVA - Tasas]] — 21%, 10,5%, 27%
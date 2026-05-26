# Material 11 — Caso II: Empresa de telefonía IP y exención de IVA

> Impuestos: [[IVA - Exenciones]], [[IVA - Concepto y Logica]], [[IVA - Importacion de Servicios]]
> Status: ✅ Validado por la cátedra

---

## Enunciado

CFO de empresa de telefonía IP (residente fiscal argentina). Estructura de costos directos del servicio mensual:

| Tipo de costo | Costo | IVA importación de servicios | IVA local |
|---|---|---|---|
| Proveedores del exterior | 50 | 10,50 | — |
| Proveedores locales | 50 | — | 10,50 |
| Sueldos | 600 | — | — |
| **Total costos directos** | **700** | | |

La empresa aplica **35% adicional** (costos indirectos + margen) sobre costos directos.

**Hasta junio 2022:** precio de venta = USD 945 + IVA 21% = **USD 1.143,45**.

**Julio 2023:** Ley exime de IVA a los servicios de telefonía IP → empresa **deja de ser RI en IVA**.

**Pregunta:** Manteniendo el 35% de markup, ¿el nuevo precio de venta debe ser USD 945? En caso negativo, calcule el precio correcto.

---

## Conceptos involucrados

- [[IVA - Exenciones]] — pérdida del CF cuando la actividad propia queda exenta
- [[IVA - Concepto y Logica]] — cuándo el IVA deja de ser neutro y se vuelve costo
- [[IVA - Importacion de Servicios]] — la obligación de responsable sustituto desaparece al dejar de ser RI

---

## Resolución

### Paso 1 — Lógica pre-exención (hasta junio 2022)

Siendo RI, el IVA era neutro en ambos casos:

```
Costos directos base:       700
Markup 35%:                 245
Precio neto:                945
IVA 21% (DF al consumidor): 198,45
Precio final:             1.143,45  ✓
```

### Paso 2 — Distinguir el mecanismo de cada IVA al quedar exenta

| Proveedor | Mecanismo siendo RI | Al dejar de ser RI | ¿Se vuelve costo? |
|---|---|---|---|
| **Exterior** | Empresa ingresa IVA a AFIP **aparte** del precio (responsable sustituto Art. 4 inc. h). Luego lo recupera como CF. | Sin condición de RI, **la obligación de responsable sustituto desaparece**. No lo ingresa ni lo recupera. | **NO. No es costo.** |
| **Locales** | Proveedor factura 50 + 10,50 IVA. Empresa recupera 10,50 como CF. | Proveedor sigue cobrando 50 + 10,50 (el IVA está dentro de su precio). Empresa ya no puede recuperarlo. | **SÍ. Es costo.** |

### Paso 3 — Nueva base de costos directos

| Concepto | Monto |
|---|---|
| Proveedores del exterior | 50 |
| Proveedores locales | 50 |
| Sueldos | 600 |
| IVA proveedores locales (ahora costo) | 10,50 |
| **Total nuevos costos directos** | **710,50** |

### Paso 4 — Nuevo precio de venta

```
710,50 × 1,35 = USD 959,175
IVA al consumidor = 0 (empresa exenta)
Nuevo precio final = USD 959,175
```

---

## Respuesta final

==**NO: el precio correcto no es USD 945, sino USD 959,175.**==

| Situación | Precio final | Composición |
|---|---|---|
| Antes (RI, hasta jun-2022) | USD 1.143,45 | 945 neto + 198,45 IVA |
| Respuesta incorrecta | USD 945,00 | "solo bajo el IVA" |
| ==**Correcto post-exención**== | ==**USD 959,175**== | 959,175 sin IVA |

**Ahorro real del consumidor:** 1.143,45 − 959,175 = USD 184,275 (no los 198,45 del IVA eliminado).

La diferencia (USD 14,175) es el IVA de locales que se traslada al precio (10,50 × 1,35).

---

## Por qué este ejercicio

1. ==La exención no es gratis==: al no cobrar IVA al cliente, se pierde el CF de las compras → sube el costo.
2. ==Distinguir los dos mecanismos de IVA==: el IVA del exterior lo pagaba la empresa como obligación propia al fisco (desaparece con la exención). El IVA local lo paga el proveedor dentro de su precio (sigue siendo costo).
3. ==El consumidor ahorra menos que el IVA eliminado==: parte del IVA "trabado" en la cadena se traslada al nuevo precio.

**Error típico 1:** decir que el precio es USD 945 (ignorar el IVA de locales como costo).
**Error típico 2:** sumar ambos IVA como costo (10,50 + 10,50 = 21) → precio 973,35. Incorrecto: el IVA del exterior deja de ingresarse al dejar de ser RI.

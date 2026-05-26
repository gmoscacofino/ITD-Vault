# IVA — Saldos a Favor (Técnico vs Libre Disponibilidad)

> Cuando el CF supera al DF, surge saldo a favor. Pero no todos los saldos tienen el mismo tratamiento.

---

## TL;DR

| Tipo de saldo | Origen | Uso permitido |
|---|---|---|
| **Técnico** | CF > DF (compras mayores a ventas) | Solo contra DF futuro del MISMO impuesto |
| **Libre disponibilidad** | Retenciones, percepciones, otros regímenes | Contra cualquier impuesto + devolución |

> El saldo técnico es el más común. Es restrictivo y suele ser un dolor de cabeza para empresas en expansión o con saldos cíclicos.

---

## Material de origen

- **Material de Lectura #4** — Saldos a Favor
- **Notas de clase**: 2026-04-17

---

## Saldo Técnico

### Cuándo surge

Cuando en un mes, el CF supera al DF:
```
CF (compras del mes):    $5.000
DF (ventas del mes):     $3.000
                        ─────
Saldo TÉCNICO a favor:   $2.000 (no se ingresa nada al fisco)
```

### Causas típicas

- **Empresa en expansión**: compra mucho stock, no alcanzó a venderlo.
- **Empresa con DF acotado**: como un exportador (cuyas ventas son a tasa 0).
- **Empresa con compras estacionales**: típica de empresas agrícolas.
- **Empresa con grandes inversiones**: compra bienes de uso costosos.

### Uso permitido

==Solo se puede aplicar contra el DF futuro del **mismo impuesto** (IVA)==.

NO se puede:
- Aplicar contra Ganancias.
- Aplicar contra otros impuestos (IIBB, etc.).
- Pedir devolución al fisco.
- Cederlo a otro contribuyente.

### Resultado

El saldo técnico queda "guardado" hasta que la empresa tenga DF suficiente para absorberlo. Si la empresa nunca genera DF (sigue exportando, sigue exenta, etc.), el saldo queda "trabado" indefinidamente.

---

## Saldo de Libre Disponibilidad

### Cuándo surge

Cuando la empresa ha pagado IVA por **regímenes específicos** (no por DF/CF normal):

1. **Retenciones** sufridas (el cliente le retuvo IVA por estar inscripta en un régimen).
2. **Percepciones** sufridas (la importación de bienes generó una percepción).
3. **Pagos a cuenta** específicos del IVA.

### Mecánica de las retenciones

#### Régimen de retención
- AFIP designa **agentes de retención** (típicamente grandes empresas, sectores específicos).
- Cuando el agente le paga a un proveedor, **retiene el 80% del IVA** y lo ingresa al fisco.
- Le paga al proveedor el monto + el 20% del IVA + un certificado de retención por el 80%.
- El proveedor usa el certificado en su DDJJ.

#### Cálculo

```
Factura: $1.000 + IVA 21% = $1.210

Sin retención (caso normal):
  Proveedor recibe $1.210.
  En DDJJ ingresa $210 al fisco.

Con retención del 80%:
  Proveedor recibe $1.000 + 20% del IVA = $1.000 + $42 = $1.042 + certificado por $168.
  En DDJJ:
    DF de la factura: $210
    Crédito por retención (cert): $168
    A ingresar: $42 (ya está en el bolsillo del proveedor).
```

### Régimen de percepción
- Adicional al precio de compra.
- El proveedor percibe IVA extra al cliente.
- El cliente puede luego computarlo como pago a cuenta.

### Uso permitido del saldo de libre disponibilidad

✅ Aplicar contra IVA propio futuro.
✅ Aplicar contra **otros impuestos** (Ganancias, IIBB, etc.) — compensación con AFIP.
✅ Pedir **devolución** al fisco (en algunos casos).
✅ Transferir a otros contribuyentes (mediante régimen específico).

> Mucho más flexible que el saldo técnico.

---

## Diferencias clave en una tabla

| Aspecto | Técnico | Libre Disponibilidad |
|---|---|---|
| Origen | CF > DF | Retenciones, percepciones, pagos a cuenta |
| Uso contra DF propio | ✅ Sí | ✅ Sí |
| Uso contra otros impuestos | ❌ No | ✅ Sí |
| Devolución del fisco | ❌ No | ✅ Sí (con requisitos) |
| Cesión a terceros | ❌ No | ✅ Sí (régimen específico) |
| Resultado si nunca genera DF | Queda trabado | Recuperable |

---

## Caso aplicado — Empresa exportadora

### Situación
Una empresa **100% exportadora**:
- Compra insumos en AR: CF = $100K/mes.
- Vende todo al exterior: DF = $0 (exportaciones a tasa 0).

### Sin régimen especial
- Saldo técnico mensual: $100K.
- Acumulado al año: $1,2M.
- ==Trabado indefinidamente== (nunca tendrá DF para usarlo).
- IVA se vuelve costo (= 21% sobre todas las compras).

### Con régimen especial para exportadores

Las exportaciones tienen un régimen específico que permite **recuperar el CF asociado a la exportación** (mediante devolución, compensación o transferencia).

> Ver [[IVA - Exportaciones]] para detalle. Sin este régimen, las exportaciones serían inviables.

---

## Caso típico — Empresa con saldo técnico crónico

### Empresa industrial en expansión

- Q1: invierte en máquinas → mucho CF, poco DF.
- Q2-Q4: empieza a vender → DF crece.

Si compró mucho equipo:
- Saldo técnico en Q1: alto.
- Se va absorbiendo con DF de los meses siguientes.

Si la compra fue muy grande:
- El saldo técnico puede tardar años en absorberse.
- La empresa "presta" plata al fisco sin intereses.

### Implicancia
Para empresas en grandes inversiones, planificar cuándo realizar las compras significativas (idealmente sincronizado con períodos de altas ventas).

---

## Errores comunes

### Error 1 — Confundir los dos tipos
Pedir compensación contra Ganancias con saldo técnico → no procede. Hay que ver el tipo.

### Error 2 — Asumir que se puede pedir devolución del técnico
NO. Solo aplica contra DF futuro. Si nunca tenés DF, queda trabado.

### Error 3 — No registrar las retenciones sufridas
Si te retienen IVA y no usás el certificado en tu DDJJ, estás regalando ese dinero al fisco.

### Error 4 — Olvidar el régimen de exportadores
Si exportás, tenés un régimen especial para recuperar el CF. No usarlo es perder dinero.

### Error 5 — Acumular indefinidamente
Algunos saldos técnicos vienen con plazo (típicamente 10 años en muchos regímenes). Después de eso, pueden caducar.

---

## Implicancias para decisiones empresariales

### Para nuevas inversiones
Considerar el impacto del CF generado. Si vas a invertir mucho de golpe, planificar para absorberlo con DF futuro.

### Para exportadores
Asegurarse de aprovechar el régimen especial. Mantener documentación impecable de las compras vinculadas a exportaciones.

### Para empresas con saldo crónico
Considerar:
- Diversificar actividades (agregar gravadas).
- Reestructurar (separar actividades exportadoras de domésticas).
- Planificar el timing de compras.

---

## Conceptos relacionados

- [[IVA - Concepto y Logica]] — mecánica DF/CF
- [[IVA - Exportaciones]] — régimen especial para exportadores
- [[IVA - Exenciones]] — empresas exentas tienen problema similar
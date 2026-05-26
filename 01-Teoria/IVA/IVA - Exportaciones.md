# IVA — Exportaciones

> Las exportaciones están técnicamente "gravadas a tasa 0%" (fuera del objeto). Mecanismos para recuperar el CF asociado.

---

## TL;DR

- Exportaciones (bienes y servicios) están **fuera del objeto del IVA** → tasa 0%.
- El exportador puede **recuperar el CF asociado** a la exportación mediante:
  1. **Devolución** del fisco
  2. **Compensación** contra otros impuestos
  3. **Transferencia** a otro contribuyente
- Sin este régimen, los exportadores acumularían saldos técnicos imposibles de absorber.

---

## Material de origen

- **Material de Lectura #4** — IVA en Exportaciones
- **Notas de clase**: 2026-04-17
- **Art. 8 LIVA** (régimen específico de exportaciones)

---

## Concepto

### Tasa 0% ≠ Exención

- **Exento**: no genera DF, y el CF asociado se pierde (es costo).
- **Tasa 0%**: no genera DF (matemáticamente), pero ==el CF asociado SE PUEDE RECUPERAR==.

> Esta es una diferencia crítica. Las exportaciones están en tasa 0 (no en exento) precisamente para permitir recuperar CF.

### Lógica
El consumo del bien o servicio se realiza **en el exterior**, no en AR. Por lo tanto AR no debería gravarlo con IVA (no se consume aquí). Pero el exportador tiene CF en AR por sus compras. Si ese CF se vuelve costo, las exportaciones serían inviables.

---

## El problema sin el régimen

### Empresa 100% exportadora

```
Ventas (todas al exterior):      $1.000.000 (tasa 0%, no hay DF)
Compras en AR:                   $500.000 + $105.000 IVA (CF)

DF: $0
CF: $105.000

Saldo TÉCNICO mensual: $105.000 a favor.
Si no se recupera → es costo (21% sobre compras).
```

Sin régimen especial, este saldo nunca se absorbe (porque el exportador no genera DF).

### Solución: recuperación

El régimen permite **recuperar** ese CF de las 3 formas mencionadas.

---

## Los 3 mecanismos de recuperación

### 1. Devolución

El exportador **presenta una solicitud ante AFIP**:
- Explica que las compras estuvieron asociadas a exportaciones.
- Adjunta documentación (facturas, comprobantes de exportación).
- AFIP audita y, si está conforme, **devuelve el monto del CF asociado**.

> El fisco NO devuelve cualquier CF: solo el que se prueba asociado a la exportación.

### 2. Compensación

El exportador **compensa** el saldo a favor (proveniente de exportaciones) contra **otros impuestos** que debe pagar:

- Contra **obligaciones patronales** (cargas sociales del empleador).
- Contra **Ganancias**.
- Contra **otros impuestos** según el régimen.

> Es la forma más rápida de recuperación (sin necesidad de devolución).

### 3. Transferencia

El exportador **transfiere** el saldo a favor **a otro contribuyente** (cesión).

- Por lo general el adquirente paga un porcentaje del valor nominal (ej. 90%).
- Es proceso más complejo y requiere autorización de AFIP.

> Es menos común porque AFIP suele tener requisitos estrictos.

---

## Requisitos para recuperar CF de exportaciones

### Vinculación con la exportación
El CF debe estar **directamente vinculado** a la exportación. AFIP no devuelve cualquier IVA pagado.

### Documentación impecable
- Facturas de proveedores correctas.
- Comprobantes de exportación (despachos aduaneros, etc.).
- Trazabilidad de los costos vinculados.

### Cumplimiento fiscal
La empresa debe estar al día con sus obligaciones para acceder al régimen.

---

## Caso típico: empresa que exporta el 80%

### Situación
- Vende 80% al exterior (tasa 0%).
- Vende 20% en AR (gravado al 21%).
- Compras al 21%.

### Cálculo

```
Ventas internas: $200K → DF = $42K
Ventas externas: $800K → DF = $0

Total CF mensual: $1.000K × 21% / (1+0.21) ≈ $173K

Compensación interna del IVA:
  DF interno: $42K
  CF que se aplica contra ese DF: $42K
  
Saldo restante CF: $173K - $42K = $131K
Este saldo proviene de las exportaciones → recuperable.

→ Solicita devolución/compensación de los $131K.
```

---

## Exportación de servicios

### Definición específica

Exportación de servicios:
- **Lugar de prestación**: Argentina.
- **Lugar de utilización**: Exterior.
- **Cliente**: No residente.

### Tratamiento
**Exenta** (técnicamente exenta, no tasa 0%, pero con beneficios similares):
- No genera DF.
- El CF asociado puede recuperarse (con régimen similar a exportación de bienes).

### Aplicación
Una empresa argentina que presta servicios profesionales a un cliente del exterior, **prestando el servicio desde Argentina**:
- La factura es de exportación de servicios.
- No lleva IVA.
- El CF asociado puede recuperarse.

> Atención: la prestación **desde Argentina** es clave. Si los empleados viajan al exterior para prestar el servicio allá, podría considerarse de manera diferente.

---

## Implicancias para decisiones empresariales

### Para exportadores

- Aprovechar el régimen es esencial. NO usarlo = el IVA es costo del 21% sobre todas las compras.
- Mantener documentación impecable.
- Considerar el lag entre solicitud y recuperación (puede ser meses).

### Para empresas con exportaciones esporádicas

Aun una exportación pequeña puede generar derecho a recuperar. No despreciar la oportunidad.

### Para inversiones en infraestructura para exportar

Si invertís en máquinas/equipos para producir bienes que vas a exportar, ese CF es recuperable. Esto reduce el costo efectivo de la inversión.

---

## Errores comunes

### Error 1 — Confundir exportación con venta a no residente sin envío
Una venta a un cliente del exterior pero entrega en Argentina (cliente lo lleva personalmente) puede NO ser exportación. La exportación requiere salida formal de la mercancía.

### Error 2 — Asumir que tasa 0% = costo cero
La tasa 0% significa que NO se cobra IVA al cliente. PERO el exportador puede tener CF que necesita recuperar. Si no usa el régimen, el CF es costo.

### Error 3 — No mantener trazabilidad
AFIP exige documentación detallada de cada CF que se reclama como vinculado a exportación. Sin documentación, no hay recuperación.

### Error 4 — Confundir exportación con venta digital al exterior
La venta de software a un cliente extranjero puede ser exportación de servicios (si se presta desde AR y se usa afuera) o no, según el caso. Hay que analizar.

### Error 5 — Olvidar incluir las actividades conexas
La exención de IIBB en exportaciones NO incluye actividades conexas (transporte, eslingaje, estibaje). Para IVA, sí están en el régimen pero hay que documentar bien.

---

## Conceptos relacionados

- [[IVA - Objeto]] — exportaciones técnicamente fuera del objeto
- [[IVA - Saldos a Favor]] — el saldo técnico de exportadores
- [[IVA - Concepto y Logica]] — mecánica general
- [[IVA - Importacion de Servicios]] — el otro lado de la moneda
- [[IIBB - Exenciones y No Alcanzados]] — exportación en IIBB
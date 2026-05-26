# Ganancias — Salidas No Documentadas (Art. 40 LIG)

> Régimen sancionatorio para gastos sin respaldo documental. Castigo doble: no se deduce + impuesto especial.

---

## TL;DR

Cuando un gasto no tiene respaldo documental (factura válida):
1. **No es deducible** como gasto en Ganancias.
2. Además, genera un **impuesto especial del 35%** sobre el monto de la erogación.

Efecto combinado: el gasto NO te baja la base imponible + pagás 35% adicional.

---

## Material de origen

- **Material de Lectura #3** — Salidas No Documentadas
- **Notas de clase**: 2026-04-10
- **Art. 40 LIG**
- **Jurisprudencia clave**: Fallo Red Hotelera Iberoamericana

---

## El régimen sancionatorio

### Qué pasa con un gasto sin respaldo

Cuando la empresa registra un gasto que no tiene comprobante (factura válida del proveedor):

**Doble penalización**:

1. **El gasto NO es deducible** → la base imponible no se reduce → pagás Ganancias sobre ese monto al 30%.
2. **Impuesto especial del 35%** → además, pagás 35% sobre el monto de la erogación (que tampoco es deducible).

### Cálculo del impacto total

Si tenés un gasto de $100 sin documentar:

```
Sin documentación:
- Gasto no deducido: $100
- Impuesto adicional: $35 (35% sobre $100)
- Ganancias adicional sobre el monto no deducido: $30 (30% × $100)
- TOTAL adicional: $65 perdidos por no haber documentado

Con documentación:
- Gasto deducido: $100
- Ganancias ahorrado: $30 (30% × $100)
- TOTAL ahorrado: $30 de beneficio fiscal
```

> Diferencia: $95 entre tener o no tener documentación correcta.

---

## Lógica del régimen

### Por qué tan estricto

El fisco busca **evitar la economía informal**:
- Si permite deducir gastos sin documentación, las empresas pueden inflar gastos sin que el fisco controle al otro lado.
- El documento (factura) genera un "rastro" porque el proveedor tiene que declararlo como ingreso.
- Sin documento, hay un "agujero negro" donde el dinero sale de una empresa pero el fisco no puede rastrear al receptor.

### El 35% castiga la falta de identificación del receptor

> Conceptualmente, el 35% es lo que el receptor del dinero "debería haber pagado" como receptor de ingreso. Como no se sabe quién es, se lo cobra al que pagó.

---

## Caso clásico — Fallo Red Hotelera Iberoamericana

### Contexto
Una cadena hotelera construye un hotel en Argentina (caso emblemático: Hotel Costa Galana en Mar del Plata). La obra tenía dos componentes de costo: ~45% mano de obra y ~55% materiales (Lauti). La mano de obra **no fue facturada formalmente** (era trabajo "en negro" de los obreros) y por eso no se podía registrar el IVA de los materiales correspondientes a esa parte. El arquitecto se ofrece a generar una factura por la mano de obra después, para regularizar.

> ==**El IVA nunca es costo**==: la trampa del esquema era que el empresario no quería pagar el IVA de los materiales atados a la mano de obra en negro, pero esa decisión arrastró todo el ajuste posterior (Lauti).

El arquitecto cobraba normalmente honorarios del ~20% del valor de obra; en este caso se le facturó ~40%. La AFIP detectó la anomalía cruzando datos: el arquitecto no tenía empleados que justificaran una facturación tan alta.

### Decisión del fisco
Aplicó el régimen de salidas no documentadas:
- No permitió deducir el gasto de mano de obra.
- Aplicó el 35% adicional.

### El "ahorro" que perdieron
La cadena hotelera "ahorraba" en amortizaciones (porque construir un inmueble se amortiza en ~50 años). El fisco le hizo pagar el 35% del monto del impuesto, anulando totalmente el ahorro.

> Lección del fallo: el régimen del Art. 40 se aplica con dureza incluso cuando hay intentos posteriores de regularizar. La documentación tiene que ser **en tiempo y forma**.

### Excepción jurisprudencial
El fallo establece una excepción: si se puede **probar que la erogación tuvo un destinatario real que tribute por ese ingreso**, puede evitarse el 35%.

> Esto deja una salida estrecha: si después se identifica al receptor y se prueba que él tributó por el ingreso, se evita la doble sanción. Pero es difícil de probar.

### Excepciones legales (facultad del Fisco)

Más allá del fallo Red Hotelera, ==el Fisco puede **decidir NO exigir** el 35% en los siguientes casos==:

1. **Cuando presume que los pagos fueron efectuados para adquirir bienes**.
   - Lógica: si claramente la salida fue para comprar bienes (aunque sin factura), el "destinatario" es el vendedor del bien. La erogación no es una "salida fantasma".

2. **Cuando presume que los pagos — por su monto, etc. — no llegan a ser ganancias gravables en manos del beneficiario**.
   - Lógica: si el receptor (aunque no identificado) no habría pagado Ganancias por el monto (por estar bajo mínimo no imponible, por ejemplo), no tiene sentido exigir el 35% que reemplaza lo que debería haber pagado.

> ==Es **facultad exclusiva del Fisco**==: el contribuyente NO puede invocar estas excepciones automáticamente. Solo el Fisco decide aplicarlas en una inspección.

---

## Factura apócrifa

Es un caso especial dentro del régimen. Una factura **apócrifa** es una factura que **parece válida pero no lo es**:

**Causales de invalidez**:
- **Emisor inexistente** (no existe la persona o empresa que emite).
- **Emisor incumplidor** (existe pero no presenta DDJJ, no paga impuestos, declarado fraudulento).
- **Emisor cumplidor PERO sin prestación efectiva** (la operación es ficticia, no hubo entrega real del bien o servicio).

### Base de datos APOC
AFIP mantiene la base APOC con emisores identificados como apócrifos. Si comprás a alguien que está en APOC, tu factura es inválida.

> Detección: el fisco cruza datos. Si el "vendedor" no declara las ventas que vos declarás como compras, hay alerta.

### Efecto
La factura apócrifa genera **salida no documentada**. Es decir: gasto no deducible + 35% adicional.

### Cálculo del ajuste fiscal — ejemplo Red Hotelera

> Caso típico de inspección. El fisco llega 5 años después de los hechos:
> 
> **Si fue por amortizaciones tomadas indebidamente** (típico de la construcción con factura apócrifa):
> - Amortización tomada de más como gasto: $72.600 × 5 años = **$363.000**
> - Ganancias dejado de pagar sobre eso: 35% × $363.000 = **$127.050**
>
> **Ajuste con salidas no documentadas**:
> - Gasto no deducible: $363.000
> - 35% del comprobante apócrifo (sobre la factura del arquitecto, ej. $3.630.000): $1.270.500
> - ==**Ajuste total**: $127.050 + $1.270.500 = **$1.397.550**==
>
> ==El "ahorro" de $127K original se transforma en una deuda fiscal de ~$1,4M==.

---

## Implicancias para decisiones empresariales

### Documentar todo
Cualquier gasto que vaya al estado de resultados debe tener su factura. Si no la tenés, **NO lo deduzcas**, porque si la AFIP lo detecta es peor.

### Verificar proveedores
Antes de hacer una operación importante, verificar que el proveedor sea cumplidor (no esté en APOC, presente DDJJ, factura electrónica válida).

### Operaciones grandes
Para operaciones de monto significativo, exigir factura A (no C, no consumidor final) y CUIT/CUIL del proveedor. Confirmar inscripción en AFIP.

### Pagos a empleados
Sueldos pagados "en negro" generan salida no documentada por el monto de los sueldos. El "ahorro" en cargas sociales se anula con creces por las penalidades.

---

## Errores comunes

### Error 1 — Asumir que se puede regularizar después
Si la factura no se obtuvo en el momento de la operación y el fisco lo detecta antes que regularices, no podés escapar de la sanción.

### Error 2 — Pagar a alguien sin verificar
"Confiar" en que el proveedor está al día no alcanza. Hay que verificar (constancia de inscripción AFIP, situación en APOC).

### Error 3 — Solo pensar en el 35%
El 35% es solo una parte del costo. Sumás también el impuesto a las ganancias sobre el monto no deducido (30%). El costo real puede ser 65% del monto.

### Error 4 — Asumir que el fallo Red Hotelera "salva"
La excepción del fallo es estrecha y difícil de aplicar. No es una vía de escape confiable.

### Error 5 — No considerar la economía informal
Los emprendimientos que operan parcialmente en negro acumulan riesgos de salida no documentada. Llegado un control, las consecuencias pueden ser ruinosas.

---

## Conceptos relacionados

- [[Ganancias - Concepto y Optimizacion]] — la deducción de gastos es una herramienta de optimización
- [[Ganancias - Dividendo Ficto y Disposicion de Fondos]] — otro régimen anti-abuso
- [[Fallo Red Hotelera]] — desarrollo completo del fallo
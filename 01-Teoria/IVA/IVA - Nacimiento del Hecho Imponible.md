# IVA — Nacimiento del Hecho Imponible

> El "cuándo" del IVA. Define el período en que la operación debe declararse.

---

## TL;DR

El IVA nace en momentos distintos según el tipo de operación:
- **Venta de bienes**: el primero entre entrega, factura o acto equivalente
- **Prestación de servicios**: el primero entre fin de la prestación o percepción del precio
- **Señas**: depende de si congelan o no el precio

---

## Material de origen

- **Material de Lectura #5** — Nacimiento del Hecho Imponible en IVA
- **Notas de clase**: 2026-04-24
- **Caso disparador** (clase): CEO de empresa de publicidad digital que factura 50% adelantado por una campaña de 2 años, cobrable a 90 días.

---

## Concepto central — por qué importa

El nacimiento del hecho imponible determina **en qué mes** se incluye la operación en la declaración jurada del IVA. Esto afecta:

- Cuándo hay que ingresar el débito fiscal al fisco
- Cuándo se puede computar el crédito fiscal correlativo
- El costo financiero de adelantar IVA antes de cobrar (la "perdida financiera" aunque no económica)

> Ejemplo del profesor: si tengo que ingresar $105 de IVA el día 20 del mes siguiente a la factura, pero cobro la factura a los 90 días, el IVA es **neutro económicamente** pero **costoso financieramente**. Esa diferencia se diseña eligiendo bien cuándo se emite la factura.

---

## Reglas por tipo de operación

### 1. Venta de cosas muebles

El IVA nace en **el primero** de estos tres momentos:

1. **Entrega del bien**
2. **Emisión de la factura** respectiva
3. **Acto equivalente** a la emisión de la factura (cuando no existe obligación de facturar)

> El "acto equivalente" aplica típicamente en venta de inmuebles, donde no se emite factura sino escritura. La escritura cumple el rol de factura para el nacimiento del HI.

### 2. Obras, locaciones y prestaciones de servicios

El IVA nace en **el primero** de:

1. **Fin de la ejecución o prestación** del servicio
2. **Percepción total o parcial del precio**

#### Servicios continuos (recurrentes)
Cuando el servicio se presta de forma continua (mantenimiento mensual, abono, suscripción), el IVA nace al **fin de cada mes calendario** sobre la prestación de ese mes.

### 3. Importación definitiva de cosas muebles

El IVA nace al momento del **despacho a plaza** por la aduana. Es el evento físico de ingreso al territorio nacional.

### 4. Importación de servicios

El IVA nace al **finalizar la prestación** o al **pagar el precio**, lo que ocurra primero. El responsable sustituto (RI argentino) lo ingresa en su DDJJ del período correspondiente.

---

## Excepciones importantes

### Canje agropecuario (excepción específica)

Cuando se realiza un canje de productos primarios (típico: camionetas a cambio de soja, fertilizante a cambio de granos):

**Regla general (no aplica acá)**: la entrega de las camionetas en febrero gravaría IVA en febrero.

**Excepción**: si el canje se materializa en momentos distintos (entrega de un lado en febrero, del otro en cosecha), el IVA del débito fiscal por la entrega de las camionetas nace recién cuando se reciben los productos primarios canjeados.

> Razón: evitar que el productor pague IVA por anticipado cuando aún no recibió el bien canjeado. Si no existiera esta excepción, el productor pagaría IVA en febrero por $120 cuando en realidad ese precio puede caer a $14 en cosecha — generando una pérdida injusta.

### Señas — dos tratamientos según congelen o no precio

**Seña que NO congela precio**
- Pagás 25% como adelanto, pero si sube el precio, la seña sube proporcionalmente.
- **El IVA no nace** con el pago de la seña.
- El IVA nace recién con el pago total del precio.

**Seña que congela precio**
- Pagás 25% y queda fijado el precio total, sin importar lo que pase después.
- **El IVA de la seña nace en el momento del pago de la seña**.
- El resto del IVA nace en cada pago posterior.

> Lógica: si la seña congela el precio, fija un hecho económico definitivo. Si no congela, sigue siendo provisorio y el verdadero hecho imponible se materializa al cierre.

---

## Caso clase aplicado — Empresa de publicidad

**Enunciado**: facturás 50% del valor de la campaña de los próximos 2 años, cobrable a 90 días.

**Análisis**:
- ¿Cuándo nace el HI por esa factura del 50%?
- Servicio: nace al **primero** entre fin de la prestación o percepción del precio.
- ¿La factura cuenta? **No** para servicios (sí cuenta solo para venta de bienes).
- Si la facturás hoy pero el servicio se prestará en 2 años, y el cobro es a 90 días → el HI nace **al cobro** (90 días), no antes.

**Implicancia práctica**: tenés 90 días sin IVA a ingresar por esa parte. Si la cobrara al contado, el IVA nace ya.

---

## Errores comunes

### Error 1 — Pensar que la factura define el HI en servicios
**No.** Para servicios, la factura **no** dispara el nacimiento del HI. Solo la entrega física del servicio o la percepción del precio lo hacen. La factura sí define el HI en venta de cosas muebles.

### Error 2 — Confundir nacimiento del HI con devengado de Ganancias
Son criterios distintos:
- **Devengado (Ganancias)** = nacimiento del derecho a cobrar
- **Nacimiento HI (IVA)** = el primero entre los eventos definidos por la Ley de IVA

Una venta puede estar devengada para Ganancias en el Año 1 pero generar IVA en el Año 2 si el cobro ocurre en el Año 2 antes de la entrega.

### Error 3 — Tratar todas las señas igual
Si te preguntan por una seña, lo primero es averiguar si **congela o no** el precio. La respuesta cambia completamente.

### Error 4 — Olvidar la regla del primer evento
"Lo que ocurra primero" es la regla, no "lo que ocurra al final". Si emitís factura antes de entregar (típico en ventas anticipadas), el IVA nace con la factura.

---

## Reglas críticas a memorizar

| Operación | Eventos | Cuál dispara HI |
|---|---|---|
| Venta de bienes | Entrega, factura, acto equiv. | El primero |
| Servicios | Fin prestación, percepción | El primero |
| Servicios continuos | — | Fin de cada mes |
| Importación bienes | Despacho aduana | Único evento |
| Importación servicios | Fin prestación, pago | El primero |
| Seña que NO congela | Pago seña, pago total | Solo el total |
| Seña que SÍ congela | Pago seña, pago total | Ambos en su momento |
| Canje agropecuario | Entrega de cada parte | Cuando se entrega el bien canjeado |

---

## Conceptos relacionados

- [[Devengado vs Percibido]] — criterio análogo pero para Ganancias, no confundir
- [[IVA - Objeto]] — qué operaciones están alcanzadas
- [[IVA - Sujeto]] — quién es responsable
- [[Hecho Imponible (4 elementos)]] — marco general

---

## Citas relevantes

> Fuente: **Notas 24/04/2026 — Nacimiento HI Venta de bienes**: el HI nace en el primero entre entrega, factura o acto equivalente. El "acto equivalente" aplica a operaciones donde no hay obligación de factura (ej. escritura inmobiliaria).

> Fuente: **Notas 24/04/2026 — Señas**: "Si la seña no congela precio no tenés que reconocer el IVA hasta que se efectúa el pago. Si la seña congela precios tenés que reconocer el IVA de la seña en el momento que pagás la seña."

> Fuente: **ITD - Skill Parcial — IVA Nacimiento HI**: servicios continuos → HI fin de cada mes calendario.

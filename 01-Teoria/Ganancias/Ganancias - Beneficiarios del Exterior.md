# Ganancias — Beneficiarios del Exterior (Art. 93)

> Mecánica de retención cuando un residente argentino paga renta de fuente argentina a un sujeto del exterior.

---

## TL;DR

- Cuando un **residente argentino paga** renta de fuente argentina a un **no residente**, actúa como **agente de retención**.
- La retención es de **pago único y definitivo** (no hay declaración jurada posterior).
- La tasa depende del tipo de ingreso (Art. 93 LIG): se aplica **presunción de ganancia neta** × **35%**.
- Si la empresa argentina asume el costo del impuesto, se aplica **gross-up**.

---

## Material de origen

- **Material de Lectura #2** — Beneficiarios del Exterior
- **Notas de clase**: 2026-03-13, 2026-04-24
- **Resumen Claude**: 2026-03-13 sección 7
- **Caso clave**: Material 7 Caso 1 — Empresa de UK con servicios técnicos

---

## Concepto general

### El problema
Un proveedor del exterior factura a una empresa argentina. La factura genera **renta de fuente argentina** para el proveedor (por aplicación del Art. 5 o de algún Art. específico como el 13).

### Quién paga
El no residente debería pagar impuesto en AR, pero **AR no tiene jurisdicción directa** sobre él. La solución: el **residente argentino** (cliente) actúa como **agente de retención** y le retiene el impuesto al proveedor al momento del pago.

### Carácter de la retención
La retención es **pago único y definitivo**: el no residente NO presenta declaración jurada en AR ni puede pedir devolución. Lo retenido es lo que tributó.

---

## Mecánica del Art. 93

### Lógica de la presunción

El proveedor del exterior no presenta declaración jurada en AR, así que no se conoce su "ganancia neta real". La ley resuelve esto con **presunciones**: asume qué porcentaje del monto pagado es ganancia neta.

```
Presunción de ganancia neta = X% del monto pagado
Tasa = 35%
Tasa efectiva = X% × 35%
```

### Tabla de presunciones (Art. 93 LIG)

| Inciso | Tipo de ingreso | Presunción ganancia neta | Tasa efectiva |
|---|---|---|---|
| **a)** | Contratos de transferencia tecnología (registrados) | 60% | 21% |
| **b)** | Regalías sobre bienes situados en AR | 60% | 21% |
| **c)** | Sumas pagadas por cesión de derechos | 60% | 21% |
| **d)** | Películas cinematográficas, videos | 50% | 17,5% |
| **e)** | Intereses por créditos | 100% (algunos casos 35,5%) | 35% (o 12,425%) |
| **f)** | Sueldos, honorarios y otras retribuciones | 70% | 24,5% |
| **g)** | Locación de cosas muebles efectuadas por locadores residentes en el exterior | 40% | 14% |
| **h)** | **Servicios técnicos** (asistencia técnica, servicios técnicos no encuadrados en otros incisos) **sin asesoramiento** | **90%** | **31,5%** |
| **i)** | Otros casos | 90% | 31,5% |

> El inciso h) es el más usado en los ejercicios. **Memorizá**: 90% presunción → 31,5% efectiva.

---

## Gross-up — cuando el comprador asume el impuesto

### El problema
Si el contrato dice "el proveedor del exterior recibe USD X netos", la empresa argentina debe absorber la retención. ¿Cuánto debe pagar **bruto** para que después de retener queden USD X netos?

### Fórmula

```
Bruto = Neto / (1 - tasa efectiva)
```

### Ejemplo

Empresa argentina contrata empresa UK por servicios técnicos sin asesoramiento. UK debe recibir USD 175.000 netos.

- Tasa efectiva = 31,5% (Art. 93 inc. h).
- Bruto = 175.000 / (1 − 0,315) = **USD 255.474,45**.

Verificación:
- Bruto: 255.474,45
- Retención (31,5%): 80.474,45
- Neto: 175.000 ✓

> Ver [[Gross-up]] para casos típicos y errores.

---

## Cómo identificar el inciso aplicable

### Si el contrato dice expresamente que NO hay asesoramiento

→ Inciso **h)** (servicios técnicos sin asesoramiento) → **31,5%**.

> Este es el caso del ejercicio típico de la materia.

### Si hay asesoramiento prestado desde el exterior con uso en AR

→ Art. 13 + Art. 93. La tasa depende del tipo específico.

### Si son regalías sobre uso de marca o patente

→ Inciso **b)** → 21%.

### Si son intereses

→ Inciso **e)**. Depende de si es banco/financiera (100% presunción → 35%) u otro (35,5% → 12,425%).

---

## Caso aplicado — Empresa UK (Material 7 Caso 1)

**Enunciado breve**: empresa AR contrata empresa UK por USD 175.000. Servicios técnicos SIN asesoramiento. UK envía empleados a trabajar EN AR durante 3 meses. Empresa AR asume impuestos.

**Resolución**:

1. **Sujeto**: UK = no residente → tributa solo por fuente argentina.
2. **Espacio**: empleados trabajan EN AR → fuente argentina (Art. 5).
3. **Tipo de ingreso**: servicios técnicos sin asesoramiento (lo dice el contrato).
4. **Inciso aplicable**: Art. 93 inc. h) → presunción 90% → tasa efectiva 31,5%.
5. **Gross-up**: 175.000 / (1 - 0,315) = USD 255.474,45.
6. **Retención**: 31,5% × 255.474,45 = USD 80.474,45.
7. **Costo total** (sin IVA): USD 255.474,45.

Más IVA por responsable sustituto (Art. 4.1 IVA), que es neutro económicamente.

> Ver [[Material 07 - Resuelto#Caso 1 — Empresa UK presta en Argentina (gross-up + IVA)|Material 07 — Caso 1]] para la resolución completa.

---

## Casos donde NO hay retención

### Importación de bienes (Art. 9)
Cuando AR importa bienes del exterior, NO hay retención al proveedor. La operación es fuente extranjera para el proveedor.

### Servicio prestado en el exterior con uso en el exterior
Si un argentino contrata un servicio que se presta afuera y se usa afuera (ej. consultor inglés que asesora sobre mercado uruguayo para desembarco en Uruguay), NO hay retención.

### Pagos a entidades exentas con tratado
Algunos tratados bilaterales eximen ciertos pagos. Hay que chequear el CDI específico (Convenio de Doble Imposición).

---

## El otro lado: cuando AR recibe

Si la empresa argentina **factura al exterior** y el cliente extranjero le retiene su impuesto local:

- Si la renta es de **fuente argentina** (servicio prestado desde AR) → la retención del cliente es **costo** (no tax credit).
- Si la renta es de **fuente extranjera** (servicio prestado afuera) → la retención del cliente es **tax credit** (recuperable contra el IG argentino sobre fuente extranjera).

> Ver [[Tax Credit]] y caso Material 7 Caso 3 (servicio a Francia).

---

## Errores comunes

### Error 1 — Aplicar 35% directo
La tasa efectiva NUNCA es 35% para beneficiarios del exterior, porque siempre hay presunción de ganancia neta. Es 35% × presunción.

### Error 2 — Olvidar el gross-up cuando se asume el impuesto
Si el contrato dice "te pago X netos" → SIEMPRE hay gross-up. Es un error común restar la retención directamente del monto del enunciado.

### Error 3 — Confundir inciso h con inciso a
- **Inciso a)** = contratos de transferencia tecnológica registrados (60% → 21%).
- **Inciso h)** = servicios técnicos sin asesoramiento (90% → 31,5%).
- Si el contrato dice "asistencia técnica" puede caer en uno u otro según si hay registro y características.

### Error 4 — Tratar la retención como recuperable en AR
La retención al beneficiario del exterior es **pago único y definitivo**. No es recuperable, no se descuenta de otro impuesto, no se devuelve.

### Error 5 — Olvidar el IVA por responsable sustituto
Cuando hay pago a no residente con servicio en AR (o importación de servicios), además de Ganancias también hay **IVA por responsable sustituto** (Art. 4.1 IVA). El IVA es neutro económicamente pero hay que mencionarlo.

---

## Conceptos relacionados

- [[Ganancias - Fuente]] — qué es fuente argentina
- [[Gross-up]] — cómo calcular el bruto
- [[Renta Mundial vs Territorialidad]] — por qué no residente tributa fuente argentina
- [[IVA - Importacion de Servicios]] — IVA paralelo a Ganancias
- [[Tax Credit]] — el otro lado de la moneda
---

## Casos en el vault donde aparece este concepto

| Caso | Beneficiario | Inciso / Tasa | Clave |
|---|---|---|---|
| [[../../03-Ejercicios/Resueltos-Catedra/Material 06/Caso 3 - CEO Discografica Argentina\|Mat 06 · Caso 3]] | Múltiples beneficiarios del exterior | Varios incisos analizados por pago | Cada concepto (regalías, sueldos, viáticos) tiene su inciso |
| [[../../03-Ejercicios/Resueltos-Catedra/Material 07/Caso 1 - Empresa UK Presta en Argentina\|Mat 07 · Caso 1]] | Empresa UK, servicios técnicos en AR | Inc. h → 31,5% | Gross-up: empresa AR asume retención |
| [[../../03-Ejercicios/Resueltos-Catedra/Material 10/Caso II - ARGSecurity Consultoria BMV Argentina\|Mat 10 · Caso II]] | Empresa uruguaya, servicio en AR | Inc. h → 31,5% | ARGSecurity actúa como agente de retención |
| [[../../04-Parciales-Anteriores/Diciembre 2025/Resolucion\|Parcial Dic 2025]] | Proveedor brasilero (A3) | 31,5% sobre porción fuente AR | Retención proporcional al uso en AR (25%) |
| [[../../04-Parciales-Anteriores/Recuperatorio 2do Cuatrim 2025/Resolucion\|Recuperatorio 2025]] | Gordon Ramsay (UK) | CDI Argentina-UK → 10% | CDI override al Art. 93; gross-up: 160k/0,90 = 177.777,78 |

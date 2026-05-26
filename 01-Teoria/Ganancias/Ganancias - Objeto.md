# Ganancias — Objeto

> El elemento Objeto del Impuesto a las Ganancias cambia según el sujeto. Hay dos teorías que conviven en la misma ley.

---

## TL;DR

| Sujeto | Teoría aplicable | Qué se grava |
|---|---|---|
| **Persona Humana (PH)** | Teoría de la Fuente | Solo ingresos que cumplan 3 requisitos concurrentes |
| **Persona Jurídica (PJ)** | Teoría del Balance | Todos los ingresos provenientes de negocios reales |

Si te preguntan por el objeto, lo primero es identificar **el sujeto** porque define qué teoría aplicar.

---

## Material de origen

- **Material de Lectura #2** — Objeto del Impuesto
- **Notas de clase**: 2026-03-13
- **Resumen Claude**: 2026-03-13 secciones 2 y 3
- **Caso disparador**: empresa de ciberseguridad propiedad de PH argentino

---

## Por qué importa

La distinción es la primera pregunta de cualquier análisis: ¿quién es el sujeto? Porque la respuesta cambia completamente lo que está alcanzado.

Un mismo evento económico puede:
- **No estar gravado** para una PH (porque no cumple los 3 requisitos)
- **Estar gravado** para una PJ (porque todo negocio real está alcanzado)

---

## Teoría de la Fuente (Persona Humana) — Art. 2 inc. 1 LIG

Para que un ingreso esté gravado en una PH, deben cumplirse **los 3 requisitos simultáneamente**. Si falta uno, no está gravado.

### Los 3 requisitos

#### 1. Periodicidad
El ingreso se repite con cierta regularidad.

- **Real**: ya ocurrió varias veces (cobré honorarios todos los meses durante 3 años).
- **Potencial**: es esperable que se repita (un médico habilitado, aunque haya tenido un mes sin pacientes).

#### 2. Permanencia de la fuente
La fuente que genera el ingreso subsiste después de producirlo. No se agota al generar el ingreso.

> Ejemplo de permanencia: la mente y la capacitación de un contador. Cada consulta no destruye la fuente.

> Ejemplo de NO permanencia: la venta de una casa propia. La fuente (la casa) desaparece al venderla.

#### 3. Habilitación
La fuente está habilitada (puesta en condiciones) para generar el ingreso.

> Ejemplo: un médico con título y consultorio habilitado. Si no tiene título, no está habilitado, aunque atienda pacientes.

### Aplicación práctica

**Médico que cobra honorarios mensuales**:
- ✅ Periodicidad: cobra todos los meses.
- ✅ Permanencia: su capacidad profesional persiste.
- ✅ Habilitación: tiene título y consultorio.
- → **GRAVADO**.

**Mismo médico vende su auto particular**:
- ❌ Periodicidad: no es periódica la venta de autos.
- → **NO GRAVADO** (no hace falta seguir analizando).

**Persona humana que vende su casa**:
- ❌ Permanencia: la casa "desaparece" como fuente.
- → **NO GRAVADO**.

---

## Teoría del Balance (Persona Jurídica) — Art. 2 inc. 2 LIG

Para las sociedades, **todos los ingresos derivados de sus negocios están gravados**, sin importar si son periódicos, si la fuente permanece o si está habilitada.

### Por qué es así

Una sociedad existe para hacer negocios. Cualquier resultado positivo de esos negocios es renta de su 3ra categoría. La ley asume que **cualquier ingreso de una sociedad es producto de su actividad empresarial**.

> Detalle clave: una sociedad solo puede tener renta de **3ra categoría** (renta empresarial). No puede tener 1ra, 2da ni 4ta. Esto se desprende de su naturaleza jurídica.

### Lo que NO está gravado (excepción)

Aunque la regla es "todo está gravado", hay una excepción crítica: los **ingresos provenientes de normas contables** sin negocio real **NO** están gravados.

| Tipo de ingreso | ¿Gravado? | Razón |
|---|---|---|
| Ingresos por ventas | ✅ Sí | Negocio real |
| Intereses ganados | ✅ Sí | Negocio real |
| Diferencias de cambio | ✅ Sí | Negocio real |
| Indemnizaciones | ✅ Sí | Negocio real |
| Ingresos por condonación | ✅ Sí | Negocio real (se le perdonó una deuda) |
| Resultado venta de acciones | ✅ Sí | Negocio real |
| Recupero de previsión por incobrables | ✅ Sí | Negocio real (se recupera algo castigado) |
| **Resultado por VPP** | ❌ No | Norma contable (revalúo en libros) |
| **Impuesto a las ganancias diferido** | ❌ No | Norma contable |
| **Resultado por tenencia** | ❌ No | Norma contable (revalúo de stocks o bienes) |
| **Revalúo técnico contable** | ❌ No | Norma contable |
| **Ganancia por ajuste por inflación contable** | ❌ No | Norma contable |

> Regla mnemotécnica: ==si surge de un **negocio real** (hubo una operación con un tercero), está gravado. Si surge de un **asiento contable** sin contraparte real, no está gravado==.

### Aplicación práctica — empresa industrial

| Operación | ¿Gravada? |
|---|---|
| Venta de mercadería a un cliente | ✅ Sí (venta = negocio real) |
| Venta de una máquina usada del patrimonio | ✅ Sí (venta = negocio real, aunque no sea habitual) |
| Revalúo contable de bienes de uso al cierre | ❌ No (norma contable) |
| Diferencia de cambio por cobro en USD | ✅ Sí (diferencia real, hay efecto patrimonial) |

---

## Caso aplicado — Bitboc (empresa de bitcoins)

Bitboc es una sociedad. Aplica teoría del balance. Análisis ítem por ítem:

1. **Comisiones por compra/venta de bitcoins**
   - Ingreso propio del negocio (los bitcoins son de los clientes pero la comisión es de Bitboc).
   - → ✅ **GRAVADO** (negocio real).

2. **Diferencia de cotización al cierre del ejercicio**
   - Es un **resultado por tenencia** (revalúo de los bitcoins en libros).
   - → ❌ **NO GRAVADO** (norma contable, no hay venta).

3. **Mayor valor de acciones en "Pay Paul"**
   - Es **resultado por VPP** (revalúo de la participación en otra sociedad).
   - → ❌ **NO GRAVADO** (norma contable). Si se vendieran las acciones, sí sería ganancia gravada.

4. **Intereses por colocación en mercado bursátil USA**
   - Intereses ganados, negocio real.
   - Como residente, Bitboc tributa por **renta mundial** (incluye fuente extranjera).
   - → ✅ **GRAVADO**.

5. **Cesión de créditos ($100 cobrados a $90)**
   - Pérdida de $10. Negocio real (transferencia efectiva del crédito).
   - → **PÉRDIDA GRAVADA** (cuenta como quebranto, en este caso específico potencialmente quebranto específico por ser de valores).

---

## Distinción crítica para el parcial

### Si el sujeto es PH

Análisis: ¿Periodicidad + Permanencia + Habilitación?
Si falta uno → **NO GRAVADO**.

### Si el sujeto es PJ

Análisis: ¿Es un negocio real o una norma contable?
- Negocio real → **GRAVADO**.
- Norma contable → **NO GRAVADO**.

---

## Errores comunes

### Error 1 — Aplicar teoría de la fuente a una sociedad
Frecuente. Una sociedad nunca usa teoría de la fuente. La pregunta "¿es periódico?" no aplica para PJ.

### Error 2 — Olvidar la habilitación
Para que una PH esté alcanzada hace falta habilitación. Si una PH realiza una actividad sin estar habilitada (ej. sin título habilitante), técnicamente no está gravada por esa renta. Esto es una zona gris.

### Error 3 — Confundir resultado por tenencia con resultado por venta
- Resultado por tenencia = revalúo en libros, NO gravado.
- Resultado por venta = se concretó la venta, SÍ gravado.

### Error 4 — Asumir que VPP es gravado porque "es una ganancia"
La ganancia de VPP es **contable**, no fiscal. Solo se grava cuando vendés las acciones (ahí sí es venta = negocio real).

### Error 5 — Olvidar la 4ta categoría
La 4ta categoría (trabajo personal en relación de dependencia) es para PH y usa criterio percibido. No la mezcles con sociedades.

---

## Conceptos relacionados

- [[Teoria de la Fuente vs Balance]] — desarrollo completo del concepto
- [[Ganancias - Sujetos]] — quiénes son cada tipo
- [[Ganancias - Fuente]] — elemento Espacio
- [[Ganancias - Criterios de Imputacion]] — elemento Tiempo
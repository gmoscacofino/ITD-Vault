# Ganancias — Endeudamiento con el Exterior

> Cómo tratar fiscalmente la recomposición de Patrimonio Neto negativo cuando la causa es deuda con el exterior. Tabla de tratamiento por tipo de pasivo y mecanismo de extinción.

---

## TL;DR

Una sociedad local con deuda en moneda extranjera puede caer en **PN negativo** por devaluación. Hay 3 mecanismos para recomponer:

1. **Capitalización de pasivo** → el pasivo pasa a Capital Social. Se considera **pago** para Ganancias.
2. **Condonación** del acreedor → la deuda desaparece. Genera **ganancia gravada** (si hubo gasto previo).
3. **Reintegro de capital** → los accionistas reponen sin emitir nuevas acciones.

==Cuando la extinción es por **capitalización** o **pago**, hay que evaluar si correspondía retención de Ganancias (Art. 93). En **condonación**, hay que ver si hubo gasto previo: si no lo hubo, no es ganancia gravada.==

---

## Material de origen

- **Material de Lectura #4** — El Endeudamiento con el Exterior
- **Notas de clase**: 2026-04-24
- **Resumen Cheto** — Material 4 sección Endeudamiento

---

## El problema del PN negativo

### Origen del problema

Una sociedad argentina contrae deuda con el exterior (préstamo financiero, deuda comercial, etc.) en moneda extranjera.

Cada vez que el peso se devalúa (decisión del gobierno, no de la empresa):
- La deuda en pesos **crece** automáticamente.
- Aparece una **pérdida por diferencia de cambio** en el balance.
- Esa pérdida acumulada puede llevar el ==**Patrimonio Neto a negativo**==.

### Por qué importa

Por la ley de sociedades, un PN negativo implica obligación de recomponer la situación o disolver. Por eso hay urgencia de buscar mecanismos para volver a PN positivo.

### Qué se puede tocar para recomponer

==Solo se puede aumentar el **Capital Social**==. El resto del PN (resultados acumulados, reservas, etc.) son consecuencia del negocio y no se pueden alterar discrecionalmente.

---

## Las 3 opciones

### Opción 1: Capitalización del pasivo

#### Mecánica

El acreedor del exterior acepta que su crédito se convierta en participación accionaria. ==El pasivo deja de ser deuda y pasa a ser **Capital Social**==.

```
ANTES:
  Pasivo (deuda con exterior): $1.000.000
  PN: -$500.000

DESPUÉS (capitalización):
  Pasivo (deuda con exterior): $0
  Capital Social: +$1.000.000
  PN: +$500.000 ✓
```

#### Problema fiscal

==Para la ley de Ganancias, **la capitalización equivale a un pago**==. Y si el pasivo capitalizado contenía intereses (renta de fuente argentina para el acreedor del exterior), debería haber correspondido **retención del 35%** sobre esos intereses.

> Es decir: capitalizar = pagar, y si correspondía retención, hay que ingresarla aunque no haya salido cash.

### Opción 2: Condonación por parte del acreedor

#### Mecánica

El acreedor le dice a la sociedad argentina: "no me debes nada, te lo regalo". El pasivo desaparece y la diferencia pasa al ==Estado de Resultados como **ganancia**==. Esa ganancia mejora el PN.

```
ANTES:
  Pasivo (deuda con exterior): $1.000.000
  PN: -$500.000

DESPUÉS (condonación):
  Pasivo: $0
  Resultado del ejercicio: +$1.000.000
  PN: +$500.000 ✓
```

#### Tratamiento fiscal

==Depende de si la deuda ya generó un gasto deducible previamente==.

| Tipo de deuda | ¿Hubo gasto previo? | Condonación |
|---|---|---|
| **Préstamo — Capital** | No (el capital recibido no es ingreso ni gasto) | ==Ganancia gravada== |
| **Préstamo — Intereses** | Sí (los intereses se devengaron como gasto) | ==NO es ganancia== (sería doble cómputo: deduje el gasto y ahora lo recibo gratis) |
| **Deuda por servicio** | Sí (el servicio se devengó como gasto) | ==NO es ganancia== (misma lógica) |

> La regla: si **hubo gasto deducido** que generó la deuda, la condonación NO se grava (sería revertir el gasto, pero ya pasó). Si **NO hubo gasto** (caso del capital de un préstamo), la condonación SÍ es ganancia gravada.

### Opción 3: Reintegro de capital

#### Mecánica

Los accionistas vuelven a poner dinero, pero **sin emitir nuevas acciones**. La diferencia con un aporte normal: aporte → emitís acciones nuevas. Reintegro → no.

```
ANTES:
  Capital Social: $500.000
  PN: -$500.000

DESPUÉS (reintegro de capital):
  Capital Social: $500.000 (igual)
  Aportes a integrar: +$1.000.000
  PN: +$500.000 ✓
```

#### Estado fiscal

==Es ambiguo==: no queda claro si la ley lo trata como pago (capitalización) o como ganancia. En la práctica, suele tratarse como aporte (sin consecuencias fiscales).

---

## Tabla maestra — Deuda con el exterior

| Tipo deuda | Concepto | ¿Fuente argentina? | Condonación | Capitalización |
|---|---|---|---|---|
| **Préstamo** | Capital | ❌ NO | ==Ganancia gravada== en sociedad AR | Pago → ==NO hay retención== (capital no es renta) |
| **Préstamo** | Intereses | ✅ SÍ | ==NO es ganancia== (ya se dedujo como gasto) | Pago → ==SÍ hay retención== 35% |
| **Deuda por servicio** | — | Depende del servicio | ==NO es ganancia== (ya se dedujo como gasto) | Pago → SÍ hay retención si la deuda era de fuente AR |

> ==Regla mnemotécnica==: si **hubo gasto deducido**, la condonación **no es ganancia**. Si **no hubo gasto** (caso del capital del préstamo), la condonación **sí es ganancia**.

---

## Implicancias prácticas

### Antes de elegir el mecanismo

Hacer el análisis fiscal **antes** de proponer el mecanismo:

1. ¿Cuál es la composición del pasivo? (capital del préstamo, intereses, deuda por servicio)
2. ¿Cuánto se dedujo como gasto históricamente?
3. ¿Cuánto correspondería retener si se considera "pago"?

### Cuándo conviene cada opción

| Situación | Recomendación |
|---|---|
| Pasivo es solo capital de un préstamo, sin intereses devengados | **Capitalización** (no hay retención porque capital no es renta) o **reintegro de capital** |
| Pasivo tiene intereses no pagados | **Condonación** (no se grava porque ya se dedujo) **es preferible** a capitalizar (que activaría la retención del 35%) |
| Pasivo por deuda comercial / servicios | **Condonación** (no se grava) |

### Riesgo: tratar mal el mecanismo

Si la empresa capitaliza un pasivo con intereses no pagados sin ingresar el 35% de retención, AFIP puede reclamarla retroactivamente con intereses y multas.

---

## Ejemplo aplicado

**Situación**: filial argentina de multinacional alemana. Tiene PN negativo de USD 500K. La casa matriz le había prestado USD 1M (de los cuales USD 800K son capital y USD 200K son intereses devengados pero no pagados).

**Análisis**:

**Si capitaliza todo (USD 1M)**:
- USD 800K (capital): es pago, pero capital no es renta argentina → no hay retención.
- USD 200K (intereses): es pago, intereses son fuente argentina → ==35% × $200K = $70K de retención==.

**Si condona todo (USD 1M)**:
- USD 800K (capital): no hubo gasto previo → ==ganancia gravada $800K × 30% = $240K==.
- USD 200K (intereses): hubo gasto previo deducido → ==no es ganancia, no se grava==.

**Total**:
- Capitalización: $70K.
- Condonación: $240K.

==En este caso, **capitalizar es más barato**==.

> El ejemplo muestra por qué el análisis depende de la composición del pasivo. La condonación es a veces mejor, a veces peor. Hay que hacer el cálculo cada vez.

---

## Errores comunes

### Error 1 — Asumir que condonar siempre es mejor
NO. Si la deuda es del capital de un préstamo, condonarlo es ganancia gravada al 30%.

### Error 2 — Capitalizar sin retener
La capitalización equivale a pago. Si había intereses de fuente argentina, hay que retener.

### Error 3 — Confundir reintegro con aporte
El reintegro no emite acciones. El aporte normal sí. Tienen tratamiento contable distinto pero ambos recomponen PN.

### Error 4 — No considerar el momento
Estos análisis son válidos si la empresa **todavía tiene tiempo**. Si AFIP ya inició inspección, la flexibilidad se pierde.

### Error 5 — Olvidar la diferencia de cambio acumulada
La pérdida que llevó al PN negativo ya está computada como gasto deducible. Si se condona la deuda, la "ganancia" por la condonación reversea ese gasto. Hay que hacer el seguimiento contable cuidadoso.

---

## Conceptos relacionados

- [[Ganancias - Diferencias de Cambio]] — el origen del problema (devaluación)
- [[Ganancias - Beneficiarios del Exterior]] — la retención del 35% que se activa al capitalizar
- [[Ganancias - Concepto y Optimizacion]] — el mecanismo elegido es decisión estratégica
- [[Teoria de la Fuente vs Balance]] — la condonación como negocio real para PJ
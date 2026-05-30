# Ganancias — Quebrantos

> Tratamiento de las pérdidas fiscales. Cómo se trasladan, en qué plazo y qué tipos hay.

---

## TL;DR

- **Quebranto** = pérdida fiscal (resultado negativo del ejercicio).
- Se puede **trasladar hasta 5 años** hacia adelante para compensar con ganancias futuras.
- A partir del 6to año no se puede usar más → **se pierde**.
- Hay 2 tipos: **generales** (compensan contra cualquier ganancia) y **específicos** (solo contra ganancias del mismo tipo).

---

## Material de origen

- **Material de Lectura #3** — Quebrantos
- **Notas de clase**: 2026-04-10
- **Art. 25 LIG**

---

## Concepto general

Cuando el resultado del ejercicio es **negativo** (gastos > ingresos), no se paga Impuesto a las Ganancias en ese ejercicio. Pero la pérdida no se "tira": se puede usar para compensar ganancias de ejercicios futuros.

### Por qué importa

- Si emprendés un negocio, los primeros años suelen dar quebranto. Esos quebrantos son **activos fiscales** que valen plata en el futuro.
- Si vendés una empresa con quebrantos acumulados, los quebrantos siguen a la empresa (no al accionista) — y son un valor real que se considera en la transacción.
- En decisiones de financiamiento e inversión, los quebrantos son una variable clave.

---

## Reglas del quebranto

### Plazo: 5 años hacia adelante

```
Año 0: Quebranto de $100
Año 1: ganancia $30 → uso $30 del quebranto → quebranto pendiente: $70
Año 2: ganancia $20 → uso $20 → quebranto pendiente: $50
Año 3: pérdida → no uso nada → pendiente: $50
Año 4: ganancia $30 → uso $30 → pendiente: $20
Año 5: ganancia $50 → uso $20 (último año posible) → pendiente: $0
Año 6: ya no hay quebranto del año 0 disponible
```

### No hay carryback

Argentina **no permite** usar quebrantos para "atrás" (carryback). Solo hacia adelante.

### Actualización

Los quebrantos **se actualizan por inflación** (mediante coeficientes definidos por la ley, típicamente RIPTE o índices oficiales).

---

## Quebrantos generales vs específicos

### Quebrantos generales
- Provienen de actividades comunes (ej. operación habitual de la empresa).
- Pueden compensarse contra **cualquier tipo** de ganancia futura.

### Quebrantos específicos
- Provienen de ciertas actividades específicas (definidas por ley).
- Solo pueden compensarse contra ganancias del **mismo tipo**.

### Tipos de quebranto específico (Art. 25 LIG)

| Actividad | Razón de la restricción |
|---|---|
| **Acciones, cuotas partes, valores negociables, monedas digitales (criptomonedas), títulos, bonos, certificados de depósito, FCI, Fideicomisos Financieros** | Para evitar que pérdidas de inversiones financieras compensen actividad operativa |
| **Fuente extranjera** | Solo se compensa con ganancias de fuente extranjera |
| **Derivados financieros sin cobertura** (especulación) | Para distinguir cobertura del negocio de pura especulación. La cobertura del negocio genera quebranto general. |
| **Recursos naturales vivos y no vivos de plataforma continental y zona económica exclusiva** (incluye islas artificiales, instalaciones y estructuras) | Solo contra ganancias netas de fuente argentina |
| **Juegos de azar en casinos** (ruleta, blackjack, póker, etc.) y **apuestas electrónicas** (máquinas de azar, plataformas digitales) | Para que las pérdidas de juego no compensen otros negocios |
| **Inmuebles** | Solo contra ganancias de la misma naturaleza |

> Fuente: Art. 25 LIG. Mnemotécnica: las actividades de mayor riesgo o especulación generan quebrantos específicos para que sus pérdidas no "contaminen" la base imponible de actividades reales.

> **Detalle cobertura vs especulación (derivados)**: una transacción o contrato derivado se considera de **cobertura** si tiene por objeto reducir el efecto de las futuras fluctuaciones en precios o tasas de mercado sobre los bienes, las deudas y los resultados de la actividad económica principal. Si no cumple esa condición, es especulación → quebranto específico.

---

## Caso aplicado — empresa con quebranto específico

**Situación**: empresa A tiene resultado operativo +$200, pero también tiene pérdida por venta de acciones de -$100.

### Si fuera quebranto general
```
Resultado operativo:    +$200
Pérdida por acciones:   -$100
Base imponible:          $100
Impuesto (30%):           $30
```

### Como es quebranto específico
```
Resultado operativo:    +$200 → tributa
Pérdida por acciones:   -$100 → quebranto específico, NO compensa
Base imponible:          $200
Impuesto (30%):           $60
Quebranto específico pendiente: $100 (solo compensa contra futuras ganancias por acciones, en 5 años)
```

> Diferencia: $30 más de impuesto en el año. Si nunca tenés ganancia por acciones, ese quebranto se pierde.

---

## Caso: Bitboc (ítem 5)

Bitboc cede un crédito de $100 al Banco Macry por $90. Pérdida de $10.

**Análisis**:
- ¿Es quebranto general o específico?
- La pérdida proviene de venta/cesión de un valor (un crédito) → posiblemente quebranto específico de valores.
- Aún así, es pérdida real → no hay impuesto sobre esos $10.
- Pero la pérdida solo compensaría futuras ganancias por venta de valores.

---

## Implicancias para decisiones

### Para emprendedores
Los primeros años de pérdida generan quebrantos que valen lo mismo (en términos de protección fiscal futura) que el ahorro del impuesto sobre ganancias equivalentes en el futuro.

### Para holdings
Estructurar negocios para que diferentes actividades estén en diferentes sociedades puede afectar cómo se usan los quebrantos. Tener todo en una sociedad permite compensar entre actividades; tener separadas puede impedirlo.

### Para fusiones y adquisiciones
Una empresa con quebrantos acumulados tiene un activo fiscal. Pero la ley tiene reglas para evitar que se compren empresas solo por sus quebrantos (Art. 78 LIG sobre cambios de control y continuidad de actividad).

---

## Errores comunes

### Error 1 — Asumir que el quebranto es general
Por default es general, pero hay actividades específicas. Si el quebranto viene de acciones, criptos, fuente extranjera, derivados especulativos, juegos o gaming → es específico.

### Error 2 — Olvidar el plazo de 5 años
Si tenés un quebranto del año 2020, en 2026 ya no podés usarlo. Hay que planificar para "usar" los quebrantos antes que venzan, idealmente acelerando ganancias en años donde haya quebrantos cerca de vencer.

### Error 3 — Pensar que se puede usar contra el accionista
Los quebrantos son de la sociedad, no del accionista. Si la sociedad tiene quebrantos, el accionista NO puede usarlos en su declaración personal.

### Error 4 — Asumir que el quebranto se mantiene en una venta de la sociedad
Si la sociedad cambia de control y de actividad, los quebrantos pueden perderse. Hay normas anti-abuso (Art. 78 LIG).

### Error 5 — No considerar la actualización
Los quebrantos se actualizan por inflación. En contextos de alta inflación argentinos, esto puede ser muy significativo.

---

## Conceptos relacionados

- [[Ganancias - Concepto y Optimizacion]] — los quebrantos son parte de la base imponible
- [[Ganancias - Venta y Reemplazo]] — alternativa para diferir impuesto
- [[Ganancias - Sujetos]] — quién tiene los quebrantos
- [[Fallo Cia Tucumana]] — relacionado por evitar quebrantos artificiales
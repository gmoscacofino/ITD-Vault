# Impuesto a los Débitos y Créditos Bancarios (IDyCB)

> Impuesto al movimiento bancario. No grava resultados, grava transacciones. Crédito ≠ costo.

---

## TL;DR

- Impuesto sobre **cada movimiento bancario** (entrada o salida) en cuentas de bancos y fintech.
- **NO grava resultados**, grava **transacciones**.
- **Tasa**: 0,6% por cada débito y 0,6% por cada crédito = 1,2% total por flujo (con variaciones).
- **Cómputo contra Ganancias**: depende del tipo de empresa:
  - **Microempresas**: 30% contra Contribuciones Patronales (límite 15%), Y también 100% contra Ganancias.
  - **Pequeñas MiPyME**: 100% contra Ganancias (0% costo).
  - **Manufacturera mediana tramo I**: 60% contra Ganancias (excedente traslada con 33% a futuros).
  - **Resto**: 33% crédito contra Ganancias, 67% costo.
- ==**REGLA PARA CASOS PRÁCTICOS: tratar SIEMPRE todas las empresas como Resto (33% crédito / 67% costo). No determinar la categoría MiPyME real.**==

---

## Material de origen

- **Material de Lectura #6** — Impuesto a los Débitos y Créditos Bancarios
- **Notas de clase**: 2026-05-08
- **Notas de Lauti (txt)**: sección sobre IDyCB

---

## Concepto

### Qué grava
==Cada movimiento bancario==: cada vez que entra o sale dinero de una cuenta bancaria (o fintech).

### A quién aplica
- Bancos calculan y retienen automáticamente sobre cada movimiento.
- ==Las fintech también aplican el impuesto==. Cualquier entidad de pago electrónico está alcanzada.

### Cómo se cobra
- El banco/fintech aplica el impuesto **directamente** al movimiento.
- El usuario ve el descuento en su resumen.
- No hay que hacer DDJJ propia (el banco lo ingresa).

### Naturaleza distintiva
==No grava sobre resultados sino sobre **movimientos bancarios**==. Esto es importante:
- Una empresa con pérdida fiscal **igual paga** IDyCB.
- Una empresa con muchas transacciones pequeñas paga mucho IDyCB aun con poca ganancia.

---

## La tasa

### Tasa general
- 0,6% en cada **débito** (salida).
- 0,6% en cada **crédito** (entrada).
- Total típico por flujo: **1,2%**.

### Caso especial: cheque
Los cheques pueden tener tasa diferente y mecánicas particulares.

> En la práctica, las tasas pueden variar levemente según el instrumento, pero el orden de magnitud es ~1% por flujo bidireccional.

---

## Cómputo contra Ganancias (clave)

### El sistema no es simple

==El IDyCB se puede usar parcialmente como **crédito** contra Ganancias, según el tipo de empresa==.

### Régimen por tipo de empresa

#### Microempresas

- **30% como pago a cuenta de contribuciones patronales** (con un límite del 15% de las patronales totales).
- **Y también: 100% contra Ganancias** como crédito adicional.
- 0% costo definitivo (todo se recupera entre ambos créditos).

> Las microempresas tienen el beneficio DOBLE: patronales + Ganancias.

#### Pequeñas MiPyME

- **100% contra Ganancias** como crédito.
- 0% costo (todo se recupera contra Ganancias).

> Es el régimen más favorable para quien no califica como microempresa.

#### Manufacturera mediana tramo I

- **60% contra Ganancias** como crédito.
- El excedente no computado puede trasladarse a ejercicios futuros con el régimen del **33%**.

> Es una categoría intermedia entre la pequeña MiPyME (100%) y el resto (33%).

#### Resto de empresas (medianas, grandes)

- **33% contra Ganancias** como crédito.
- **67% es costo**.

### Implicancia
==Para empresas grandes, la mayor parte del IDyCB es **costo definitivo**==. No se recupera.

> Solo las MiPyME pueden recuperarlo en su totalidad. El sistema favorece a las empresas chicas (proporcionalmente).

---

## Certificación MiPyME

### Cómo se obtiene
Argentina tiene un sistema de **certificación MiPyME** que clasifica empresas en:
- Microempresa
- Pequeña empresa
- Mediana empresa Tramo 1
- Mediana empresa Tramo 2
- (Resto de empresas)

### Parámetros de clasificación

La AFIP/Secretaría PyME considera:
- **Cantidad de empleados**.
- **Industria** (sector económico).
- **Facturación anual** (ingresos brutos).

> Hay tablas específicas por sector. Los umbrales se actualizan periódicamente.

### Por qué importa

La certificación MiPyME tiene **múltiples beneficios fiscales**:
- 100% del IDyCB contra Ganancias (mencionado arriba).
- Acceso a planes de financiamiento.
- Plazos extendidos en obligaciones fiscales.
- Otros regímenes preferenciales.

> **No tener certificación MiPyME cuando la empresa califica es un error fiscal con costo significativo**.

---

## Crédito vs Costo (concepto clave)

### Crédito

==Es algo que **reduce** el impuesto a pagar==. Funciona como un descuento.

**Ejemplo**:
- Una empresa debe pagar $100 de Ganancias.
- Tiene $20 de crédito por IDyCB.
- Paga: $100 - $20 = $80.

> El crédito es **dinero recuperado**. Es como si nunca hubiera pagado esa parte del IDyCB.

### Costo

==Es algo que **NO reduce el impuesto** pero **sí reduce la ganancia**==.

**Ejemplo**:
- Una empresa tiene ganancia bruta de $1.000.
- Tiene $20 de IDyCB como costo.
- Ganancia neta: $1.000 - $20 = $980.
- Impuesto sobre $980 (30%): $294.
- Sin IDyCB, hubiera sido sobre $1.000: $300.

> El costo te ahorra **el porcentaje del impuesto** sobre ese monto (no el monto completo). Para $20 de costo, ahorra $20 × 30% = $6. Los otros $14 son pérdida real.

### La diferencia importa MUCHO

```
$100 de IDyCB:
  Como CRÉDITO completo (100%): recuperás $100.
  Como COSTO completo: recuperás $30 (a tasa 30%) y perdés $70.
  
Diferencia: $70 de pérdida real entre uno y otro.
```

> ==Crédito ≠ Costo==. El profesor lo remarca con énfasis. Es uno de los errores más comunes.

---

## Implicancia económica

### Para industria vs servicios

La industria tiene **18% de contribuciones patronales**. Los servicios tienen **25%**. Esta diferencia favorece a la industria.

Pero el IDyCB:
- **Microempresas industriales**: 30% se puede usar como pago a cuenta de contribuciones patronales.
- Como las contribuciones de la industria son 18% (más bajas), el 30% del IDyCB cubre una porción menor de las contribuciones.

> Para una empresa de servicios con 25% de contribuciones, ese 30% del IDyCB representa "más cubierto" que para una industria.

### Resumen efecto

| Tipo empresa | % recuperado | % costo |
|---|---|---|
| Microempresa | 30% patronales + 100% Ganancias | 0% costo |
| Pequeña MiPyME | 100% contra Ganancias | 0% costo |
| Manufacturera mediana tramo I | 60% contra Ganancias | 40% costo (excedente traslada 33%) |
| Mediana / Grande (**Resto** — default prácticos) | 33% crédito contra Ganancias | 67% costo |

---

## Implicancias para decisiones empresariales

### Optimización del cash flow

- Concentrar movimientos para reducir transacciones (menos IDyCB).
- Usar herramientas como compensación entre cuentas en vez de pasaje por banco.

### Mantener certificación MiPyME

- Si la empresa califica, mantener la certificación es prioridad. La diferencia en IDyCB (100% vs 33% de crédito) puede ser significativa.

### Estructuración del flujo

- Las empresas grandes a veces estructuran movimientos para minimizar IDyCB:
  - Pagos directos al proveedor sin pasar por cuenta principal.
  - Uso de cuentas en moneda extranjera (con sus propias reglas).
  - Compensación intra-grupo.

### Diferencia con otros impuestos

- IDyCB es un impuesto "silencioso": se aplica automáticamente, muchos empresarios no lo ven en sus DDJJ.
- Pero el impacto acumulado puede ser significativo (1-2% del flujo total movido).

---

## Errores comunes

### Error 1 — Confundir los regímenes
Las **microempresas** tienen 30% contra contribuciones patronales **más** 100% contra Ganancias (doble beneficio). Las **pequeñas MiPyME** tienen 100% contra Ganancias. Las **manufactureras medianas tramo I** tienen 60% contra Ganancias. Las **medianas y grandes (resto)** solo tienen 33% contra Ganancias.

### Error 2 — Confundir crédito con costo
==Crédito es recuperar el 100% de ese dinero==. Costo es deducir como gasto (recuperás solo el % del impuesto). La diferencia es enorme.

### Error 3 — No certificarse como MiPyME
Si la empresa califica y no se certifica, está dejando dinero en la mesa.

### Error 4 — Olvidar fintech
Las fintech aplican el mismo impuesto. No es exclusivo de los bancos. Usar Mercado Pago, Ualá, etc., no exime del IDyCB.

### Error 5 — Asumir que con pérdida no se paga
Se paga sobre movimientos, no sobre ganancia. Una empresa con pérdida igual paga IDyCB.

---

## Conceptos relacionados

- [[Sistema Tributario Argentino]] — IDyCB en contexto general
- [[Ganancias - Concepto y Optimizacion]] — cómo afecta el crédito vs costo
---

## Casos en el vault donde aparece este concepto

| Caso | Tratamiento | Clave |
|---|---|---|
| [[../../03-Ejercicios/Resueltos-Catedra/Material 10/Caso I - Software Cadbury UK Argentina Uruguay\|Mat 10 · Caso I]] | Débitos (sueldos) + créditos (cobro) | Régimen Resto: 67% costo + 33% crédito |
| [[../../03-Ejercicios/Resueltos-Catedra/Material 10/Caso II - ARGSecurity Consultoria BMV Argentina\|Mat 10 · Caso II]] | Por opción varía (sueldos vs proveedor exterior) | Incluir todos los movimientos bancarios reales |
| [[../../03-Ejercicios/Resueltos-Catedra/Material 11/Caso I - Franquicia Detroit Brasil\|Mat 11 · Caso I]] | Crédito sobre cobro; 67% costo + 33% crédito | Régimen Resto confirmado |
| [[../../04-Parciales-Anteriores/Diciembre 2025/Resolucion\|Parcial Dic 2025]] | Ingresos + egresos (incl. IVA a ingresar + IVA sustituto) | Los pagos de IVA a AFIP son egresos bancarios reales → generan IDyCB |
| [[../../04-Parciales-Anteriores/Recuperatorio 2do Cuatrim 2025/Resolucion\|Recuperatorio 2025]] | Ingresos (cobro neto 378k); egresos incluyen IVA Gordon recuperable | IVA recuperable = egreso real = base IDyCB aunque no sea costo P&L |

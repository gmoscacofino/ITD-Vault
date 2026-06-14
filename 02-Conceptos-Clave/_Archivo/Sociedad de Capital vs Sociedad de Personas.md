# Sociedad de Capital vs Sociedad de Personas

> Las dos grandes categorías de sociedades en la teoría jurídica, con tratamientos fiscales muy distintos especialmente en USA.

---

## TL;DR

| Concepto | Sociedad de Capital | Sociedad de Personas |
|---|---|---|
| **Responsabilidad del socio** | Limitada al capital aportado | Ilimitada (responde con patrimonio personal) |
| **Quién tributa Ganancias** | La sociedad como ente | Suele recaer en los socios (pass-through) |
| **Equivalente AR** | SA, SRL | Sociedad de Hecho, Soc. Colectiva |
| **Equivalente USA** | C-Corporation | LLC (por default) |
| **Tratamiento fiscal AR** | Mismo tratamiento que cualquier PJ | Suele tributar como PH (transparente) |

> En Argentina, SA y SRL tributan igual. La distinción importa más en USA.

---

## Material de origen

- **Material de Lectura #2** — Sujetos
- **Notas de clase**: 2026-03-20
- **Notas de Lauti (txt)**: sección sobre SA, LLC y K-1

---

## Sociedad de Capital

### Características jurídicas
- El socio aporta capital y su responsabilidad **se limita a ese aporte**.
- La sociedad es una **persona jurídica separada** del socio.
- Si la sociedad va a la quiebra, los socios pierden solo lo aportado.
- Tiene órganos propios (asamblea, directorio).

### Tratamiento fiscal típico
La sociedad **tributa por sus ganancias** como ente independiente. Cuando distribuye dividendos, el socio recibe (y puede pagar adicional por dividendos).

### Ejemplos
- **Argentina**: SA, SRL (ambas tributan igual).
- **USA**: C-Corporation.
- **Internacional**: Corporation, GmbH (Alemania), Société Anonyme (Francia).

---

## Sociedad de Personas

### Características jurídicas
- El socio **responde con su patrimonio personal** (ilimitada, solidaria o subsidiaria según el tipo).
- La sociedad NO tiene la misma "barrera" entre sociedad y persona.
- Si la sociedad se endeuda, el acreedor puede ir contra los bienes personales del socio.

### Tratamiento fiscal típico — el principio de transparencia (pass-through)
La sociedad **NO paga Ganancias** como ente. En su lugar:
- Los ingresos y gastos se atribuyen **directamente a los socios** según su participación.
- Cada socio incluye su parte en su DDJJ personal.
- Tributa al nivel del socio, según su jurisdicción y situación.

### Ejemplos
- **Argentina**: Sociedad de Hecho, Sociedad Colectiva, ciertas modalidades de Soc. Civil.
- **USA**: LLC (por default), Partnerships.
- **Otros**: Limited Partnership, General Partnership.

---

## El caso USA — Corporation vs LLC

### C-Corporation

- **Tributa como ente**: paga **federal corporate tax** (~21% federal + estatal variable).
- Al distribuir dividendos, los accionistas pagan **dividend tax** (~15%-37% según ingresos).
- **Doble imposición**: corporation + accionista.

**Características**:
- Estructura formal.
- Necesita asambleas, directorio, registro de acciones.
- Mayor complejidad administrativa.
- Mejor para empresas grandes con muchos socios.

### LLC (Limited Liability Company)

Tiene **3 modalidades fiscales posibles**:

#### Modalidad 1: Pass-through (default)

- **Tributación**: cada socio paga directamente según su parte.
- **Implementación**: la LLC emite **K-1** a cada socio anualmente informando su parte.
- Es la modalidad por default para LLC con 2+ socios.

#### Modalidad 2: Disregarded entity (LLC con 1 solo socio no residente fuera de USA)

- **Tributación**: la LLC se "ignora" para efectos fiscales federales.
- **Aplicación**: solo si:
  - 1 socio único
  - Socio NO residente USA
  - Operación se hace **fuera de USA**

- **Efecto**: no paga Federal income tax. El único socio paga solo en su jurisdicción de residencia.

> ==Caso típico de uso==: un argentino que quiere prestar servicios de software a clientes en USA. Si arma una LLC con él como único socio, prestando servicios al exterior (fuera de USA), la LLC es disregarded → no paga federal income tax. Paga solo en Argentina.

#### Modalidad 3: Elección C-Corp (opt-in)

- La LLC **elige** voluntariamente tributar como Corporation.
- Se usa cuando los socios prefieren la complejidad de Corp para acceder a beneficios específicos (ej. ciertos planes de pensión, deducciones específicas).

### Tabla comparativa

| Aspecto | C-Corp | LLC pass-through | LLC disregarded |
|---|---|---|---|
| Tributación | Doble (corp + accionista) | Una sola vez (en el socio) | Solo en jurisdicción del socio |
| K-1 emitido | No | Sí | No (es transparente) |
| Quién paga | La corporación + accionista al distribuir | El socio (cada uno) | El socio único |
| Recomendado por contadores | Para empresas grandes | Para emprendedores con varios socios | Para argentinos sin operación en USA |
| Federal income tax | Sí | El socio | No (en jurisdicción del socio) |

---

## El caso argentino

### SA vs SRL: para Ganancias, son lo mismo

En Argentina ambas:
- Son sociedades de capital (responsabilidad limitada al aporte).
- Tributan como **PJ** (teoría del balance, criterio devengado).
- Tasa escalonada 25/30/35% + 7% al accionista por dividendos.

> La elección entre SA y SRL es **societaria**, no fiscal:
> - SA: más formal, mejor para muchos socios o salir a oferta pública.
> - SRL: más simple, mejor para emprendimientos chicos o familiares.

### Sociedades de personas en AR

Son tributariamente **transparentes**:
- Los socios incluyen su parte en su DDJJ personal.
- No hay "doble imposición" porque la sociedad no paga, paga el socio directamente.

### Casos especiales: fideicomisos y FCI

Tienen reglas propias según su tipo y composición. Ver [[Fideicomiso]].

---

## Implicancia para decisiones empresariales

### Elegir tipo societario para un emprendimiento

**En USA**:
- ¿Tenés operaciones en USA? Tal vez Corp o LLC pass-through.
- ¿Solo querés facturar al exterior desde USA sin operar allá? LLC disregarded.

**En AR**:
- SA o SRL: cualquiera, son fiscalmente iguales. Elegí según tu necesidad legal.
- Sociedad de Hecho: solo si querés transparencia (tributa en cada socio).

### Para argentinos prestando servicios al exterior

Considerar LLC en USA como vehículo:
- Si es 1 solo socio y no operás en USA → disregarded → no pagás IRS.
- Pagás solo en AR como residente (por renta mundial).

> Atención: la AFIP puede invocar normas anti-abuso si la estructura es claramente artificial.

---

## El K-1 (USA)

### Qué es

El **K-1** es el formulario que una sociedad de personas o LLC pass-through envía a cada socio en USA. Informa:
- La parte del socio en los ingresos, gastos, créditos y deducciones.
- Cuánto le corresponde declarar individualmente.

### Por qué importa
- Los socios necesitan el K-1 para preparar su DDJJ individual.
- Si la LLC tiene muchos socios, hay K-1 para cada uno.
- Genera complejidad administrativa pero permite transparencia.

---

## Errores comunes

### Error 1 — Tratar a la LLC como si siempre fuera transparente
NO. La LLC tiene 3 modalidades posibles (pass-through, disregarded, opt-in Corp). Hay que mirar la situación específica.

### Error 2 — Asumir que SA y SRL son distintas en AR para Ganancias
NO. En Argentina son lo mismo fiscalmente. La diferencia es jurídica.

### Error 3 — Usar disregarded entity para operación dentro de USA
La modalidad disregarded requiere que el negocio se haga **fuera de USA**. Si operás en USA, no aplica.

### Error 4 — Olvidar la renta mundial argentina
Aunque la LLC en USA sea disregarded y no pague allí, vos como residente argentino seguís siendo gravado por renta mundial en AR.

### Error 5 — Confundir responsabilidad limitada con tributación
Una sociedad puede tener responsabilidad limitada pero ser transparente fiscalmente (como la LLC pass-through). No son lo mismo.

---

## Conceptos relacionados

- [[Ganancias - Sujetos]] — desarrollo de sujetos en LIG
- [[Renta Mundial vs Territorialidad]] — afecta a los socios argentinos de LLC
- [[Fideicomiso]] — otro vehículo con reglas propias
- [[Ganancias - Tasas]] — cómo paga cada tipo
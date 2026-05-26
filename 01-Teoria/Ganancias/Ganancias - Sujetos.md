# Ganancias — Sujetos

> Quiénes son contribuyentes del Impuesto a las Ganancias. Va más allá de "personas y empresas": hay sujetos que solo existen para el derecho tributario.

---

## TL;DR

Son sujetos del impuesto:
- **Personas Humanas (PH)** — usan teoría de la fuente, criterio percibido (en general)
- **Personas Jurídicas (PJ)** — sociedades, usan teoría del balance, criterio devengado
- **Sujetos especiales** — fideicomisos, fondos comunes de inversión, establecimientos permanentes, LLC

Para algunos sujetos especiales hay reglas específicas de quién paga (fideicomisos), o cómo se computa (LLC).

---

## Material de origen

- **Material de Lectura #2** — Sujetos del Impuesto
- **Notas de clase**: 2026-03-20
- **Resumen Claude**: 2026-03-13 sección 8
- **Caso disparador**: Fideicomiso de construcción, LLC en USA

---

## Los grandes sujetos

### Personas Humanas
- Aplican **teoría de la fuente**
- Distinguen entre 4 categorías de renta (1ra/2da/3ra/4ta)
- Criterios de imputación variados según categoría (devengado o percibido)

### Personas Jurídicas (sociedades)
- Aplican **teoría del balance**
- Solo tienen renta de **3ra categoría**
- Criterio de imputación: **devengado** (sin excepciones generales)

### Sujetos especiales
- **Fideicomisos**: dependen del tipo
- **Fondos Comunes de Inversión (FCI)** cerrados: pagan como sociedad
- **Establecimientos permanentes (EP)**: filiales/sucursales de empresas extranjeras
- **Sociedades de personas extranjeras (LLC)**: distintos tratamientos según estructura
- **Asociaciones civiles y fundaciones**: pueden ser exentas con requisitos

---

## SA vs SRL en Argentina

En Argentina **ambas tributan de la misma manera**. La elección entre SA y SRL es por temas societarios, no fiscales.

En cambio, **en USA la distinción es central**:

### Corporation (equivalente a SA)
- **Sociedad de capital**.
- El socio responde solo por su aporte de capital.
- La sociedad paga su impuesto (federal corporate tax).
- El socio paga adicional al recibir dividendos.

### LLC (equivalente a SRL)
- **Sociedad de personas**.
- El socio puede responder por las obligaciones de la sociedad.
- Tratamiento fiscal distinto según cantidad de socios:

| LLC | Socios | Tratamiento fiscal |
|---|---|---|
| **Disregarded entity** | 1 socio único, no residente, negocio fuera de USA | LLC se ignora. No paga IRS. El socio paga en su jurisdicción. |
| **Pass-through** (default) | 2+ socios | Se emite K-1 a cada socio. Cada socio paga individualmente. La LLC presenta declaración jurada pero no paga ella. |
| **Elección C-Corp** | Cualquier nro de socios | La LLC elige tributar como Corporation. Tributa ella + dividendos. |

> **Caso típico de uso**: una persona argentina que quiere prestar servicios de tecnología en EEUU. Si arma una LLC con un solo socio (él mismo), no residente, prestando servicios fuera de USA → **disregarded entity** → no paga impuesto federal en USA. Paga solo en Argentina como residente argentino.

> Los contadores recomiendan la LLC porque es más simple administrativamente que una Corporation.

---

## Fideicomiso (Trust)

### Estructura

Un fideicomiso tiene **al menos 3 personas y típicamente 4**:

| Rol | Función | Restricciones |
|---|---|---|
| **Fiduciante** | Transfiere bienes al fideicomiso (se "desapodera") | NO puede ser fiduciario |
| **Fiduciario** | Administra los bienes en nombre del fideicomiso | NO puede ser beneficiario |
| **Beneficiario** | Recibe los frutos del fideicomiso durante su vigencia | — |
| **Fideicomisario** | Recibe los bienes remanentes al vencimiento | Puede ser el mismo fiduciante |

> Ejemplo histórico (Roma antigua): el hombre que va a la guerra deja a su esposa como fiduciaria. Si fallece, los hijos son fideicomisarios. Si vuelve, él mismo es fideicomisario y recupera todo.

**Plazo máximo del fideicomiso**: 30 años.

### Tipos de fideicomiso

Hay solo 2 tipos para efectos impositivos:

1. **Fideicomiso financiero** — bajo organismo de control (CNV)
2. **Los demás** — el resto (de garantía, de administración, de construcción al costo, etc.)

### Quién tributa Ganancias del fideicomiso

| Situación | Quién paga |
|---|---|
| **Fideicomiso financiero** | El fideicomiso (en cabeza del fiduciario), **siempre** |
| **Fiduciante = Beneficiario, residente argentino** | El **fiduciante** (tributa directamente por las rentas del fideicomiso) |
| **Fiduciante = Beneficiario, NO residente** | El **fideicomiso** (en cabeza del fiduciario) |
| **Fiduciante ≠ Beneficiario** | El **fideicomiso** (en cabeza del fiduciario), tributa como Persona Jurídica (Art. 69) |

### Caso mixto (residentes + no residentes)

Si hay fiduciantes-beneficiarios residentes y no residentes mezclados → pueden optar por tributar **todos como fideicomiso** (opción que dura 5 años).

### Caso aplicado — Fideicomiso de construcción al costo

- 80% fiduciantes-beneficiarios residentes argentinos.
- 20% fiduciantes-beneficiarios residentes uruguayos.

**Análisis**:
- Los 80% residentes pueden tributar como fiduciantes individuales (cada uno por su parte).
- Los 20% uruguayos NO pueden, porque son no residentes → en cabeza del fideicomiso.
- O TODOS pueden optar por tributar como fideicomiso (opción 5 años).

---

## Asociaciones civiles y fundaciones — Exención del Art. 20 inc. f)

Están **exentas** de Ganancias siempre que:
1. Las ganancias se destinen a los fines de su creación
2. NO se distribuyan entre los socios
3. NO exploten espectáculos públicos, juegos de azar o carreras de caballos

**Límite adicional**: la exención se pierde si se pagan a directivos importes superiores al 50% del promedio de las 3 mejores remuneraciones del personal administrativo.

> Lógica: evitar que se monten ONG fachada para distribuir ganancias disfrazadas de sueldos altos a los directivos.

---

## Quantum: cómo calcula cada sujeto

| Sujeto | Cómo calcula |
|---|---|
| PJ (sociedad) | Renta gravada × tasa escalonada (25/30/35%) + 7% al distribuir dividendos |
| PH | Renta gravada × escala progresiva (5-35% según monto, con mínimo no imponible y deducciones) |
| Fideicomiso (cuando tributa) | Igual que PJ |
| LLC (cuando se pasa a Argentina) | Como su socio según residencia |

> Ver [[Ganancias - Tasas]] para detalle.

---

## Errores comunes

### Error 1 — Aplicar teoría de la fuente a una sociedad
Una sociedad nunca usa teoría de la fuente, siempre teoría del balance. Esto es por su naturaleza jurídica de sujeto que se constituye para hacer negocios.

### Error 2 — Pensar que LLC es siempre transparente fiscalmente
La LLC default es pass-through, pero puede elegir tributar como C-Corp. Y el caso de disregarded entity es muy específico (1 solo socio no residente, negocio fuera de USA).

### Error 3 — Confundir los roles del fideicomiso
- El fiduciante NUNCA puede ser fiduciario.
- El fiduciario NUNCA puede ser beneficiario.
- El fideicomisario SÍ puede ser el mismo fiduciante.

### Error 4 — Asumir que el fideicomiso siempre paga
NO. Si el fiduciante = beneficiario residente, paga el fiduciante directamente. El fideicomiso solo paga cuando es financiero o cuando hay no residentes mezclados.

### Error 5 — Confundir SA con SRL en Argentina
Para Ganancias, ambas son lo mismo. La distinción solo aplica en USA y otras jurisdicciones.

---

## Conceptos relacionados

- [[Sociedad de Capital vs Sociedad de Personas]] — diferencia jurídica y fiscal
- [[Fideicomiso]] — desarrollo completo del concepto
- [[Ganancias - Objeto]] — qué se grava según el sujeto
- [[Ganancias - Tasas]] — cuánto paga cada sujeto
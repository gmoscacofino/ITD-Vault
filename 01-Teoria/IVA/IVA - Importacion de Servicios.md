# IVA — Importación de Servicios

> Cuando una empresa argentina contrata un servicio prestado desde el exterior y usado en AR, debe ingresar IVA como responsable sustituto.

---

## TL;DR

- Servicio prestado **en el exterior** + uso económico **en AR** + cliente **RI argentino** = importación de servicios.
- La empresa AR actúa como **responsable sustituto**: ingresa el IVA al fisco por cuenta del proveedor extranjero.
- Al mes siguiente, computa ese IVA como **CF** → es **neutro económicamente**.
- Mecánica del Art. 1 inc. d LIVA y Art. 4 inc. h LIVA.

---

## Material de origen

- **Material de Lectura #4** — Importación de Servicios
- **Notas de clase**: 2026-04-17
- **Art. 1 inc. d) LIVA**
- **Art. 4 inc. h) LIVA** — responsable sustituto

---

## Concepto

### Los 3 requisitos para que aplique

1. **Lugar de prestación del servicio**: fuera de Argentina.
2. **Lugar de utilización económica**: Argentina (uso inmediato).
3. **Cliente**: Responsable Inscripto en AR (no es consumidor final).

> Si alguno de los 3 falla, NO es importación de servicios.

### Distinción con servicio en territorio AR

| Caso | Lugar prestación | Lugar utilización | Cliente | Tratamiento |
|---|---|---|---|---|
| Servicio prestado EN AR | AR | AR | Cualquiera | Servicio gravado normalmente |
| Importación de servicios | Exterior | AR | RI argentino | Responsable sustituto |
| Exportación de servicios | AR | Exterior | No residente | Exento (no gravada) |
| Servicios digitales B2C | Exterior | AR | Consumidor final | Categoría 5, percepción por tarjeta |

---

## La mecánica del responsable sustituto

### El problema
El proveedor del exterior NO es sujeto del IVA en Argentina. El fisco argentino no tiene cómo cobrarle directamente. Pero el servicio se está consumiendo en AR.

### La solución
La empresa argentina (cliente) actúa como **sustituto** del proveedor extranjero:
1. Le paga al proveedor el monto pactado.
2. **Ingresa el IVA por cuenta del proveedor extranjero** al fisco AR.
3. Al mes siguiente, computa ese IVA como Crédito Fiscal en su propia DDJJ.

### Resultado: neutro económicamente

```
Mes 1:
  Empresa AR paga USD 100.000 al proveedor UK.
  Empresa AR ingresa USD 21.000 (21%) al fisco AR como sustituto.
  Costo total para AR: USD 121.000 (out of pocket).
  
Mes 2 (DDJJ del mes 1):
  Empresa AR computa USD 21.000 como CF en su DDJJ.
  Si tiene DF suficiente, lo absorbe inmediatamente.
  Si no, genera saldo técnico a favor (recuperable contra DF futuro).
```

> El IVA es **financieramente** un costo temporal, pero **económicamente** neutro.

---

## Cuándo el IVA por importación de servicios NO es neutro

### Si la actividad del cliente AR es EXENTA o NO GRAVADA

Si la empresa AR usa el servicio importado en una actividad que ella misma no grava con IVA (ej. una entidad financiera con servicios financieros exentos), el CF del importación de servicios **NO se puede recuperar**.

→ El IVA se convierte en **costo** para la empresa AR.

---

## Cómo identificar "utilización económica" en AR

### Concepto
La "utilización económica" significa **dónde se aprovecha el servicio**, no dónde se entrega o factura.

### Casos típicos

**Servicio de asesoramiento para una decisión que se ejecuta en AR**:
- Una consultora inglesa asesora a una empresa argentina sobre cómo expandirse en AR.
- Lugar de prestación: UK.
- Lugar de utilización: AR (el asesoramiento se aplica acá).
- → Importación de servicios, gravado.

**Servicio de asesoramiento para una decisión que se ejecuta afuera**:
- Una consultora inglesa asesora a una empresa argentina sobre cómo expandirse en Uruguay.
- Lugar de prestación: UK.
- Lugar de utilización: Uruguay.
- → NO es importación de servicios en AR. NO está gravado.

---

## Ejemplo aplicado — empresa UK (Caso 1 Material 7)

**Datos**:
- Empresa argentina contrata empresa UK por servicios técnicos.
- Los empleados de UK trabajan **EN Argentina** durante 3 meses.
- Pago pactado: USD 175.000 netos.

### Análisis del IVA

**Cuestión 1**: ¿Es importación de servicios o servicio en AR?
- Los empleados trabajan EN AR (no en UK).
- Por lo tanto: NO es importación de servicios (en sentido estricto del Art. 1 inc. d).
- Es un **servicio prestado en territorio AR por un no residente**.

**Cuestión 2**: ¿Quién es responsable sustituto?
- Por el Art. 4 inc. h LIVA, el contratante argentino actúa como sustituto.
- La empresa AR ingresa el IVA.

### Cálculo del IVA

```
Bruto Ganancias (gross-up al 31,5%): USD 255.474,45
IVA (21% sobre el bruto):            USD 53.649,63

La empresa AR:
  - Paga al proveedor UK:          USD 175.000 (neto)
  - Ingresa al fisco AR (GAN):      USD 80.474,45 (retención)
  - Ingresa al fisco AR (IVA):      USD 53.649,63 (responsable sustituto)
  - Total out of pocket:            USD 309.124,08
  
Al mes siguiente:
  - Computa CF (IVA):              USD 53.649,63
  - Si tiene DF que cubra, el IVA es neutro
```

> Ver [[Gross-up]] y [[Ganancias - Beneficiarios del Exterior]] para Ganancias paralelo.

---

## Distinción crítica con servicios digitales B2C

### Importación de servicios (Art. 1 inc. d)
- Cliente: RI argentino.
- Mecanismo: responsable sustituto.
- B2B.

### Servicios digitales (Art. 1 inc. e, reforma 2018)
- Cliente: consumidor final argentino.
- Mecanismo: percepción por intermediarios financieros (tarjetas).
- B2C.

> Si tu cliente es un RI argentino, usá el régimen de responsable sustituto. Si es consumidor final, aplica el régimen de servicios digitales.

---

## Errores comunes

### Error 1 — Olvidar el responsable sustituto
Cualquier servicio del exterior usado en AR requiere actuar como responsable sustituto. No hacerlo es incumplimiento.

### Error 2 — Pensar que el IVA es costo
Es neutro económicamente si el cliente es RI con DF suficiente. Solo es costo si la actividad propia es exenta.

### Error 3 — Confundir lugar de prestación con lugar de utilización
El lugar de prestación es donde el proveedor hace el trabajo. El lugar de utilización es donde el cliente lo aprovecha. Para importación de servicios, lo que importa es la **utilización**.

### Error 4 — Aplicar a B2C
Si tu cliente argentino es consumidor final (no RI), no es importación de servicios sino servicios digitales (régimen distinto).

### Error 5 — Calcular IVA sobre el neto
El IVA en responsable sustituto se calcula sobre el **bruto** (después del gross-up de Ganancias, si lo hay), no sobre el neto pactado.

---

## Conceptos relacionados

- [[IVA - Objeto]] — categoría 4 del objeto
- [[IVA - Sujeto]] — responsable sustituto
- [[IVA - Servicios Digitales B2C]] — el régimen para B2C
- [[Ganancias - Beneficiarios del Exterior]] — retención de Ganancias en paralelo
- [[Gross-up]] — cálculo cuando se asume el costo
---

## Casos en el vault donde aparece este concepto

| Caso | Situación | Consecuencia |
|---|---|---|
| [[../../03-Ejercicios/Resueltos-Catedra/Material 07/Caso 1 - Empresa UK Presta en Argentina\|Mat 07 · Caso 1]] | Empresa UK presta en AR → RI actúa como sustituto | CF al mes siguiente; neutro económicamente |
| [[../../03-Ejercicios/Resueltos-Catedra/Material 10/Caso II - ARGSecurity Consultoria BMV Argentina\|Mat 10 · Caso II]] | Empresa uruguaya, utilización en AR | Sustituto 17.850 > DF 17.355 → saldo a favor |
| [[../../03-Ejercicios/Resueltos-Catedra/Material 10/Caso III - DevArg CRM Empresa Peruana\|Mat 10 · Caso III]] | Empresa peruana → IVA AR como sustituto (neutro) + IVA peruano (costo) | Distinguir: AR = recuperable; extranjero = costo real |
| [[../../03-Ejercicios/Resueltos-Catedra/Material 11/Caso II - Telefonia IP Exencion IVA\|Mat 11 · Caso II]] | Empresa deja de ser RI → obligación de sustituto desaparece | IVA del exterior ya NO es costo ni obligación |
| [[../../04-Parciales-Anteriores/Diciembre 2025/Resolucion\|Parcial Dic 2025]] | A3: proveedor brasilero, 25% uso en AR | Sustituto proporcional: 42.000 × 25% × 21% = 2.205 |
| [[../../04-Parciales-Anteriores/Recuperatorio 2do Cuatrim 2025/Resolucion\|Recuperatorio 2025]] | A1: Gordon graba en AR → sustituto 42.531,65 | CF recuperable → no costo P&L, pero sí necesidad financiera |

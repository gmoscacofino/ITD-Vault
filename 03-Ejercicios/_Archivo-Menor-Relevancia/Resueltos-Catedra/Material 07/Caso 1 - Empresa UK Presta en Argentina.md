# Material 07 — Caso 1: Empresa UK presta en Argentina (gross-up + IVA)

> Impuestos: [[Ganancias - Beneficiarios del Exterior]], [[Gross-up]], [[IVA - Importacion de Servicios]]
> Status: ✅ Validado en clase

---

## Enunciado

El dueño de una empresa de tecnología residente fiscal argentina contrata una empresa residente fiscal de UK para procesar información de redes sociales. El contrato indica expresamente que el servicio **NO comprende asesoramiento**. La empresa de UK enviará 2 empleados que trabajarán **en Argentina** durante 3 meses. Presupuesto: **USD 175.000**. La empresa argentina debe hacerse cargo de los impuestos que correspondan.

**¿Cuál será el costo final del servicio?**

---

## Conceptos involucrados

- [[Ganancias - Beneficiarios del Exterior]] — Art. 93 LIG
- [[Ganancias - Fuentes Especificas]] — inc. h) servicios técnicos sin asesoramiento
- [[Gross-up]]
- [[IVA - Importacion de Servicios]] — responsable sustituto

---

## Resolución — Ganancias

Los empleados trabajan **físicamente en Argentina** → ==fuente argentina== (Art. 5 LIG).
La empresa de UK es no residente → tributa solo sobre fuente argentina. La empresa argentina actúa como **agente de retención** con carácter de pago único y definitivo.

El contrato dice que NO hay asesoramiento → **Art. 93 inc. h) LIG** (servicios técnicos sin asesoramiento):
- Ganancia neta presumida: **90%**
- Tasa efectiva: 90% × 35% = ==**31,5%**==

Como la empresa argentina asume los impuestos, hay que hacer **gross-up** para que UK reciba USD 175.000 netos:

| Concepto | Cálculo | Resultado |
|---|---|---|
| Monto bruto (gross-up) | 175.000 / (1 − 0,315) | **USD 255.474,45** |
| Retención Ganancias | 255.474,45 × 31,5% | **USD 80.474,45** |
| Neto recibido por UK | 255.474,45 − 80.474,45 | **USD 175.000** ✓ |

## Resolución — IVA

Los empleados prestan el servicio físicamente en Argentina → **Art. 4 inc. h) Ley IVA**: la empresa argentina es **responsable sustituto** → debe ingresar el IVA.

El IVA ingresado se computa como **crédito fiscal** al mes siguiente → es ==económicamente neutro== (solo genera costo financiero por el adelanto de ~30 días).

| Concepto | Cálculo | Resultado |
|---|---|---|
| Base imponible | USD 255.474,45 | |
| IVA (21%) | 255.474,45 × 21% | **USD 53.649,63** |
| Efecto económico | Se recupera como CF al mes siguiente | ==**NEUTRO**== |

---

## Respuesta final

| Concepto | Monto |
|---|---|
| Pago neto a UK | USD 175.000 |
| Retención Ganancias (a cargo empresa AR) | USD 80.474,45 |
| ==**Costo económico real**== | ==**USD 255.474,45**== |
| IVA responsable sustituto | USD 53.649,63 → NEUTRO (se recupera como CF) |

---

## Por qué este ejercicio

Integra los 3 conceptos críticos para operaciones con beneficiarios del exterior:
1. Identificar la **fuente** (acá: argentina, porque trabajan físicamente en AR).
2. Aplicar la **tasa efectiva correcta** del Art. 93 (no 35% pleno, sino 31,5% por presunción del 90%).
3. **Gross-up** correcto cuando se pacta neto (dividir por (1 − tasa), no sumar).
4. Reconocer el **responsable sustituto** del IVA.

==Error típico==: aplicar 35% en vez de 31,5%, o sumar la retención al neto en vez de hacer gross-up.

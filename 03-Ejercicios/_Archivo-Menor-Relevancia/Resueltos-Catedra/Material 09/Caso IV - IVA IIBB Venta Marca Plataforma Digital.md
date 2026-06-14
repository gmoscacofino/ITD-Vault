# Material 09 — Caso IV: IVA e IIBB — Venta de marca + desarrollo plataforma digital

> Impuestos: [[IVA - Controversias del Objeto]], [[IIBB - Hecho Imponible]], [[IVA - Exportaciones]], [[IIBB - Exenciones y No Alcanzados]]
> Status: ✅ Validado en clase

---

## Enunciado

CEO de empresa de tecnología argentina.

**(a) Venta de marca "Armazón":** marca registrada en 2016 para un proyecto de venta de hardware suspendido en 2017 (nunca ejecutado). Comprador del exterior quiere adquirirla. Tratamiento en IVA e IIBB.

**(b) Desarrollo de plataforma digital para fast food del exterior (Mc Callister):** contrato exclusivo 2022-2023, USD 20M para 2 años. Margen: 2% de las ventas. El trabajo se desarrolla totalmente en el exterior. Uso: 40% en el exterior, 60% en Argentina. Alícuota IIBB servicios de desarrollo de software: 5%. Analizar conveniencia considerando solo IVA e IIBB.

---

## Conceptos involucrados

- [[IVA - Controversias del Objeto]] — cesión definitiva de marca: NO gravada sin ambigüedad
- [[IIBB - Hecho Imponible]] — habitualidad: venta de intangible nunca afectado al ciclo comercial
- [[IVA - Exportaciones]] — exportación parcial: % de utilización económica en el exterior
- [[IIBB - Exenciones y No Alcanzados]] — exportación de servicios: exenta solo en la porción efectivizada en el exterior

---

## Resolución

### (a) Venta de marca "Armazón"

**IVA: NO gravada.**

| Operación | Tratamiento IVA | Certeza |
|---|---|---|
| Franquicia (cesión temporal + servicio) | Gravada | Sin dudas — Ley IVA Art. 3 |
| Cesión temporal de marca sin servicio | Contingente | DR pretende gravarla; la Ley no la incluye |
| **Venta de marca (cesión definitiva)** | **NO gravada** | **Sin dudas — ni Ley ni DR la incluyen** |

> Fuente: **Lectura 4 — Controversias Objeto, Cesión de Derechos**: *"VENTA DE LA MARCA (CESIÓN DEFINITIVA) — ACÁ NO HAY DUDAS, PORQUE TANTO LA LEY COMO EL DECRETO REGLAMENTARIO NO INCLUYEN DENTRO DEL OBJETO DEL IVA A LA TRANSFERENCIA DEFINITIVA DE DERECHOS."*

La venta de "Armazón" es una cesión definitiva → ==NO alcanzada por IVA, sin ambigüedad==.

**IIBB: NO gravada.**

La marca nunca integró el proceso productivo habitual de la empresa (proyecto suspendido en 2017, nunca ejecutado). La habitualidad se determina por la índole de las actividades y el objeto de la empresa.

> Fuente: **Lectura 8 — IIBB Habitualidad**: *"La habitualidad está determinada por: la índole de las actividades que dan lugar al hecho imponible, el objeto de la empresa, profesión o locación, y los usos y costumbres de la vida económica."*

==La venta de la marca es un hecho aislado que no corresponde al objeto habitual de una consultora tecnológica.== La marca puede asimilarse a un activo intangible nunca afectado al ciclo comercial.

==La venta de la marca NO está alcanzada por IVA ni por IIBB.==

---

### (b) Desarrollo de plataforma para Mc Callister

> [!warning] Clase: resuelto con limitaciones
> Este caso fue marcado como "MAL HECHO EN CLASE" en las notas. La resolución que sigue refleja los criterios correctos aplicados al enunciado.

**Configuración del caso:**

| Variable | Valor |
|---|---|
| Precio total | USD 20.000.000 |
| Margen 2% | USD 400.000 |
| Lugar de prestación | Exterior |
| Uso en el exterior | 40% |
| Uso en Argentina | 60% |

**Regla clave:** se presta en el exterior pero el 60% se utiliza económicamente en Argentina. La exportación de servicios solo aplica a la porción efectivizada en el exterior.

**IIBB:**
- Porción usada en AR (60%): gravada al 5%
- Porción usada en el exterior (40%): exenta (exportación de servicios)

```
IIBB (costo) = 20.000.000 × 60% × 5% = USD 600.000
```

**IVA:**
- El servicio se presta en el exterior → en principio fuera del objeto del IVA argentino
- Pero el 60% se utiliza económicamente en Argentina → esa porción podría estar gravada
- El cliente es del exterior → probablemente no haya CF computable para neutralizarlo

```
IVA (puede ser costo) = 20.000.000 × 60% × 21% = USD 2.520.000
```

**Resultado:**
```
Margen bruto:   400.000
IIBB:          (600.000)
Resultado:     (200.000) — YA CON IIBB SOLO HAY PÉRDIDA
```

==**NO CONVIENE aceptar el contrato.** Ya solo con IIBB el margen del 2% (USD 400.000) es superado por el costo de IIBB (USD 600.000). El IVA podría agravar aún más la situación.==

---

## Por qué este ejercicio

1. **Cesión definitiva de marca**: caso emblema de NO alcanzado en IVA sin zona gris.
2. **Habitualidad en IIBB**: una empresa que vende un activo aislado que nunca usó no genera hecho imponible en IIBB.
3. **Exportación parcial**: cuando el servicio se usa en parte en AR y en parte en el exterior, los impuestos aplican **proporcionalmente** al uso local.
4. **Margen vs carga impositiva**: con márgenes bajos, IIBB puede ser mayor que la utilidad → hacer el análisis antes de aceptar.

==Error típico==: asumir que porque el cliente es del exterior toda la operación es exportación de servicios. Lo determinante es **dónde se utiliza económicamente**, no quién paga.

# Matriz de Riesgos — Nexa Paraguay

---

> **Nota post-restructura.** Con el nuevo modelo (Nexa Paraguay marca
> cliente, LEALTIS proveedor técnico) se agregaron dos familias de
> riesgos al registro (R26–R37): dependencia del proveedor LEALTIS
> (R26–R30) y riesgos específicos del paquete 4 de Compra de Tierras
> (R31–R37). La matriz visual de abajo está pendiente de actualización
> gráfica para incluirlos. Ver `registro-de-riesgos.md` como fuente
> canónica.

---

## Matriz de probabilidad vs impacto

```
                          IMPACTO
                 Bajo         Medio        Alto
            ┌────────────┬────────────┬────────────┐
    Alta     │  R03       │  R02, R05  │  R01       │
            │            │  R13       │            │
Probabilidad├────────────┼────────────┼────────────┤
    Media    │  R15, R17  │  R09, R14  │  R06, R07  │
            │            │  R22       │  R11, R19  │
            ├────────────┼────────────┼────────────┤
    Baja     │  R04, R16  │  R10, R21  │  R08, R18  │
            │  R25       │            │  R20, R23  │
            │            │            │  R24       │
            └────────────┴────────────┴────────────┘
```

---

## Código de colores

| Color | Nivel | Zona | Acción requerida |
|:-----:|:-----:|:----:|-----------------|
| **Rojo** | Crítico | Alta probabilidad + Alto impacto | Mitigación inmediata, plan de acción activo, revisión mensual |
| **Naranja** | Alto | Alta+Medio, Media+Alto | Plan de mitigación definido, revisión trimestral |
| **Amarillo** | Medio | Media+Medio, Alta+Bajo, Baja+Alto | Monitoreo activo, mitigación planificada |
| **Verde** | Bajo | Baja+Bajo, Baja+Medio, Media+Bajo | Aceptar y monitorear |

---

## Distribución de riesgos por zona

### Zona roja (Crítico) — Acción inmediata

| ID | Riesgo | Mitigación activa |
|----|--------|:-----------------:|
| R01 | Dependencia de Daniel | Pendiente |

### Zona naranja (Alto) — Plan de mitigación activo

| ID | Riesgo | Mitigación activa |
|----|--------|:-----------------:|
| R02 | Rechazo bancario | Sí |
| R05 | Indisponibilidad personal clave | Pendiente |
| R06 | Cambio ley migratoria | Pendiente |
| R07 | Endurecimiento bancario | Pendiente |
| R09 | Regulación europea CRS | Pendiente |
| R11 | Insatisfacción de cliente | Pendiente |
| R13 | Comportamiento de competidores | Activo |
| R14 | Volumen inferior al proyectado | Activo |
| R19 | Conflicto entre socios | Pendiente |
| R22 | Límites de escalabilidad | Pendiente |

### Zona amarilla (Medio) — Monitoreo activo

| ID | Riesgo |
|----|--------|
| R03 | Retrasos gubernamentales |
| R08 | Reforma fiscal Paraguay |
| R12 | Asociación con mercado gris |
| R15 | Presión de precios |
| R17 | Riesgo cambiario |
| R18 | Responsabilidad profesional |
| R20 | Cierre prematuro de ventana |
| R23 | Inestabilidad política |
| R24 | Restricciones de viaje |

### Zona verde (Bajo) — Aceptar y monitorear

| ID | Riesgo |
|----|--------|
| R04 | Error en documentación |
| R10 | Obligaciones SEPRELAD |
| R16 | Impago de cliente |
| R21 | Competidor profesionalizado |
| R25 | Crisis económica |

---

## Apetito de riesgo

| Categoría | Tolerancia | Justificación |
|-----------|:----------:|---------------|
| **Operativo** | Media | El modelo depende de ejecución; se aceptan riesgos de proceso con mitigación |
| **Regulatorio** | Baja | Cambios regulatorios pueden destruir la propuesta de valor; monitoreo activo obligatorio |
| **Reputacional** | Muy baja | El negocio es trust-based; un incidente reputacional tiene impacto desproporcionado |
| **Financiero** | Media-alta | Estructura de costos flexible, break-even bajo; se pueden absorber variaciones |
| **Legal** | Muy baja | Cumplimiento estricto; no se aceptan riesgos legales evitables |
| **Estratégico** | Media | La ventana de oportunidad justifica asumir riesgos estratégicos calculados |

---

## Umbrales de escalación

| Nivel | Trigger | Quién escala | A quién |
|:-----:|---------|-------------|---------|
| 1 | Riesgo nuevo identificado o cambio de probabilidad/impacto | Cualquiera del equipo | Director de operaciones |
| 2 | Riesgo sube a zona naranja | Director de operaciones | Ambos socios |
| 3 | Riesgo llega a zona roja o se materializa | Cualquier socio | Reunión extraordinaria de socios |
| 4 | Riesgo materializado afecta a clientes | Ambos socios | Clientes afectados + plan de acción |

---

## Cadencia de revisión

| Actividad | Frecuencia | Responsable |
|-----------|:----------:|-------------|
| Revisión de la matriz completa | Trimestral | Ambos socios |
| Actualización de probabilidad/impacto | Trimestral | Ambos socios |
| Revisión de mitigaciones en zona roja | Mensual | Responsable asignado |
| Revisión de mitigaciones en zona naranja | Trimestral | Responsable asignado |
| Incorporación de riesgos nuevos | Continuo | Todo el equipo |
| Reporte de estado de riesgos | Trimestral (en revisión estratégica) | Ambos socios |

---

*Referencia: `riesgos/registro-de-riesgos.md`, `riesgos/plan-de-mitigacion.md`.*

# Plan de Continuidad del Negocio — [NOMBRE DE EMPRESA]

---

## 1. Procesos críticos y dependencias

| Proceso | Criticidad | Dependencia principal | Punto único de fallo |
|---------|:----------:|----------------------|:--------------------:|
| Coordinación bancaria | Crítica | Daniel (relaciones personales) | Sí |
| Presentación migratoria | Crítica | Equipo legal + Daniel | Parcial |
| Constitución societaria | Alta | Equipo legal + escribano | No |
| Gestión contable | Alta | Equipo contable | No |
| Adquisición de clientes | Crítica | Socio europeo | Sí |
| Logística jornada operativa | Media | Coordinador + chofer | No |

---

## 2. Escenarios de contingencia

### Escenario A: Daniel no disponible (temporal, 1–4 semanas)

| Proceso | Plan B | RTO |
|---------|--------|:---:|
| Coordinación bancaria | Deputy bancario (a desarrollar) + contacto directo con banco documentado | 3–5 días |
| Relaciones institucionales | Equipo legal ejecuta con protocolos documentados | 2–3 días |
| Supervisión de equipo | Socio europeo coordina remotamente + equipo legal senior lidera | 1 día |
| Jornada operativa | Equipo legal + coordinador logístico ejecutan con agenda pre-armada | 1 día |

**Acciones inmediatas:**
1. Socio europeo asume coordinación general
2. Equipo legal senior lidera operaciones
3. Comunicar a clientes activos (si hay impacto en plazos)
4. Activar contactos bancarios documentados

### Escenario B: Daniel sale permanentemente

| Acción | Plazo | Responsable |
|--------|-------|-------------|
| Activar cláusula de salida del acuerdo de partnership | Inmediato | Socio EU |
| Deputy bancario asume relaciones con entidades | 1–2 semanas | Deputy / Socio EU |
| Renegociar acuerdos con equipo técnico si necesario | 2–4 semanas | Socio EU |
| Evaluar contratación de director de operaciones | 1–3 meses | Socio EU |
| Comunicar a clientes activos con plan de continuidad | 1 semana | Socio EU |

### Escenario C: Socio europeo no disponible (temporal)

| Proceso | Plan B | RTO |
|---------|--------|:---:|
| Adquisición de clientes | Pipeline existente se pausa, Daniel atiende leads activos | 1 semana |
| Marketing y redes | Contenido programado se publica automáticamente, se pausa creación nueva | 1 día |
| Consultas comerciales | Daniel realiza consultas iniciales (en inglés/español) | 2–3 días |

### Escenario D: Relación bancaria principal se interrumpe

| Acción | Plazo |
|--------|-------|
| Activar banco alternativo (debe estar pre-identificado) | 1–2 semanas |
| Adaptar proceso de pre-validación a requisitos del nuevo banco | 1 semana |
| Comunicar a clientes en pipeline | 48 horas |
| Evaluar impacto en SLAs y ajustar | 1 semana |

### Escenario E: Cambio regulatorio significativo

| Acción | Plazo |
|--------|-------|
| Análisis de impacto por equipo legal | 48–72 horas |
| Comunicación a clientes activos | 48 horas |
| Actualización de procesos y documentación | 5 días hábiles |
| Actualización de web y materiales de marketing | 1–2 semanas |
| Ajuste de pricing si necesario | 1 semana |

### Escenario F: Restricción de viajes internacionales

| Acción | Plazo |
|--------|-------|
| Maximizar pre-procesamiento remoto (Fases 1–2 completas) | Inmediato |
| Diferir jornada operativa con agenda pre-armada | Según restricción |
| Explorar opciones de poder notarial para trámites presenciales | 1–2 semanas |
| Comunicar calendario revisado a clientes | 48 horas |

---

## 3. Objetivos de recuperación

| Proceso | RTO (Recovery Time Objective) | RPO (Recovery Point Objective) |
|---------|:-----------------------------:|:------------------------------:|
| Coordinación bancaria | 5 días | Sin pérdida de expedientes |
| Operaciones migratorias | 3 días | Sin pérdida de expedientes |
| Atención a clientes activos | 1 día | Sin pérdida de comunicación |
| Adquisición de nuevos clientes | 2 semanas | Pipeline preservado en CRM |
| Contabilidad de clientes | 5 días | Sin pérdida de registros |

---

## 4. Requisitos para que el plan funcione

| Requisito | Estado | Plazo para completar |
|-----------|:------:|:--------------------:|
| Contactos bancarios documentados | Pendiente | Mes 3 |
| Protocolos de cada institución escritos | Pendiente | Mes 6 |
| Deputy bancario identificado e introducido | Pendiente | Mes 12 |
| Acuerdo de partnership con cláusula de salida | Pendiente | Mes 0 |
| CRM con pipeline actualizado | Pendiente | Mes 2 |
| Backups digitales de toda la documentación | Pendiente | Mes 1 |
| Equipo legal con autonomía para ejecutar sin Daniel | Parcial | Mes 6 |

---

## 5. Plan de comunicación durante incidentes

| Audiencia | Quién comunica | Cuándo | Canal |
|-----------|---------------|--------|-------|
| Clientes activos (con programa en curso) | Socio más cercano | Dentro de 48 horas si hay impacto | Email personal + llamada |
| Clientes en pipeline (pre-contratación) | Socio europeo | Dentro de 1 semana | Email |
| Equipo técnico | Daniel o su deputy | Inmediato | Reunión + mensaje |
| Partners/referidores | Socio europeo | Si impacto > 2 semanas | Email |

### Template de comunicación a clientes

> "Estimado [nombre], le escribo para informarle sobre [situación]. Su programa sigue en curso y [detalle del impacto o no-impacto]. [Acción que estamos tomando]. Si tiene preguntas, estoy a su disposición. [Firma]"

**Principios:** Transparencia, proactividad, solución incluida, no alarmar innecesariamente.

---

## 6. Pruebas y revisión

| Actividad | Frecuencia | Responsable |
|-----------|-----------|-------------|
| Revisión del plan de continuidad | Anual | Ambos socios |
| Simulación de ausencia de Daniel (1 semana) | Anual (a partir de Mes 12) | Ambos socios |
| Verificación de documentación de contactos | Semestral | Daniel |
| Actualización de protocolos institucionales | Semestral | Equipo legal |
| Test de recuperación de datos | Anual | Operaciones |

---

*Referencia: `riesgos/registro-de-riesgos.md`, `source-of-truth/conversation-synthesis-source-of-truth.txt`.*

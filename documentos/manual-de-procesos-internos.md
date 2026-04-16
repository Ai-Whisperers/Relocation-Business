# Manual de Procesos Internos — Nexa Paraguay

---

> **Modelo operativo.** Nexa Paraguay es la marca cliente-facing. Los
> procesos técnico-legales de los paquetes Paraguay Base, Business e
> Investor Program están **delegados a LEALTIS** como proveedor
> especializado. Nexa Paraguay actúa como:
>
> - Punto único de contacto comercial y contractual con el cliente final.
> - Coordinador operativo con LEALTIS (recepción de insumos del cliente,
>   handoff a LEALTIS, seguimiento de hitos, QA, comunicación con el
>   cliente).
> - Ejecutor directo del paquete 4 (Compra de Tierras en Paraguay).
>
> Todos los procesos descritos abajo deben entenderse desde esta
> arquitectura: cuando aparece "Equipo legal" o "Equipo técnico" en
> paquetes 1–3, la ejecución corresponde al equipo de LEALTIS, coordinado
> por Nexa Paraguay.

---

## 1. Proceso de intake de clientes

### Trigger
Lead cualificado acepta programa y realiza pago.

### Pasos

| # | Acción | Responsable | Herramienta | Output |
|---|--------|-------------|-------------|--------|
| 1 | Confirmar recepción de pago | Administración | Banco / contabilidad | Confirmación escrita |
| 2 | Crear registro del cliente en CRM | Socio EU | CRM | Ficha del cliente creada |
| 3 | Enviar welcome pack (guía del cliente + checklist documental) | Socio EU | Email | Cliente informado |
| 4 | Asignar equipo responsable | Daniel | Interno | Equipo notificado |
| 5 | Programar kickoff interno (5 min) | Daniel | Reunión | Equipo alineado |
| 6 | Registrar fecha de inicio del programa | Coordinador | CRM | Timeline activado |

---

## 2. Verificación documental

### Trigger
Cliente envía documentación escaneada.

### Pasos

| # | Acción | Responsable | Plazo | Output |
|---|--------|-------------|:-----:|--------|
| 1 | Acuse de recibo al cliente | Coordinador | 1 día hábil | Email confirmación |
| 2 | Verificación de completitud (¿están todos los documentos?) | Coordinador | 1 día hábil | Lista de faltantes (si hay) |
| 3 | Revisión jurídica y de coherencia | Equipo legal | 3 días hábiles | Informe de validación |
| 4 | Chequeo preventivo ante Migraciones | Equipo legal | 2 días hábiles | Viabilidad confirmada |
| 5 | Comunicar resultado al cliente | Coordinador | 1 día hábil | "Listo para viajar" o lista de observaciones |
| 6 | Si hay observaciones: seguimiento hasta resolución | Coordinador | Hasta completar | Documentación 100% validada |

### Quality gate
No se agenda jornada operativa hasta que la documentación esté 100% validada y aprobada por el equipo legal.

---

## 3. Preparación del expediente

### Trigger
Documentación validada al 100%.

### Pasos

| # | Acción | Responsable | Plazo | Output |
|---|--------|-------------|:-----:|--------|
| 1 | Armado profesional del expediente migratorio | Equipo legal | 3 días hábiles | Expediente armado |
| 2 | Preparación de formularios complementarios | Equipo legal | Incluido | Formularios listos |
| 3 | Revisión final por abogado principal | Abogado principal | 1 día hábil | Aprobación con firma |
| 4 | Coordinación de agenda institucional | Coordinador | 1–2 días hábiles | Agenda confirmada |
| 5 | Comunicar agenda y logística al cliente | Coordinador | 1 día hábil | Cliente informado |

### Quality gate
Expediente aprobado internamente + agenda institucional confirmada.

---

## 4. Jornada operativa

### Trigger
Cliente llega a Asunción en fecha acordada.

### Protocolo del día

| Hora | Actividad | Responsable | Checklist |
|:----:|-----------|-------------|-----------|
| 07:30 | Chofer recoge al cliente en hotel | Chofer | Confirmar dirección la noche anterior |
| 08:00 | Briefing en punto de encuentro | Coordinador | Repasar agenda del día |
| 08:30 | Presentación ante autoridad migratoria | Equipo legal + cliente | Expediente completo, documentos originales |
| 10:00 | Gestión ante escribanía (si necesario) | Escribano | Documentos a notarizar listos |
| 10:30 | Trámite de Cédula de Identidad | Equipo legal + cliente | Requisitos preparados |
| 11:30 | Coordinaciones complementarias | Coordinador | Según programa |
| 12:00 | Pausa / almuerzo | — | — |
| 14:00 | Tour estratégico inmobiliario | Asesor Nexa Paraguay | Desarrolladoras agendadas |
| 17:00 | Cierre del día, resumen al cliente | Coordinador | Confirmar todo lo realizado |

### Checklist pre-jornada (día anterior)

- [ ] Confirmar horario y dirección de hotel del cliente
- [ ] Confirmar chofer y vehículo
- [ ] Verificar que expediente está completo e impreso
- [ ] Confirmar agenda institucional
- [ ] Confirmar tour inmobiliario
- [ ] Preparar carpeta del cliente (copias de seguridad de documentos)

---

## 5. Proceso post-jornada

### Constitución societaria

| # | Acción | Responsable | Plazo |
|---|--------|-------------|:-----:|
| 1 | Análisis estratégico del tipo societario | Equipo legal | 3 días |
| 2 | Redacción de estatutos | Equipo legal | 5 días |
| 3 | Formalización ante escribano | Escribano | 3 días |
| 4 | Inscripción registral | Equipo legal | 5 días |
| 5 | Confirmar inscripción al cliente | Coordinador | 1 día |

### Activación RUC

| # | Acción | Responsable | Plazo |
|---|--------|-------------|:-----:|
| 1 | Preparación de documentación SET | Equipo contable | 2 días |
| 2 | Inscripción ante SET | Equipo contable | 3 días |
| 3 | Activación y configuración | Equipo contable | 2 días |
| 4 | Confirmar RUC activo al cliente | Coordinador | 1 día |

### Apertura bancaria

| # | Acción | Responsable | Plazo |
|---|--------|-------------|:-----:|
| 1 | Preparación de perfil financiero (KYC) | Equipo contable | 5 días |
| 2 | Coordinación con entidad bancaria | Daniel | 5 días |
| 3 | Presentación de expediente bancario | Daniel | 1 día |
| 4 | Seguimiento hasta habilitación | Coordinador | Hasta 30 días |
| 5 | Confirmar cuenta operativa al cliente | Coordinador | 1 día |

---

## 6. Control de calidad

### Checkpoints obligatorios

| Momento | Qué se verifica | Quién verifica |
|---------|----------------|----------------|
| Pre-envío de expediente | Completitud, coherencia, firmas | Abogado principal (doble revisión) |
| Pre-jornada | Agenda confirmada, documentos listos, logística lista | Coordinador + Daniel |
| Post-jornada | Todo presentado correctamente, cliente informado | Coordinador |
| Post-constitución | Estatutos correctos, inscripción confirmada | Equipo legal |
| Post-apertura bancaria | Cuenta operativa, cliente notificado | Coordinador |
| Cierre del programa | Todos los entregables completados | Daniel |

### Protocolo ante error

1. Detectar y documentar el error inmediatamente.
2. Notificar al responsable del área + Daniel.
3. Evaluar impacto en el cliente y en plazos.
4. Ejecutar corrección.
5. Comunicar al cliente si hay impacto (con plan de acción).
6. Documentar en retrospectiva para evitar recurrencia.

---

## 7. Gestión de archivos

| Tipo | Formato | Almacenamiento | Retención |
|------|---------|----------------|:---------:|
| Expedientes de clientes | Digital (PDF) + físico | Cloud seguro + archivo físico | 5 años |
| Correspondencia | Digital | Email + CRM | 3 años |
| Acuerdos firmados | Digital + físico | Cloud + archivo | 5 años |
| Registros internos | Digital | Cloud | 3 años |

### Estructura de carpetas por cliente

```
/Clientes/[Apellido_Nombre]/
  ├── 01_Documentación_recibida/
  ├── 02_Expediente_migratorio/
  ├── 03_Societario/
  ├── 04_Bancario/
  ├── 05_Fiscal/
  ├── 06_Correspondencia/
  └── 07_Cierre/
```

---

## 8. Comunicación interna

| Tipo | Canal | Frecuencia |
|------|-------|-----------|
| Estado de clientes activos | Sync semanal Daniel + Socio EU | Semanal |
| Incidencias urgentes | Mensajería directa | Inmediato |
| Asignación de tareas | CRM / herramienta de gestión | Según necesidad |
| Retrospectivas | Reunión | Post cada 5 clientes (mínimo trimestral) |

---

## 9. Procedimiento de escalación

| Nivel | Situación | Quién escala | A quién | Plazo de resolución |
|:-----:|-----------|-------------|---------|:-------------------:|
| 1 | Consulta operativa estándar | Coordinador | Responsable del área | 24–48 horas |
| 2 | Retraso o incidencia en un hito | Responsable del área | Daniel | 3–5 días |
| 3 | Problema que afecta al programa completo | Daniel | Ambos socios | 5–10 días |
| 4 | Incidencia crítica (rechazo, cambio regulatorio, queja grave) | Cualquiera | Reunión extraordinaria | Inmediato |

---

## 10. Reportes

| Reporte | Contenido | Frecuencia | Responsable |
|---------|-----------|:----------:|-------------|
| Estado de clientes | Cada cliente activo: fase, % avance, próximos pasos, alertas | Semanal | Coordinador |
| KPIs operativos | Tiempos de ciclo, SLA compliance, tasa bancaria | Mensual | Daniel |
| Financiero | Ingresos, costos, margen | Mensual | Contabilidad |
| Satisfacción | NPS, feedback | Por cliente + trimestral | Socio EU |

---

*Referencia: `servicios/blueprint-operativo-paraguay-business.md`, `servicios/SLAs-y-compromisos.md`, `riesgos/politica-de-compliance.md`.*

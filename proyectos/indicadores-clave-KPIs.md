# Indicadores Clave de Desempeño (KPIs) — [NOMBRE DE EMPRESA]

---

## 1. KPIs de negocio

| KPI | Definición | Fórmula | Meta | Frecuencia | Fuente | Owner |
|-----|-----------|---------|:----:|:----------:|--------|-------|
| Clientes/mes | Programas contratados en el mes | Conteo directo | 2–4 | Mensual | CRM | Ambos |
| Ingreso mensual | Facturación total del mes | Suma de programas + recurrentes | USD 10k–20k | Mensual | Contabilidad | Ambos |
| Ingreso promedio por cliente | Revenue por cliente | Ingresos / clientes | > USD 5.000 | Mensual | Contabilidad | Ambos |
| Mix de paquetes | % Business vs Investor | Investor / total | 40% Investor | Mensual | CRM | Socio EU |
| Ingreso recurrente (%) | % de ingresos de servicios continuos | Recurrentes / total | > 15% (Año 2) | Trimestral | Contabilidad | Ambos |
| Satisfacción (NPS) | Net Promoter Score | Encuesta post-programa | > 8/10 | Por cliente | Encuesta | Socio EU |

---

## 2. KPIs de marketing

| KPI | Definición | Fórmula | Meta | Frecuencia | Fuente | Owner |
|-----|-----------|---------|:----:|:----------:|--------|-------|
| Visitas web/mes | Tráfico total al sitio | GA4 sessions | 500–1.000 | Mensual | GA4 | Socio EU |
| Leads/mes | Formularios + consultas recibidas | Conteo CRM | 10–15 | Mensual | CRM | Socio EU |
| Tasa de conversión web | Leads / visitas | Leads / sessions × 100 | 2–3% | Mensual | GA4 + CRM | Socio EU |
| Tasa de conversión lead→cliente | Clientes / leads | Clientes / leads × 100 | 20–30% | Mensual | CRM | Socio EU |
| Costo por lead (CPL) | Inversión marketing / leads | Marketing spend / leads | < USD 100 | Mensual | Marketing + CRM | Socio EU |
| Costo de adquisición (CAC) | Inversión total / clientes | Total spend / clientes | < USD 500 | Mensual | Finanzas | Socio EU |
| % clientes por referido | Referidos / total clientes | Referidos / total × 100 | > 30% | Trimestral | CRM | Socio EU |
| Engagement redes | Interacciones / alcance | Engagement rate | > 3% | Semanal | Plataformas | Socio EU |

---

## 3. KPIs de operaciones

| KPI | Definición | Fórmula | Meta | Frecuencia | Fuente | Owner |
|-----|-----------|---------|:----:|:----------:|--------|-------|
| Tiempo de validación documental | Días desde recepción hasta "listo para viajar" | Fecha fin – fecha inicio | < 10 días hábiles | Por cliente | Registro interno | Daniel |
| Cumplimiento de jornada operativa | % de jornadas completadas en 1 día | Exitosas / total × 100 | > 95% | Trimestral | Registro | Daniel |
| Tasa de aprobación bancaria | % cuentas aprobadas en primer intento | Aprobadas / presentadas × 100 | > 85% | Trimestral | Registro | Daniel |
| Tiempo de constitución societaria | Días desde jornada hasta sociedad registrada | Fecha registro – fecha jornada | < 15 días hábiles | Por cliente | Registro | Daniel |
| Tiempo de activación RUC | Días hasta RUC activo | Fecha activo – fecha solicitud | < 10 días hábiles | Por cliente | Registro | Daniel |
| Tasa de error/rework | % de expedientes con errores que requieren corrección | Errores / total × 100 | < 5% | Trimestral | Registro | Daniel |
| Cumplimiento de SLAs | % de hitos dentro de plazo comprometido | Dentro SLA / total × 100 | > 90% | Trimestral | Registro | Daniel |

---

## 4. KPIs financieros

| KPI | Definición | Fórmula | Meta | Frecuencia | Fuente | Owner |
|-----|-----------|---------|:----:|:----------:|--------|-------|
| Margen bruto por cliente | Ingreso – costos variables | Precio – CV | > USD 3.000 | Por cliente | Contabilidad | Ambos |
| Margen bruto (%) | Margen / ingreso | (Precio – CV) / Precio × 100 | > 55% | Mensual | Contabilidad | Ambos |
| Costos fijos / ingreso | Proporción de costos fijos | CF / ingreso total × 100 | < 25% | Mensual | Contabilidad | Ambos |
| Cash runway | Meses de operación con efectivo actual | Efectivo / burn mensual | > 3 meses | Mensual | Contabilidad | Ambos |
| LTV (Lifetime Value) | Valor total de un cliente | Programa + renovaciones + comisiones | > USD 8.000 | Anual | Contabilidad | Ambos |
| LTV/CAC | Eficiencia de adquisición | LTV / CAC | > 10x | Trimestral | Calc | Socio EU |

---

## 5. Dashboard de revisión

### Revisión semanal (15 min)

| Métrica | Qué revisar |
|---------|-------------|
| Leads de la semana | Cantidad, origen, calidad |
| Pipeline activo | Clientes en proceso, estado de cada programa |
| Engagement redes | Posts publicados, interacciones |

### Revisión mensual (60 min)

| Métrica | Qué revisar |
|---------|-------------|
| Todos los KPIs de negocio | vs meta, vs mes anterior |
| Todos los KPIs de marketing | Tendencia, ROI |
| Finanzas | Ingresos, costos, margen, runway |
| Operaciones | SLA compliance, tiempos de ciclo |

### Revisión trimestral (90 min)

| Métrica | Qué revisar |
|---------|-------------|
| Todo lo anterior + tendencias | 3 meses, dirección |
| NPS acumulado | Satisfacción del cliente |
| Registro de riesgos | Actualización de probabilidad/impacto |
| Progreso vs roadmap | Hitos alcanzados |
| Ajustes estratégicos | Cambios en plan, pricing, operaciones |

---

## 6. Alertas y triggers

| Alerta | Trigger | Acción |
|--------|---------|--------|
| Volumen bajo | < 1 cliente/mes por 2 meses consecutivos | Revisión urgente de estrategia de adquisición |
| NPS bajo | < 7/10 en cualquier cliente | Investigación inmediata + plan de mejora |
| Tasa bancaria baja | < 70% aprobación | Revisión de pre-validación + relaciones bancarias |
| Cash bajo | Runway < 2 meses | Reducción de costos + revisión de pipeline |
| SLA incumplido | < 80% cumplimiento | Revisión de procesos + capacidad |

---

*Referencia: `source-of-truth/objectives-general-and-specific.md`, `servicios/SLAs-y-compromisos.md`, `presupuesto/estructura-de-ingresos.md`.*

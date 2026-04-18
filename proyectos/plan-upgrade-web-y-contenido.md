# Plan de upgrade — Web y Contenido (derivado de investigación competitiva 2026-04)

Este plan operacionaliza los hallazgos de `competidores/brechas-y-oportunidades.md` en entregables concretos para los equipos de web, producto y contenido.

## 1. Sitio web — arquitectura objetivo

### 1.1 Mapa de sitio propuesto

```
/
├── / (home)
├── /por-que-paraguay
├── /programas
│   ├── /programas/paraguay-business
│   ├── /programas/paraguay-investor-program
│   └── /programas/compra-de-tierras
├── /plan-anual-de-compliance            (nuevo producto recurrente)
├── /precios                              (NUEVO — precios públicos)
├── /proceso                              (timeline de 6 pasos)
├── /por-que-nosotros                    (landing vs alternativas)
├── /garantia                             (NUEVO — garantía de residencia)
├── /sla                                  (NUEVO — SLA contractual público)
├── /recursos
│   ├── /recursos/guia-paraguay-2026      (lead magnet, NL/DE/EN)
│   ├── /recursos/calculadora-ahorro-fiscal  (NUEVO)
│   ├── /recursos/blog
│   └── /recursos/podcast                 (NUEVO)
├── /casos                                (testimonios en video NL/DE)
├── /equipo                               (con LEALTIS como partner)
├── /aplicar                              (formulario calificador)
└── /contacto
```

### 1.2 Componentes reutilizables clave

- **Hero multilingüe** con toggle NL/DE/EN/ES visible en header.
- **Calculadora de ahorro fiscal** embebible en varias páginas (home, programas, recursos).
- **Comparador de programas** (Business vs Investor vs Compra de tierras).
- **Widget SLA** (compromisos visibles en páginas de programa).
- **CTA dual**: “Descargar guía” (top/middle) + “Aplicar ahora” (bottom).

### 1.3 Principios de UX

- Cada página debe responder una pregunta principal en el H1.
- Precio visible en ≤2 clics desde cualquier página.
- Formularios: 1 en home (email-only para guía), 1 en /aplicar (largo calificador).
- Performance budget: LCP <2.0s, CLS <0.1.
- Accesibilidad: WCAG 2.2 AA mínimo.

## 2. Home page — cambios específicos

**Situación actual:** placeholder (aún sin web pública).

**Objetivo:** home que convierta al visitante NL/DE en una descarga de guía en <30s.

**Estructura del home:**

1. **Hero** — Titular: “Paraguay operativo: residencia, empresa y banca en su idioma.” Subtitular: scope de 3 líneas. CTA primario: “Calcular mi ahorro fiscal”. CTA secundario: “Ver precios”.
2. **Barra de proof** — LEALTIS (partner legal), años de experiencia, idiomas, país de origen de clientes.
3. **Los 5 pilares** — Claridad · Idioma · Ejecución local · Producto · Continuidad (ver `competidores/matriz-posicionamiento.md`).
4. **Programas** — 3 cards (Business, Investor, Compra de tierras) con precio “desde”.
5. **Proceso en 6 pasos** — timeline visual.
6. **Garantía** — banner con texto de la garantía de residencia.
7. **Casos** — 2–3 testimonios en video (cuando existan).
8. **Calculadora de ahorro fiscal** — interactiva, captura email al final.
9. **FAQ corto** — 6 preguntas top, link a FAQ completo.
10. **CTA final** — “Aplicar ahora” + “Hablar con el equipo”.

## 3. Contenido — calendario editorial 6 meses

Derivado de `marketing/plan-de-contenidos.md`, priorizando queries identificadas en análisis competitivo.

### Q2 2026 (abril–junio)

**Blog (mínimo 2 posts/mes por idioma, NL/DE/EN):**

- [EN] “Paraguay residency in 2026: the complete guide for European professionals”
- [NL] “Paraguay als fiscale residentie: wat een Nederlander echt moet weten”
- [DE] “Paraguay-Residenz 2026: Schritt für Schritt für deutsche Unternehmer”
- [EN] “Paraguay vs Panama vs Portugal: honest comparison for EU citizens”
- [NL] “Box 3 en Paraguay: wanneer is het legaal, wanneer niet”
- [DE] “Wegzugsbesteuerung und Paraguay: was der §6 AStG bedeutet”

**Podcast — lanzar 3 episodios:**
- Episodio 1 (NL): “Waarom Paraguay, niet Portugal” — con fiscalista NL.
- Episodio 2 (DE): “Paraguay praktisch — Behörden, Bank, Büro” — con consultor DE ya relocado.
- Episodio 3 (EN): “The Paraguay residency process, unfiltered” — con LEALTIS.

**Lead magnet:** publicar “Guía Paraguay 2026” en NL/DE/EN (ver `marketing/contenido-web.md` para tono de voz).

### Q3 2026 (julio–septiembre)

- 6 posts nuevos por idioma (12 total).
- 2 episodios podcast por idioma.
- Webinar mensual (1 NL, 1 DE, alternar meses).
- Caso de estudio del primer cliente cerrado (con su permiso).

### Q4 2026 (octubre–diciembre)

- Continuidad + primera ronda de “refresh” de contenido antiguo.
- Contenido estacional: “Cerrar el año fiscal europeo con residencia paraguaya ya tramitada”.
- Evento presencial piloto en Asunción (30 asistentes).

## 4. Canales y distribución

| Canal | Objetivo 6 meses | Responsable |
|---|---|---|
| Blog propio (SEO) | 500 visitas orgánicas/mes | Marketing |
| YouTube (podcast video) | 500 suscriptores | Marketing + host |
| Spotify/Apple Podcast | 1.000 descargas/mes | Marketing |
| LinkedIn (fundador/equipo) | 2 posts/semana por idioma | Dirección |
| Google Ads (NL/DE) | CPL <USD 40 | Marketing |
| YouTube Ads (pre-roll en podcasts fiscales) | CPL <USD 60 | Marketing |
| Newsletter | >500 suscriptores, open rate >35% | Marketing |
| Alianzas media NL/DE | 1 artículo/trimestre | Dirección |

## 5. Stack técnico recomendado

- **CMS headless:** Payload CMS o Strapi — permite i18n real y API.
- **Frontend:** Next.js 15 con ISR para páginas de blog, SSR para /aplicar.
- **Calculadora:** componente React client-side con lógica validada por fiscalista.
- **Forms:** React Hook Form + schema Zod.
- **Analytics:** Plausible o Matomo (evita Google Analytics por GDPR — importante para cliente DE/NL).
- **Form backend:** servicio propio en `paragu-ai-leads` (repo hermano) con CRM básico.
- **i18n:** `next-intl`, rutas `/nl/...`, `/de/...`, `/en/...`, default `/es/...`.

## 6. Cronograma de implementación

| Semana | Hito |
|---|---|
| 1 | Arquitectura de información + wireframes firmados |
| 2 | Contenido base de home/programas redactado en ES, validado por LEALTIS |
| 3 | Traducción NL/DE/EN de páginas core |
| 4–5 | Implementación front + CMS |
| 6 | Calculadora fiscal funcional |
| 7 | Lead magnet producido y distribuible |
| 8 | QA, performance budget, accesibilidad |
| 9 | Soft launch (solo EN) |
| 10 | Launch NL + DE |
| 11–12 | SEO on-page, schema, sitemap, Search Console |

## 7. Presupuesto estimado (primer ciclo)

Actualizar `presupuesto/presupuesto-marketing.md` con estos rangos:

| Ítem | Rango USD |
|---|---|
| Diseño + front-end (agencia o freelance senior) | 12.000 – 18.000 |
| CMS + infraestructura primer año | 1.500 – 3.000 |
| Traducción profesional (NL/DE/EN) ciclo inicial | 3.000 – 5.000 |
| Producción podcast primer trimestre | 1.500 – 3.000 |
| Lead magnet (diseño + redacción + traducción) | 2.000 – 3.500 |
| Ads piloto (primeros 3 meses) | 3.000 – 6.000 |
| **Total inicial** | **23.000 – 38.500** |

## 8. KPIs para el primer año

| KPI | Meta a 12 meses |
|---|---|
| Leads calificados (A-fit) | 120 |
| Conversión lead → cliente | 12% |
| Clientes nuevos | 15 |
| Revenue programas | USD 90.000 – 110.000 |
| Retainers anuales activos | 10 |
| Revenue recurrente (ARR) | USD 18.000 |
| Descargas guía | 1.500 |
| Tráfico orgánico mensual | 2.000 visitas |
| NPS | >60 |

## 9. Riesgos y mitigaciones

- **Riesgo:** producción de contenido en 3 idiomas excede capacidad. **Mitigación:** priorizar NL primero, DE segundo, EN tercero; usar traductores freelance validados.
- **Riesgo:** calculadora fiscal mal diseñada genera expectativas irreales. **Mitigación:** disclaimer claro, validación de fiscalista por país, escenarios conservadores.
- **Riesgo:** competidor lanza en NL/DE antes. **Mitigación:** priorizar lead magnet y podcast en Q2 como “claim” de territorio.
- **Riesgo:** performance insuficiente del sitio daña SEO. **Mitigación:** performance budget en CI/CD, Lighthouse ≥90 como gate.

## 10. Dueños

- **Producto/Web:** dirección de producto + agencia.
- **Contenido:** dirección de marketing + traductores freelance + LEALTIS (revisión legal).
- **Datos/Analítica:** dirección + equipo técnico.
- **Decisión final:** comité semanal de 60 min durante las primeras 12 semanas.

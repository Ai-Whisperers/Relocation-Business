# CLAUDE.md -- Project Context for AI Assistants

## Project Type

Documentation-only business planning repository. **No application code.** All content is markdown files in Spanish.

## What This Business Does

Professional relocation service helping European clients establish legal, financial, and operational presence in Paraguay. Two programs: Paraguay Business (USD 4,400) and Paraguay Investor Program (USD 6,900).

## Repository Conventions

- **Language**: All business documents are in Spanish. Configuration files and AI tooling are in English.
- **Company name placeholder**: `[NOMBRE DE EMPRESA]` is used everywhere -- the name has not been decided yet.
- **Directory structure**: Business content is organized by domain (marketing, servicios, riesgos, etc.). Configuration/tooling is in dotfiles (.cursor, .claude, .specstory).

## Known Issues

- The `.cursor/` directory (488 files) contains rules imported from a .NET development project. Most are irrelevant to this repo.
- Legal documents in `documentos/` are drafts requiring attorney review.
- SEPRELAD (anti-money-laundering) compliance status is unverified.
- Financial projections use unvalidated assumptions (60/40 client mix, no market research data).

## When Editing Business Documents

- Maintain Spanish language consistency
- Preserve `[NOMBRE DE EMPRESA]` placeholder (do not invent a company name)
- Cross-reference related documents when making changes (e.g., pricing changes must be reflected in presupuesto/, servicios/, and marketing/)
- Do not modify financial figures without flagging the change explicitly

## Key Reference Files

- Source of truth for program details: `source-of-truth/lealtis-paraguay-business-program.md`
- Source of truth for strategic objectives: `source-of-truth/objectives-general-and-specific.md`
- Source of truth for full questionnaire answers: `source-of-truth/cuestionario-respuestas-completas.md`

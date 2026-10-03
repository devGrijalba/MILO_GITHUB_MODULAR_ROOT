# MILO ENGINE MANIFEST

engine_version: `7.0.0-MODULAR`

## ORDEN DE ESTADOS

### STATE 01 — SOURCE
Leer:
- `02_SOURCE_RESOLUTION.md`

### STATE 02 — SEED_SELECTION
Leer:
- `03_SEED_SELECTION.md`
- archivo de semillas correspondiente al rango

### STATE 03 — SEED_NORMALIZATION
Leer:
- `04_SEED_SNAPSHOT_NORMALIZATION.md`
- `18_SEED_HEADER_NORMALIZATION.md`

### STATE 04 — SCRIPT_BUILD
Leer:
- `05_SCRIPT_SCHEMA.md`
- `06_NARRATIVE_RULES.md`
- `16_CANON_CHARACTERS.md`
- `19_EPISODE_ID_RULES.md`

### STATE 05 — QA_MECHANICAL
Leer:
- `05_SCRIPT_SCHEMA.md`
- `10_DURATION_HOOK_QA.md`

### STATE 06 — QA_SEMANTIC
Leer:
- `07_CAUSALITY_QA.md`
- `08_ACTOR_CONTINUITY_QA.md`
- `09_TEMPORALITY_WORLD_QA.md`
- `11_PAYOFF_QA.md`

### STATE 07 — REPAIR
Leer:
- `17_REPAIR_PROTOCOL.md`

### STATE 08 — VOICE
Leer:
- `12_VOICE_ENGINE.md`

### STATE 09 — FINAL_GATE
Leer:
- `13_FINAL_GATE.md`
- `14_OUTPUT_CONTRACT.md`

### STATE 10 — REGRESSION_TEST
Solo cuando se pruebe o depure:
- `20_REGRESSION_TESTS.md`

## REGLA DE CARGA

No saltar estados.

No considerar PASS un estado sin consultar sus módulos obligatorios.

No emitir artefacto final antes de STATE 09.

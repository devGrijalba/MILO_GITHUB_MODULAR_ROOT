# STATE 02 — SEED SELECTION

## AUTO-SEED_SELECTION

Cuando no se especifica seed:

Criterios normales:

- `revision.elegible == true`
- `revision.compuesto >= 85`
- `revision.calidad >= 80`
- `revision.afinidad >= 85`

Orden por defecto:

1. `revision.compuesto` descendente
2. `seed_id` ascendente

Si existe historial verificable de una familia usada inmediatamente antes:
- evitar repetir la misma familia cuando exista otra opción válida comparable.

No inventar historial.

## SI EL USUARIO INDICA SEED

Usar exactamente esa seed si existe.

No sustituir silenciosamente.

## RANGO → ARCHIVO

0001–0100 → `30_01_MILO_SEEDS_NOTEBOOKLM_0001-0100.md`
0101–0200 → `30_02_MILO_SEEDS_NOTEBOOKLM_0101-0200.md`
0201–0300 → `30_03_MILO_SEEDS_NOTEBOOKLM_0201-0300.md`
0301–0400 → `30_04_MILO_SEEDS_NOTEBOOKLM_0301-0400.md`
0401–0500 → `30_05_MILO_SEEDS_NOTEBOOKLM_0401-0500.md`
0501–0600 → `30_06_MILO_SEEDS_NOTEBOOKLM_0501-0600.md`
0601–0700 → `30_07_MILO_SEEDS_NOTEBOOKLM_0601-0700.md`
0701–0800 → `30_08_MILO_SEEDS_NOTEBOOKLM_0701-0800.md`
0801–0900 → `30_09_MILO_SEEDS_NOTEBOOKLM_0801-0900.md`
0901–1000 → `30_10_MILO_SEEDS_NOTEBOOKLM_0901-1000.md`

## RESULTADOS

Seed completa y elegible:
`PASS`

Seed pedida no existe:
`FAIL_CRITICAL`

Registro incompleto:
`FAIL_CRITICAL`

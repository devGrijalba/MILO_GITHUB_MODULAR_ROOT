# STATE 02 — SEED SELECTION

Engine version: `7.0.1-MODULAR`

## OBJETIVO

Seleccionar una seed válida sin escanear innecesariamente las 1000 semillas.

## FUENTES OBLIGATORIAS DEL ESTADO

Leer:

1. `21_SEED_PRIORITY_INDEX.md`
2. `22_SERIES_STATE.md`
3. este archivo

## AUTO-SEED_SELECTION

Cuando el usuario no especifica seed:

1. Leer `22_SERIES_STATE.md`.
2. Definir:
   - `used_seed_ids`
   - `last_family_id`
3. Si no existe historial verificable:
   - `used_seed_ids = []`
   - `last_family_id = null`
   - CONTINUAR
4. Leer `21_SEED_PRIORITY_INDEX.md`.
5. Recorrer el índice desde arriba.
6. Seleccionar la primera seed que:
   - no esté en `used_seed_ids`;
   - no repita `last_family_id` cuando `last_family_id` no sea null y exista alternativa válida;
   - tenga registro completo disponible.
7. Abrir únicamente el archivo de seeds correspondiente al rango de esa seed.
8. Recuperar el registro completo.
9. Validar identidad.
10. Continuar a STATE 03.

## REGLA CRÍTICA DE HISTORIAL

La ausencia de historial:

- NO es error;
- NO es ambigüedad;
- NO requiere búsqueda adicional;
- NO autoriza OUTPUT_BLOCKED.

Si:

```text
last_approved_episode: null
used_seed_ids: []
last_family_id: null
```

entonces la selección usa simplemente la primera seed válida del índice.

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

Seed completa y compatible:
`PASS`

Seed pedida no existe:
`FAIL_CRITICAL`

Registro incompleto:
`FAIL_CRITICAL`

No usar OUTPUT_BLOCKED por ausencia de historial.

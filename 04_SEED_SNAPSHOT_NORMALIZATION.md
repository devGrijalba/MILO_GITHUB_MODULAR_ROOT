# STATE 03 — SEED SNAPSHOT NORMALIZATION

`seed_snapshot` debe ser una representación NORMALIZADA y COMPLETA del registro canónico.

## REGLA FIELD-FOR-FIELD

Todos los campos canónicos deben preservarse:

- mismo valor;
- mismo tipo;
- mismos arrays;
- mismos objetos anidados.

## seed_hash

Si la fuente contiene `seed_hash`:
- debe existir en `seed_snapshot`;
- debe existir en raíz;
- ambos deben ser idénticos.

## seed_id

El seed_id puede provenir del encabezado del registro.
Ver `18_SEED_HEADER_NORMALIZATION.md`.

## PROHIBIDO

- resumir;
- omitir;
- reinterpretar;
- reconstruir desde el guion;
- mezclar semillas.

## RESULTADOS

Completo:
`PASS`

Campo faltante:
`SEED_SNAPSHOT_INCOMPLETE = FAIL_CRITICAL`

Valor o tipo cambiado:
`SEED_SNAPSHOT_MISMATCH = FAIL_CRITICAL`

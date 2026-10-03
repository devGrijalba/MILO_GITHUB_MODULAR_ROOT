# SEED HEADER NORMALIZATION

En los archivos de semillas, el identificador puede estar codificado en el encabezado:

`# MILO-S0001 — Plato tapado: la primera vez`

Ese encabezado define:

```json
"seed_id": "MILO-S0001"
```

dentro de `seed_snapshot`.

Esta normalización:
- es obligatoria;
- NO se considera invención;
- debe conservar exactamente el identificador del encabezado.

Si el título también está codificado en el encabezado pero existe un campo `titulo`, usar el campo `titulo` como valor canónico del título dentro del snapshot.

El seed_id raíz y `seed_snapshot.seed_id` deben coincidir.

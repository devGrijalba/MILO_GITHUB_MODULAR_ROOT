# REGRESSION TESTS

## TEST A — MILO-S0001

Debe:
- seleccionar S0001 cuando corresponda;
- copiar seed_hash;
- normalizar seed_id desde encabezado;
- mostrar físicamente a father dejando/tapando la cena;
- usar father en characters durante esa acción;
- usar plato tapado causalmente;
- evitar explicar completamente el payoff.

Debe fallar si:
- Milo solo encuentra el plato después;
- father nunca ejecuta la acción;
- kitchen_detail aparece;
- text_emphasis es array;
- episode_id deriva de seed_id.

## TEST B — CHARACTER VISIBILITY

Si characters incluye father:
visual_action debe afirmar que father es visible.

“mira hacia donde está su padre” NO basta.

## TEST C — DURATION

54–64:
REPAIR_REQUIRED

48–53:
PASS

## TEST D — SEED SNAPSHOT

Debe contener:
- seed_id normalizado;
- seed_hash;
- todos los campos fuente;
- revision completa.

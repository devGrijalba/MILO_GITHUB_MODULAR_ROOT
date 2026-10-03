# MILO ROUTER

Engine version: `7.0.1-MODULAR`

Este archivo controla el flujo modular.

## ENTRADA NORMAL

Cuando el usuario diga:

`CREA UN EPISODIO`

o equivalente:

1. leer `00_MANIFEST_MILO_ENGINE.md`;
2. congelar `engine_version`;
3. ejecutar STATE 01;
4. continuar únicamente si el estado actual queda PASS;
5. si aparece REPAIR_REQUIRED, ir a STATE 07;
6. reparar;
7. volver al estado que falló;
8. máximo 3 ciclos de reparación por episodio;
9. si persiste FAIL_CRITICAL o REPAIR_REQUIRED después del máximo:
   `OUTPUT_BLOCKED`;
10. si todos los estados pasan:
   emitir usando `14_OUTPUT_CONTRACT.md`.

## STATE 02 — REGLA ESPECIAL

La selección automática debe usar:

- `21_SEED_PRIORITY_INDEX.md`
- `22_SERIES_STATE.md`

No volver a escanear las 1000 seeds para encontrar un máximo global.

Si el estado de serie está vacío:

```text
used_seed_ids = []
last_family_id = null
```

continuar normalmente.

La ausencia de historial nunca bloquea.

## ESTADOS

- PASS
- REPAIR_REQUIRED
- FAIL_CRITICAL

## PROHIBICIÓN

No generar un guion libre en Markdown.

No mostrar:
- estados;
- QA;
- razonamiento;
- módulos consultados;
- deliberación;
- reparaciones;
- links.

Solo mostrar el artefacto final permitido.

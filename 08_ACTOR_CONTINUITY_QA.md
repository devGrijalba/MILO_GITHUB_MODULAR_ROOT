# QA — ACTOR + CONTINUITY

## SEMANTIC_ACTOR_CONSISTENCY

Comparar:
- agente fuente;
- sujeto narration;
- objeto narration;
- visual_action;
- characters.

No cambiar silenciosamente el agente.

Pronombre ambiguo:
`REPAIR_REQUIRED`

Cambio causal de agente:
`FAIL_CRITICAL`

## CHARACTER VISIBILITY

`characters` solo contiene personajes explícitamente visibles en `visual_action`.

No basta:
- “mira hacia donde está”;
- personaje inferido;
- presencia fuera de cuadro.

Si un personaje aparece en `characters`, `visual_action` debe afirmar su visibilidad.

## CONTINUIDAD

Revisar:
- ubicación;
- objetos;
- estado de objetos;
- iluminación;
- vestuario relevante;
- posición;
- información conocida;
- presencia física.

Todo coherente:
`PASS`

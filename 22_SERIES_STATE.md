# MILO — SERIES STATE

Engine version: `7.0.2-MODULAR`

Este archivo representa el estado explícito de continuidad de la serie.

## ESTADO ACTUAL

```yaml
last_approved_episode: null
used_seed_ids: []
last_family_id: null
approved_episode_count: 0
```

## REGLAS

- La ausencia de historial NO bloquea generación.
- Si `last_approved_episode == null`, asumir serie limpia.
- Si `used_seed_ids == []`, no excluir ninguna seed por uso previo.
- Si `last_family_id == null`, no excluir ninguna familia por continuidad.
- Nunca inventar historial.
- Solo actualizar este archivo cuando el usuario apruebe explícitamente un episodio.
- Un episodio generado pero no aprobado NO modifica el estado.

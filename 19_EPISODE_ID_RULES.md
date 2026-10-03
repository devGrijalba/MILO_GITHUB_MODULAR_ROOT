# EPISODE_ID CONTRACT

`episode_id` es la identidad secuencial del episodio dentro de la serie.

NO se deriva de seed_id.

Serie limpia:

- primer episodio → `EP0001`
- segundo → `EP0002`
- tercero → `EP0003`

Formato obligatorio:

`EP` + cuatro dígitos.

Regex conceptual:

`^EP[0-9]{4}$`

Prohibido:

- MILO-EP-S0001
- EP-MILO-S0001
- S0001
- cualquier ID derivado de la semilla.

Si no existe continuidad aprobada:
usar `EP0001`.

# MILO — SEED PRIORITY INDEX

Engine version: `7.0.1-MODULAR`

Este archivo evita escanear las 1000 semillas en cada generación.

## REGLA

La lista ya está prefiltrada con:

- `revision.elegible == true`
- `revision.compuesto >= 85`
- `revision.calidad >= 80`
- `revision.afinidad >= 85`

Orden:

1. `revision.compuesto` descendente
2. `seed_id` ascendente

El LLM debe seleccionar la primera seed compatible con `22_SERIES_STATE.md`.

No volver a calcular el ranking global durante cada episodio.

## PRIORIDAD

1. `MILO-S0001` | family `F001` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Plato tapado: la primera vez
2. `MILO-S0011` | family `F002` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Luz del pasillo: la primera vez
3. `MILO-S0021` | family `F003` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Zapatos reparados: la primera vez
4. `MILO-S0031` | family `F004` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Paraguas: la primera vez
5. `MILO-S0041` | family `F005` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Taza tibia: la primera vez
6. `MILO-S0051` | family `F006` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Madre y carga | Bolsa de compras: la primera vez
7. `MILO-S0071` | family `F008` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Madre y carga | Taza olvidada: la primera vez
8. `MILO-S0091` | family `F010` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Madre y carga | Canasta de ropa: la primera vez
9. `MILO-S0101` | family `F011` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Receta: la primera vez
10. `MILO-S0121` | family `F013` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Mantel: la primera vez
11. `MILO-S0131` | family `F014` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Radio: la primera vez
12. `MILO-S0141` | family `F015` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Fotografía: la primera vez
13. `MILO-S0151` | family `F016` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Frasco: la primera vez
14. `MILO-S0161` | family `F017` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Taburete: la primera vez
15. `MILO-S0171` | family `F018` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Lentes: la primera vez
16. `MILO-S0191` | family `F020` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Reloj: la primera vez
17. `MILO-S0201` | family `F021` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Puerta: la primera vez
18. `MILO-S0211` | family `F022` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Control remoto: la primera vez
19. `MILO-S0221` | family `F023` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Juguete compartido: la primera vez
20. `MILO-S0231` | family `F024` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Dos tazas: la primera vez
21. `MILO-S0241` | family `F025` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Caja de mudanza: la primera vez
22. `MILO-S0251` | family `F026` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Dibujo: la primera vez
23. `MILO-S0261` | family `F027` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Torre de bloques: la primera vez
24. `MILO-S0281` | family `F029` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Linterna: la primera vez
25. `MILO-S0291` | family `F030` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Rompecabezas: la primera vez
26. `MILO-S0301` | family `F031` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Teléfono: la primera vez
27. `MILO-S0321` | family `F033` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Ventana: la primera vez
28. `MILO-S0331` | family `F034` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Cuaderno: la primera vez
29. `MILO-S0341` | family `F035` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Reloj de cocina: la primera vez
30. `MILO-S0351` | family `F036` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Puerta cerrada: la primera vez
31. `MILO-S0361` | family `F037` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Teléfono boca abajo: la primera vez
32. `MILO-S0381` | family `F039` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Bolsa prestada: la primera vez
33. `MILO-S0391` | family `F040` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Calendario: la primera vez
34. `MILO-S0401` | family `F041` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Taza rota: la primera vez
35. `MILO-S0411` | family `F042` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Maceta caída: la primera vez
36. `MILO-S0421` | family `F043` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Llave perdida: la primera vez
37. `MILO-S0431` | family `F044` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Comida quemada: la primera vez
38. `MILO-S0441` | family `F045` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Costura: la primera vez
39. `MILO-S0461` | family `F047` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Mesa pequeña: la primera vez
40. `MILO-S0471` | family `F048` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Regalo sencillo: la primera vez
41. `MILO-S0481` | family `F049` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Foto familiar: la primera vez
42. `MILO-S0501` | family `F051` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Llavero: la primera vez
43. `MILO-S0511` | family `F052` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Cama preparada: la primera vez
44. `MILO-S0521` | family `F053` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Taza guardada: la primera vez
45. `MILO-S0541` | family `F055` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Perchero: la primera vez
46. `MILO-S0551` | family `F056` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Silla vacía: la primera vez
47. `MILO-S0561` | family `F057` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Taza sin usar: la primera vez
48. `MILO-S0571` | family `F058` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Prenda guardada: la primera vez
49. `MILO-S0581` | family `F059` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Receta heredada: la primera vez
50. `MILO-S0591` | family `F060` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Fotografía en cajón: la primera vez
51. `MILO-S0601` | family `F061` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Vaso de agua: la primera vez
52. `MILO-S0611` | family `F062` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Sofá: la primera vez
53. `MILO-S0621` | family `F063` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Llamada: la primera vez
54. `MILO-S0631` | family `F064` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Juego de mesa: la primera vez
55. `MILO-S0641` | family `F065` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Plato extra: la primera vez
56. `MILO-S0661` | family `F067` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Bandeja: la primera vez
57. `MILO-S0671` | family `F068` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Escoba: la primera vez
58. `MILO-S0691` | family `F070` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Almohada: la primera vez
59. `MILO-S0711` | family `F072` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lista: la primera vez
60. `MILO-S0721` | family `F073` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lámpara: la primera vez
61. `MILO-S0751` | family `F076` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Herramienta prestada: la primera vez
62. `MILO-S0761` | family `F077` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Plato lavado: la primera vez
63. `MILO-S0821` | family `F083` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Café de domingo: la primera vez
64. `MILO-S0841` | family `F085` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Luz de cocina: la primera vez
65. `MILO-S0851` | family `F086` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Control extraviado: la primera vez
66. `MILO-S0921` | family `F093` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mochila: la primera vez
67. `MILO-S0931` | family `F094` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Reloj detenido: la primera vez
68. `MILO-S0951` | family `F096` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Dos sillas: la primera vez
69. `MILO-S0961` | family `F097` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Taza entre manos: la primera vez
70. `MILO-S0971` | family `F098` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Puerta de entrada: la primera vez
71. `MILO-S0981` | family `F099` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Teléfono apagado: la primera vez
72. `MILO-S0991` | family `F100` | compuesto `88.75` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Mantel doblado: la primera vez
73. `MILO-R0002` | family `F001` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Plato tapado: la copia que no funcionó
74. `MILO-R0003` | family `F001` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Plato tapado: el favor convertido en deuda
75. `MILO-R0004` | family `F001` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Plato tapado: dos personas, dos necesidades
76. `MILO-R0005` | family `F001` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Plato tapado: el acuerdo que nadie había entendido
77. `MILO-R0006` | family `F001` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Plato tapado: la ayuda que cambió algo querido
78. `MILO-R0007` | family `F001` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Plato tapado: la pregunta que no quería hacer
79. `MILO-R0008` | family `F001` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Plato tapado: el recuerdo que tenían distinto
80. `MILO-R0009` | family `F001` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Plato tapado: el agradecimiento dicho demasiado tarde
81. `MILO-R0010` | family `F001` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Plato tapado: el cuidado que necesitó permiso
82. `MILO-R0012` | family `F002` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Luz del pasillo: la copia que no funcionó
83. `MILO-R0013` | family `F002` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Luz del pasillo: el favor convertido en deuda
84. `MILO-R0014` | family `F002` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Luz del pasillo: dos personas, dos necesidades
85. `MILO-R0015` | family `F002` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Luz del pasillo: el acuerdo que nadie había entendido
86. `MILO-R0016` | family `F002` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Luz del pasillo: la ayuda que cambió algo querido
87. `MILO-R0017` | family `F002` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Luz del pasillo: la pregunta que no quería hacer
88. `MILO-R0018` | family `F002` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Luz del pasillo: el recuerdo que tenían distinto
89. `MILO-R0019` | family `F002` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Luz del pasillo: el agradecimiento dicho demasiado tarde
90. `MILO-R0020` | family `F002` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Luz del pasillo: el cuidado que necesitó permiso
91. `MILO-R0022` | family `F003` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Zapatos reparados: la copia que no funcionó
92. `MILO-R0023` | family `F003` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Zapatos reparados: el favor convertido en deuda
93. `MILO-R0024` | family `F003` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Zapatos reparados: dos personas, dos necesidades
94. `MILO-R0025` | family `F003` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Zapatos reparados: el acuerdo que nadie había entendido
95. `MILO-R0026` | family `F003` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Zapatos reparados: la ayuda que cambió algo querido
96. `MILO-R0027` | family `F003` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Zapatos reparados: la pregunta que no quería hacer
97. `MILO-R0028` | family `F003` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Zapatos reparados: el recuerdo que tenían distinto
98. `MILO-R0029` | family `F003` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Zapatos reparados: el agradecimiento dicho demasiado tarde
99. `MILO-R0030` | family `F003` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Zapatos reparados: el cuidado que necesitó permiso
100. `MILO-R0032` | family `F004` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Paraguas: la copia que no funcionó
101. `MILO-R0033` | family `F004` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Paraguas: el favor convertido en deuda
102. `MILO-R0034` | family `F004` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Paraguas: dos personas, dos necesidades
103. `MILO-R0035` | family `F004` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Paraguas: el acuerdo que nadie había entendido
104. `MILO-R0036` | family `F004` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Paraguas: la ayuda que cambió algo querido
105. `MILO-R0037` | family `F004` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Paraguas: la pregunta que no quería hacer
106. `MILO-R0038` | family `F004` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Paraguas: el recuerdo que tenían distinto
107. `MILO-R0039` | family `F004` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Paraguas: el agradecimiento dicho demasiado tarde
108. `MILO-R0040` | family `F004` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Paraguas: el cuidado que necesitó permiso
109. `MILO-R0042` | family `F005` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Taza tibia: la copia que no funcionó
110. `MILO-R0043` | family `F005` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Taza tibia: el favor convertido en deuda
111. `MILO-R0044` | family `F005` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Taza tibia: dos personas, dos necesidades
112. `MILO-R0045` | family `F005` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Taza tibia: el acuerdo que nadie había entendido
113. `MILO-R0046` | family `F005` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Taza tibia: la ayuda que cambió algo querido
114. `MILO-R0047` | family `F005` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Taza tibia: la pregunta que no quería hacer
115. `MILO-R0048` | family `F005` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Taza tibia: el recuerdo que tenían distinto
116. `MILO-R0049` | family `F005` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Taza tibia: el agradecimiento dicho demasiado tarde
117. `MILO-R0050` | family `F005` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Padre y cariño | Taza tibia: el cuidado que necesitó permiso
118. `MILO-R0052` | family `F006` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Bolsa de compras: la copia que no funcionó
119. `MILO-R0053` | family `F006` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Bolsa de compras: el favor convertido en deuda
120. `MILO-R0054` | family `F006` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Bolsa de compras: dos personas, dos necesidades
121. `MILO-R0055` | family `F006` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Bolsa de compras: el acuerdo que nadie había entendido
122. `MILO-R0056` | family `F006` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Bolsa de compras: la ayuda que cambió algo querido
123. `MILO-R0057` | family `F006` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Bolsa de compras: la pregunta que no quería hacer
124. `MILO-R0058` | family `F006` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Bolsa de compras: el recuerdo que tenían distinto
125. `MILO-R0059` | family `F006` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Bolsa de compras: el agradecimiento dicho demasiado tarde
126. `MILO-R0060` | family `F006` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Bolsa de compras: el cuidado que necesitó permiso
127. `MILO-R0061` | family `F007` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Delantal: el gesto que llegó a la persona equivocada
128. `MILO-R0062` | family `F007` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Delantal: la copia que no funcionó
129. `MILO-R0063` | family `F007` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Delantal: el favor convertido en deuda
130. `MILO-R0064` | family `F007` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Delantal: dos personas, dos necesidades
131. `MILO-R0065` | family `F007` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Delantal: el acuerdo que nadie había entendido
132. `MILO-R0066` | family `F007` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Delantal: la ayuda que cambió algo querido
133. `MILO-R0067` | family `F007` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Delantal: la pregunta que no quería hacer
134. `MILO-R0068` | family `F007` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Delantal: el recuerdo que tenían distinto
135. `MILO-R0069` | family `F007` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Delantal: el agradecimiento dicho demasiado tarde
136. `MILO-R0070` | family `F007` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Delantal: el cuidado que necesitó permiso
137. `MILO-R0072` | family `F008` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Taza olvidada: la copia que no funcionó
138. `MILO-R0073` | family `F008` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Taza olvidada: el favor convertido en deuda
139. `MILO-R0074` | family `F008` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Taza olvidada: dos personas, dos necesidades
140. `MILO-R0075` | family `F008` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Taza olvidada: el acuerdo que nadie había entendido
141. `MILO-R0076` | family `F008` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Taza olvidada: la ayuda que cambió algo querido
142. `MILO-R0077` | family `F008` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Taza olvidada: la pregunta que no quería hacer
143. `MILO-R0078` | family `F008` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Taza olvidada: el recuerdo que tenían distinto
144. `MILO-R0079` | family `F008` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Taza olvidada: el agradecimiento dicho demasiado tarde
145. `MILO-R0080` | family `F008` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Taza olvidada: el cuidado que necesitó permiso
146. `MILO-R0081` | family `F009` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Silla de cocina: el gesto que llegó a la persona equivocada
147. `MILO-R0082` | family `F009` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Silla de cocina: la copia que no funcionó
148. `MILO-R0083` | family `F009` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Silla de cocina: el favor convertido en deuda
149. `MILO-R0084` | family `F009` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Silla de cocina: dos personas, dos necesidades
150. `MILO-R0085` | family `F009` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Silla de cocina: el acuerdo que nadie había entendido
151. `MILO-R0086` | family `F009` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Silla de cocina: la ayuda que cambió algo querido
152. `MILO-R0087` | family `F009` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Silla de cocina: la pregunta que no quería hacer
153. `MILO-R0088` | family `F009` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Silla de cocina: el recuerdo que tenían distinto
154. `MILO-R0089` | family `F009` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Silla de cocina: el agradecimiento dicho demasiado tarde
155. `MILO-R0090` | family `F009` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Silla de cocina: el cuidado que necesitó permiso
156. `MILO-R0092` | family `F010` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Canasta de ropa: la copia que no funcionó
157. `MILO-R0093` | family `F010` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Canasta de ropa: el favor convertido en deuda
158. `MILO-R0094` | family `F010` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Canasta de ropa: dos personas, dos necesidades
159. `MILO-R0095` | family `F010` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Canasta de ropa: el acuerdo que nadie había entendido
160. `MILO-R0096` | family `F010` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Canasta de ropa: la ayuda que cambió algo querido
161. `MILO-R0097` | family `F010` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Canasta de ropa: la pregunta que no quería hacer
162. `MILO-R0098` | family `F010` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Canasta de ropa: el recuerdo que tenían distinto
163. `MILO-R0099` | family `F010` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Canasta de ropa: el agradecimiento dicho demasiado tarde
164. `MILO-R0100` | family `F010` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Madre y carga | Canasta de ropa: el cuidado que necesitó permiso
165. `MILO-R0102` | family `F011` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Receta: la copia que no funcionó
166. `MILO-R0103` | family `F011` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Receta: el favor convertido en deuda
167. `MILO-R0104` | family `F011` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Receta: dos personas, dos necesidades
168. `MILO-R0105` | family `F011` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Receta: el acuerdo que nadie había entendido
169. `MILO-R0106` | family `F011` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Receta: la ayuda que cambió algo querido
170. `MILO-R0107` | family `F011` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Receta: la pregunta que no quería hacer
171. `MILO-R0108` | family `F011` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Receta: el recuerdo que tenían distinto
172. `MILO-R0109` | family `F011` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Receta: el agradecimiento dicho demasiado tarde
173. `MILO-R0110` | family `F011` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Receta: el cuidado que necesitó permiso
174. `MILO-R0111` | family `F012` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Caja de botones: el gesto que llegó a la persona equivocada
175. `MILO-R0112` | family `F012` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Caja de botones: la copia que no funcionó
176. `MILO-R0113` | family `F012` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Caja de botones: el favor convertido en deuda
177. `MILO-R0114` | family `F012` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Caja de botones: dos personas, dos necesidades
178. `MILO-R0115` | family `F012` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Caja de botones: el acuerdo que nadie había entendido
179. `MILO-R0116` | family `F012` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Caja de botones: la ayuda que cambió algo querido
180. `MILO-R0117` | family `F012` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Caja de botones: la pregunta que no quería hacer
181. `MILO-R0118` | family `F012` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Caja de botones: el recuerdo que tenían distinto
182. `MILO-R0119` | family `F012` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Caja de botones: el agradecimiento dicho demasiado tarde
183. `MILO-R0120` | family `F012` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Caja de botones: el cuidado que necesitó permiso
184. `MILO-R0122` | family `F013` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Mantel: la copia que no funcionó
185. `MILO-R0123` | family `F013` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Mantel: el favor convertido en deuda
186. `MILO-R0124` | family `F013` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Mantel: dos personas, dos necesidades
187. `MILO-R0125` | family `F013` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Mantel: el acuerdo que nadie había entendido
188. `MILO-R0126` | family `F013` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Mantel: la ayuda que cambió algo querido
189. `MILO-R0127` | family `F013` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Mantel: la pregunta que no quería hacer
190. `MILO-R0128` | family `F013` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Mantel: el recuerdo que tenían distinto
191. `MILO-R0129` | family `F013` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Mantel: el agradecimiento dicho demasiado tarde
192. `MILO-R0130` | family `F013` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Mantel: el cuidado que necesitó permiso
193. `MILO-R0132` | family `F014` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Radio: la copia que no funcionó
194. `MILO-R0133` | family `F014` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Radio: el favor convertido en deuda
195. `MILO-R0134` | family `F014` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Radio: dos personas, dos necesidades
196. `MILO-R0135` | family `F014` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Radio: el acuerdo que nadie había entendido
197. `MILO-R0136` | family `F014` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Radio: la ayuda que cambió algo querido
198. `MILO-R0137` | family `F014` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Radio: la pregunta que no quería hacer
199. `MILO-R0138` | family `F014` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Radio: el recuerdo que tenían distinto
200. `MILO-R0139` | family `F014` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Radio: el agradecimiento dicho demasiado tarde
201. `MILO-R0140` | family `F014` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Radio: el cuidado que necesitó permiso
202. `MILO-R0142` | family `F015` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Fotografía: la copia que no funcionó
203. `MILO-R0143` | family `F015` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Fotografía: el favor convertido en deuda
204. `MILO-R0144` | family `F015` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Fotografía: dos personas, dos necesidades
205. `MILO-R0145` | family `F015` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Fotografía: el acuerdo que nadie había entendido
206. `MILO-R0146` | family `F015` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Fotografía: la ayuda que cambió algo querido
207. `MILO-R0147` | family `F015` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Fotografía: la pregunta que no quería hacer
208. `MILO-R0148` | family `F015` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Fotografía: el recuerdo que tenían distinto
209. `MILO-R0149` | family `F015` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Fotografía: el agradecimiento dicho demasiado tarde
210. `MILO-R0150` | family `F015` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuela y memoria | Fotografía: el cuidado que necesitó permiso
211. `MILO-R0152` | family `F016` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Frasco: la copia que no funcionó
212. `MILO-R0153` | family `F016` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Frasco: el favor convertido en deuda
213. `MILO-R0154` | family `F016` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Frasco: dos personas, dos necesidades
214. `MILO-R0155` | family `F016` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Frasco: el acuerdo que nadie había entendido
215. `MILO-R0156` | family `F016` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Frasco: la ayuda que cambió algo querido
216. `MILO-R0157` | family `F016` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Frasco: la pregunta que no quería hacer
217. `MILO-R0158` | family `F016` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Frasco: el recuerdo que tenían distinto
218. `MILO-R0159` | family `F016` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Frasco: el agradecimiento dicho demasiado tarde
219. `MILO-R0160` | family `F016` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Frasco: el cuidado que necesitó permiso
220. `MILO-R0162` | family `F017` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Taburete: la copia que no funcionó
221. `MILO-R0163` | family `F017` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Taburete: el favor convertido en deuda
222. `MILO-R0164` | family `F017` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Taburete: dos personas, dos necesidades
223. `MILO-R0165` | family `F017` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Taburete: el acuerdo que nadie había entendido
224. `MILO-R0166` | family `F017` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Taburete: la ayuda que cambió algo querido
225. `MILO-R0167` | family `F017` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Taburete: la pregunta que no quería hacer
226. `MILO-R0168` | family `F017` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Taburete: el recuerdo que tenían distinto
227. `MILO-R0169` | family `F017` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Taburete: el agradecimiento dicho demasiado tarde
228. `MILO-R0170` | family `F017` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Taburete: el cuidado que necesitó permiso
229. `MILO-R0172` | family `F018` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Lentes: la copia que no funcionó
230. `MILO-R0173` | family `F018` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Lentes: el favor convertido en deuda
231. `MILO-R0174` | family `F018` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Lentes: dos personas, dos necesidades
232. `MILO-R0175` | family `F018` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Lentes: el acuerdo que nadie había entendido
233. `MILO-R0176` | family `F018` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Lentes: la ayuda que cambió algo querido
234. `MILO-R0177` | family `F018` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Lentes: la pregunta que no quería hacer
235. `MILO-R0178` | family `F018` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Lentes: el recuerdo que tenían distinto
236. `MILO-R0179` | family `F018` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Lentes: el agradecimiento dicho demasiado tarde
237. `MILO-R0180` | family `F018` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Lentes: el cuidado que necesitó permiso
238. `MILO-R0181` | family `F019` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Maceta: el gesto que llegó a la persona equivocada
239. `MILO-R0182` | family `F019` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Maceta: la copia que no funcionó
240. `MILO-R0183` | family `F019` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Maceta: el favor convertido en deuda
241. `MILO-R0184` | family `F019` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Maceta: dos personas, dos necesidades
242. `MILO-R0185` | family `F019` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Maceta: el acuerdo que nadie había entendido
243. `MILO-R0186` | family `F019` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Maceta: la ayuda que cambió algo querido
244. `MILO-R0187` | family `F019` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Maceta: la pregunta que no quería hacer
245. `MILO-R0188` | family `F019` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Maceta: el recuerdo que tenían distinto
246. `MILO-R0189` | family `F019` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Maceta: el agradecimiento dicho demasiado tarde
247. `MILO-R0190` | family `F019` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Maceta: el cuidado que necesitó permiso
248. `MILO-R0192` | family `F020` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Reloj: la copia que no funcionó
249. `MILO-R0193` | family `F020` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Reloj: el favor convertido en deuda
250. `MILO-R0194` | family `F020` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Reloj: dos personas, dos necesidades
251. `MILO-R0195` | family `F020` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Reloj: el acuerdo que nadie había entendido
252. `MILO-R0196` | family `F020` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Reloj: la ayuda que cambió algo querido
253. `MILO-R0197` | family `F020` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Reloj: la pregunta que no quería hacer
254. `MILO-R0198` | family `F020` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Reloj: el recuerdo que tenían distinto
255. `MILO-R0199` | family `F020` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Reloj: el agradecimiento dicho demasiado tarde
256. `MILO-R0200` | family `F020` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Abuelo y autonomía | Reloj: el cuidado que necesitó permiso
257. `MILO-R0202` | family `F021` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Puerta: la copia que no funcionó
258. `MILO-R0203` | family `F021` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Puerta: el favor convertido en deuda
259. `MILO-R0204` | family `F021` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Puerta: dos personas, dos necesidades
260. `MILO-R0205` | family `F021` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Puerta: el acuerdo que nadie había entendido
261. `MILO-R0206` | family `F021` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Puerta: la ayuda que cambió algo querido
262. `MILO-R0207` | family `F021` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Puerta: la pregunta que no quería hacer
263. `MILO-R0208` | family `F021` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Puerta: el recuerdo que tenían distinto
264. `MILO-R0209` | family `F021` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Puerta: el agradecimiento dicho demasiado tarde
265. `MILO-R0210` | family `F021` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Puerta: el cuidado que necesitó permiso
266. `MILO-R0212` | family `F022` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Control remoto: la copia que no funcionó
267. `MILO-R0213` | family `F022` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Control remoto: el favor convertido en deuda
268. `MILO-R0214` | family `F022` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Control remoto: dos personas, dos necesidades
269. `MILO-R0215` | family `F022` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Control remoto: el acuerdo que nadie había entendido
270. `MILO-R0216` | family `F022` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Control remoto: la ayuda que cambió algo querido
271. `MILO-R0217` | family `F022` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Control remoto: la pregunta que no quería hacer
272. `MILO-R0218` | family `F022` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Control remoto: el recuerdo que tenían distinto
273. `MILO-R0219` | family `F022` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Control remoto: el agradecimiento dicho demasiado tarde
274. `MILO-R0220` | family `F022` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Control remoto: el cuidado que necesitó permiso
275. `MILO-R0222` | family `F023` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Juguete compartido: la copia que no funcionó
276. `MILO-R0223` | family `F023` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Juguete compartido: el favor convertido en deuda
277. `MILO-R0224` | family `F023` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Juguete compartido: dos personas, dos necesidades
278. `MILO-R0225` | family `F023` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Juguete compartido: el acuerdo que nadie había entendido
279. `MILO-R0226` | family `F023` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Juguete compartido: la ayuda que cambió algo querido
280. `MILO-R0227` | family `F023` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Juguete compartido: la pregunta que no quería hacer
281. `MILO-R0228` | family `F023` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Juguete compartido: el recuerdo que tenían distinto
282. `MILO-R0229` | family `F023` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Juguete compartido: el agradecimiento dicho demasiado tarde
283. `MILO-R0230` | family `F023` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Juguete compartido: el cuidado que necesitó permiso
284. `MILO-R0232` | family `F024` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Dos tazas: la copia que no funcionó
285. `MILO-R0233` | family `F024` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Dos tazas: el favor convertido en deuda
286. `MILO-R0234` | family `F024` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Dos tazas: dos personas, dos necesidades
287. `MILO-R0235` | family `F024` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Dos tazas: el acuerdo que nadie había entendido
288. `MILO-R0236` | family `F024` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Dos tazas: la ayuda que cambió algo querido
289. `MILO-R0237` | family `F024` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Dos tazas: la pregunta que no quería hacer
290. `MILO-R0238` | family `F024` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Dos tazas: el recuerdo que tenían distinto
291. `MILO-R0239` | family `F024` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Dos tazas: el agradecimiento dicho demasiado tarde
292. `MILO-R0240` | family `F024` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Dos tazas: el cuidado que necesitó permiso
293. `MILO-R0242` | family `F025` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Caja de mudanza: la copia que no funcionó
294. `MILO-R0243` | family `F025` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Caja de mudanza: el favor convertido en deuda
295. `MILO-R0244` | family `F025` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Caja de mudanza: dos personas, dos necesidades
296. `MILO-R0245` | family `F025` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Caja de mudanza: el acuerdo que nadie había entendido
297. `MILO-R0246` | family `F025` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Caja de mudanza: la ayuda que cambió algo querido
298. `MILO-R0247` | family `F025` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Caja de mudanza: la pregunta que no quería hacer
299. `MILO-R0248` | family `F025` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Caja de mudanza: el recuerdo que tenían distinto
300. `MILO-R0249` | family `F025` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Caja de mudanza: el agradecimiento dicho demasiado tarde
301. `MILO-R0250` | family `F025` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Hermanos y distancia | Caja de mudanza: el cuidado que necesitó permiso
302. `MILO-R0252` | family `F026` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Dibujo: la copia que no funcionó
303. `MILO-R0253` | family `F026` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Dibujo: el favor convertido en deuda
304. `MILO-R0254` | family `F026` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Dibujo: dos personas, dos necesidades
305. `MILO-R0255` | family `F026` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Dibujo: el acuerdo que nadie había entendido
306. `MILO-R0256` | family `F026` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Dibujo: la ayuda que cambió algo querido
307. `MILO-R0257` | family `F026` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Dibujo: la pregunta que no quería hacer
308. `MILO-R0258` | family `F026` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Dibujo: el recuerdo que tenían distinto
309. `MILO-R0259` | family `F026` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Dibujo: el agradecimiento dicho demasiado tarde
310. `MILO-R0260` | family `F026` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Dibujo: el cuidado que necesitó permiso
311. `MILO-R0262` | family `F027` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Torre de bloques: la copia que no funcionó
312. `MILO-R0263` | family `F027` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Torre de bloques: el favor convertido en deuda
313. `MILO-R0264` | family `F027` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Torre de bloques: dos personas, dos necesidades
314. `MILO-R0265` | family `F027` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Torre de bloques: el acuerdo que nadie había entendido
315. `MILO-R0266` | family `F027` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Torre de bloques: la ayuda que cambió algo querido
316. `MILO-R0267` | family `F027` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Torre de bloques: la pregunta que no quería hacer
317. `MILO-R0268` | family `F027` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Torre de bloques: el recuerdo que tenían distinto
318. `MILO-R0269` | family `F027` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Torre de bloques: el agradecimiento dicho demasiado tarde
319. `MILO-R0270` | family `F027` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Torre de bloques: el cuidado que necesitó permiso
320. `MILO-R0271` | family `F028` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Peluche: el gesto que llegó a la persona equivocada
321. `MILO-R0272` | family `F028` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Peluche: la copia que no funcionó
322. `MILO-R0273` | family `F028` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Peluche: el favor convertido en deuda
323. `MILO-R0274` | family `F028` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Peluche: dos personas, dos necesidades
324. `MILO-R0275` | family `F028` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Peluche: el acuerdo que nadie había entendido
325. `MILO-R0276` | family `F028` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Peluche: la ayuda que cambió algo querido
326. `MILO-R0277` | family `F028` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Peluche: la pregunta que no quería hacer
327. `MILO-R0278` | family `F028` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Peluche: el recuerdo que tenían distinto
328. `MILO-R0279` | family `F028` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Peluche: el agradecimiento dicho demasiado tarde
329. `MILO-R0280` | family `F028` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Peluche: el cuidado que necesitó permiso
330. `MILO-R0282` | family `F029` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Linterna: la copia que no funcionó
331. `MILO-R0283` | family `F029` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Linterna: el favor convertido en deuda
332. `MILO-R0284` | family `F029` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Linterna: dos personas, dos necesidades
333. `MILO-R0285` | family `F029` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Linterna: el acuerdo que nadie había entendido
334. `MILO-R0286` | family `F029` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Linterna: la ayuda que cambió algo querido
335. `MILO-R0287` | family `F029` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Linterna: la pregunta que no quería hacer
336. `MILO-R0288` | family `F029` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Linterna: el recuerdo que tenían distinto
337. `MILO-R0289` | family `F029` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Linterna: el agradecimiento dicho demasiado tarde
338. `MILO-R0290` | family `F029` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Linterna: el cuidado que necesitó permiso
339. `MILO-R0292` | family `F030` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Rompecabezas: la copia que no funcionó
340. `MILO-R0293` | family `F030` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Rompecabezas: el favor convertido en deuda
341. `MILO-R0294` | family `F030` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Rompecabezas: dos personas, dos necesidades
342. `MILO-R0295` | family `F030` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Rompecabezas: el acuerdo que nadie había entendido
343. `MILO-R0296` | family `F030` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Rompecabezas: la ayuda que cambió algo querido
344. `MILO-R0297` | family `F030` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Rompecabezas: la pregunta que no quería hacer
345. `MILO-R0298` | family `F030` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Rompecabezas: el recuerdo que tenían distinto
346. `MILO-R0299` | family `F030` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Rompecabezas: el agradecimiento dicho demasiado tarde
347. `MILO-R0300` | family `F030` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Infancia y escucha | Rompecabezas: el cuidado que necesitó permiso
348. `MILO-R0302` | family `F031` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Teléfono: la copia que no funcionó
349. `MILO-R0303` | family `F031` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Teléfono: el favor convertido en deuda
350. `MILO-R0304` | family `F031` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Teléfono: dos personas, dos necesidades
351. `MILO-R0305` | family `F031` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Teléfono: el acuerdo que nadie había entendido
352. `MILO-R0306` | family `F031` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Teléfono: la ayuda que cambió algo querido
353. `MILO-R0307` | family `F031` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Teléfono: la pregunta que no quería hacer
354. `MILO-R0308` | family `F031` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Teléfono: el recuerdo que tenían distinto
355. `MILO-R0309` | family `F031` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Teléfono: el agradecimiento dicho demasiado tarde
356. `MILO-R0310` | family `F031` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Teléfono: el cuidado que necesitó permiso
357. `MILO-R0311` | family `F032` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Llaves: el gesto que llegó a la persona equivocada
358. `MILO-R0312` | family `F032` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Llaves: la copia que no funcionó
359. `MILO-R0313` | family `F032` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Llaves: el favor convertido en deuda
360. `MILO-R0314` | family `F032` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Llaves: dos personas, dos necesidades
361. `MILO-R0315` | family `F032` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Llaves: el acuerdo que nadie había entendido
362. `MILO-R0316` | family `F032` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Llaves: la ayuda que cambió algo querido
363. `MILO-R0317` | family `F032` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Llaves: la pregunta que no quería hacer
364. `MILO-R0318` | family `F032` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Llaves: el recuerdo que tenían distinto
365. `MILO-R0319` | family `F032` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Llaves: el agradecimiento dicho demasiado tarde
366. `MILO-R0320` | family `F032` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Llaves: el cuidado que necesitó permiso
367. `MILO-R0322` | family `F033` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Ventana: la copia que no funcionó
368. `MILO-R0323` | family `F033` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Ventana: el favor convertido en deuda
369. `MILO-R0324` | family `F033` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Ventana: dos personas, dos necesidades
370. `MILO-R0325` | family `F033` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Ventana: el acuerdo que nadie había entendido
371. `MILO-R0326` | family `F033` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Ventana: la ayuda que cambió algo querido
372. `MILO-R0327` | family `F033` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Ventana: la pregunta que no quería hacer
373. `MILO-R0328` | family `F033` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Ventana: el recuerdo que tenían distinto
374. `MILO-R0329` | family `F033` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Ventana: el agradecimiento dicho demasiado tarde
375. `MILO-R0330` | family `F033` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Ventana: el cuidado que necesitó permiso
376. `MILO-R0332` | family `F034` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Cuaderno: la copia que no funcionó
377. `MILO-R0333` | family `F034` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Cuaderno: el favor convertido en deuda
378. `MILO-R0334` | family `F034` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Cuaderno: dos personas, dos necesidades
379. `MILO-R0335` | family `F034` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Cuaderno: el acuerdo que nadie había entendido
380. `MILO-R0336` | family `F034` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Cuaderno: la ayuda que cambió algo querido
381. `MILO-R0337` | family `F034` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Cuaderno: la pregunta que no quería hacer
382. `MILO-R0338` | family `F034` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Cuaderno: el recuerdo que tenían distinto
383. `MILO-R0339` | family `F034` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Cuaderno: el agradecimiento dicho demasiado tarde
384. `MILO-R0340` | family `F034` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Cuaderno: el cuidado que necesitó permiso
385. `MILO-R0342` | family `F035` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Reloj de cocina: la copia que no funcionó
386. `MILO-R0343` | family `F035` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Reloj de cocina: el favor convertido en deuda
387. `MILO-R0344` | family `F035` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Reloj de cocina: dos personas, dos necesidades
388. `MILO-R0345` | family `F035` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Reloj de cocina: el acuerdo que nadie había entendido
389. `MILO-R0346` | family `F035` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Reloj de cocina: la ayuda que cambió algo querido
390. `MILO-R0347` | family `F035` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Reloj de cocina: la pregunta que no quería hacer
391. `MILO-R0348` | family `F035` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Reloj de cocina: el recuerdo que tenían distinto
392. `MILO-R0349` | family `F035` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Reloj de cocina: el agradecimiento dicho demasiado tarde
393. `MILO-R0350` | family `F035` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Sobrepensamiento | Reloj de cocina: el cuidado que necesitó permiso
394. `MILO-R0352` | family `F036` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Puerta cerrada: la copia que no funcionó
395. `MILO-R0353` | family `F036` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Puerta cerrada: el favor convertido en deuda
396. `MILO-R0354` | family `F036` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Puerta cerrada: dos personas, dos necesidades
397. `MILO-R0355` | family `F036` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Puerta cerrada: el acuerdo que nadie había entendido
398. `MILO-R0356` | family `F036` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Puerta cerrada: la ayuda que cambió algo querido
399. `MILO-R0357` | family `F036` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Puerta cerrada: la pregunta que no quería hacer
400. `MILO-R0358` | family `F036` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Puerta cerrada: el recuerdo que tenían distinto
401. `MILO-R0359` | family `F036` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Puerta cerrada: el agradecimiento dicho demasiado tarde
402. `MILO-R0360` | family `F036` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Puerta cerrada: el cuidado que necesitó permiso
403. `MILO-R0362` | family `F037` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Teléfono boca abajo: la copia que no funcionó
404. `MILO-R0363` | family `F037` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Teléfono boca abajo: el favor convertido en deuda
405. `MILO-R0364` | family `F037` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Teléfono boca abajo: dos personas, dos necesidades
406. `MILO-R0365` | family `F037` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Teléfono boca abajo: el acuerdo que nadie había entendido
407. `MILO-R0366` | family `F037` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Teléfono boca abajo: la ayuda que cambió algo querido
408. `MILO-R0367` | family `F037` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Teléfono boca abajo: la pregunta que no quería hacer
409. `MILO-R0368` | family `F037` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Teléfono boca abajo: el recuerdo que tenían distinto
410. `MILO-R0369` | family `F037` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Teléfono boca abajo: el agradecimiento dicho demasiado tarde
411. `MILO-R0370` | family `F037` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Teléfono boca abajo: el cuidado que necesitó permiso
412. `MILO-R0371` | family `F038` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Silla: el gesto que llegó a la persona equivocada
413. `MILO-R0372` | family `F038` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Silla: la copia que no funcionó
414. `MILO-R0373` | family `F038` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Silla: el favor convertido en deuda
415. `MILO-R0374` | family `F038` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Silla: dos personas, dos necesidades
416. `MILO-R0375` | family `F038` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Silla: el acuerdo que nadie había entendido
417. `MILO-R0376` | family `F038` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Silla: la ayuda que cambió algo querido
418. `MILO-R0377` | family `F038` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Silla: la pregunta que no quería hacer
419. `MILO-R0378` | family `F038` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Silla: el recuerdo que tenían distinto
420. `MILO-R0379` | family `F038` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Silla: el agradecimiento dicho demasiado tarde
421. `MILO-R0380` | family `F038` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Silla: el cuidado que necesitó permiso
422. `MILO-R0382` | family `F039` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Bolsa prestada: la copia que no funcionó
423. `MILO-R0383` | family `F039` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Bolsa prestada: el favor convertido en deuda
424. `MILO-R0384` | family `F039` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Bolsa prestada: dos personas, dos necesidades
425. `MILO-R0385` | family `F039` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Bolsa prestada: el acuerdo que nadie había entendido
426. `MILO-R0386` | family `F039` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Bolsa prestada: la ayuda que cambió algo querido
427. `MILO-R0387` | family `F039` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Bolsa prestada: la pregunta que no quería hacer
428. `MILO-R0388` | family `F039` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Bolsa prestada: el recuerdo que tenían distinto
429. `MILO-R0389` | family `F039` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Bolsa prestada: el agradecimiento dicho demasiado tarde
430. `MILO-R0390` | family `F039` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Bolsa prestada: el cuidado que necesitó permiso
431. `MILO-R0392` | family `F040` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Calendario: la copia que no funcionó
432. `MILO-R0393` | family `F040` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Calendario: el favor convertido en deuda
433. `MILO-R0394` | family `F040` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Calendario: dos personas, dos necesidades
434. `MILO-R0395` | family `F040` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Calendario: el acuerdo que nadie había entendido
435. `MILO-R0396` | family `F040` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Calendario: la ayuda que cambió algo querido
436. `MILO-R0397` | family `F040` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Calendario: la pregunta que no quería hacer
437. `MILO-R0398` | family `F040` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Calendario: el recuerdo que tenían distinto
438. `MILO-R0399` | family `F040` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Calendario: el agradecimiento dicho demasiado tarde
439. `MILO-R0400` | family `F040` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Límites cotidianos | Calendario: el cuidado que necesitó permiso
440. `MILO-R0402` | family `F041` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Taza rota: la copia que no funcionó
441. `MILO-R0403` | family `F041` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Taza rota: el favor convertido en deuda
442. `MILO-R0404` | family `F041` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Taza rota: dos personas, dos necesidades
443. `MILO-R0405` | family `F041` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Taza rota: el acuerdo que nadie había entendido
444. `MILO-R0406` | family `F041` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Taza rota: la ayuda que cambió algo querido
445. `MILO-R0407` | family `F041` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Taza rota: la pregunta que no quería hacer
446. `MILO-R0408` | family `F041` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Taza rota: el recuerdo que tenían distinto
447. `MILO-R0409` | family `F041` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Taza rota: el agradecimiento dicho demasiado tarde
448. `MILO-R0410` | family `F041` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Taza rota: el cuidado que necesitó permiso
449. `MILO-R0412` | family `F042` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Maceta caída: la copia que no funcionó
450. `MILO-R0413` | family `F042` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Maceta caída: el favor convertido en deuda
451. `MILO-R0414` | family `F042` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Maceta caída: dos personas, dos necesidades
452. `MILO-R0415` | family `F042` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Maceta caída: el acuerdo que nadie había entendido
453. `MILO-R0416` | family `F042` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Maceta caída: la ayuda que cambió algo querido
454. `MILO-R0417` | family `F042` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Maceta caída: la pregunta que no quería hacer
455. `MILO-R0418` | family `F042` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Maceta caída: el recuerdo que tenían distinto
456. `MILO-R0419` | family `F042` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Maceta caída: el agradecimiento dicho demasiado tarde
457. `MILO-R0420` | family `F042` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Maceta caída: el cuidado que necesitó permiso
458. `MILO-R0422` | family `F043` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Llave perdida: la copia que no funcionó
459. `MILO-R0423` | family `F043` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Llave perdida: el favor convertido en deuda
460. `MILO-R0424` | family `F043` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Llave perdida: dos personas, dos necesidades
461. `MILO-R0425` | family `F043` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Llave perdida: el acuerdo que nadie había entendido
462. `MILO-R0426` | family `F043` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Llave perdida: la ayuda que cambió algo querido
463. `MILO-R0427` | family `F043` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Llave perdida: la pregunta que no quería hacer
464. `MILO-R0428` | family `F043` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Llave perdida: el recuerdo que tenían distinto
465. `MILO-R0429` | family `F043` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Llave perdida: el agradecimiento dicho demasiado tarde
466. `MILO-R0430` | family `F043` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Llave perdida: el cuidado que necesitó permiso
467. `MILO-R0432` | family `F044` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Comida quemada: la copia que no funcionó
468. `MILO-R0433` | family `F044` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Comida quemada: el favor convertido en deuda
469. `MILO-R0434` | family `F044` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Comida quemada: dos personas, dos necesidades
470. `MILO-R0435` | family `F044` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Comida quemada: el acuerdo que nadie había entendido
471. `MILO-R0436` | family `F044` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Comida quemada: la ayuda que cambió algo querido
472. `MILO-R0437` | family `F044` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Comida quemada: la pregunta que no quería hacer
473. `MILO-R0438` | family `F044` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Comida quemada: el recuerdo que tenían distinto
474. `MILO-R0439` | family `F044` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Comida quemada: el agradecimiento dicho demasiado tarde
475. `MILO-R0440` | family `F044` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Comida quemada: el cuidado que necesitó permiso
476. `MILO-R0442` | family `F045` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Costura: la copia que no funcionó
477. `MILO-R0443` | family `F045` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Costura: el favor convertido en deuda
478. `MILO-R0444` | family `F045` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Costura: dos personas, dos necesidades
479. `MILO-R0445` | family `F045` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Costura: el acuerdo que nadie había entendido
480. `MILO-R0446` | family `F045` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Costura: la ayuda que cambió algo querido
481. `MILO-R0447` | family `F045` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Costura: la pregunta que no quería hacer
482. `MILO-R0448` | family `F045` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Costura: el recuerdo que tenían distinto
483. `MILO-R0449` | family `F045` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Costura: el agradecimiento dicho demasiado tarde
484. `MILO-R0450` | family `F045` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Errores y reparación | Costura: el cuidado que necesitó permiso
485. `MILO-R0451` | family `F046` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Espejo: el gesto que llegó a la persona equivocada
486. `MILO-R0452` | family `F046` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Espejo: la copia que no funcionó
487. `MILO-R0453` | family `F046` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Espejo: el favor convertido en deuda
488. `MILO-R0454` | family `F046` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Espejo: dos personas, dos necesidades
489. `MILO-R0455` | family `F046` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Espejo: el acuerdo que nadie había entendido
490. `MILO-R0456` | family `F046` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Espejo: la ayuda que cambió algo querido
491. `MILO-R0457` | family `F046` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Espejo: la pregunta que no quería hacer
492. `MILO-R0458` | family `F046` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Espejo: el recuerdo que tenían distinto
493. `MILO-R0459` | family `F046` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Espejo: el agradecimiento dicho demasiado tarde
494. `MILO-R0460` | family `F046` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Espejo: el cuidado que necesitó permiso
495. `MILO-R0462` | family `F047` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Mesa pequeña: la copia que no funcionó
496. `MILO-R0463` | family `F047` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Mesa pequeña: el favor convertido en deuda
497. `MILO-R0464` | family `F047` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Mesa pequeña: dos personas, dos necesidades
498. `MILO-R0465` | family `F047` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Mesa pequeña: el acuerdo que nadie había entendido
499. `MILO-R0466` | family `F047` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Mesa pequeña: la ayuda que cambió algo querido
500. `MILO-R0467` | family `F047` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Mesa pequeña: la pregunta que no quería hacer
501. `MILO-R0468` | family `F047` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Mesa pequeña: el recuerdo que tenían distinto
502. `MILO-R0469` | family `F047` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Mesa pequeña: el agradecimiento dicho demasiado tarde
503. `MILO-R0470` | family `F047` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Mesa pequeña: el cuidado que necesitó permiso
504. `MILO-R0472` | family `F048` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Regalo sencillo: la copia que no funcionó
505. `MILO-R0473` | family `F048` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Regalo sencillo: el favor convertido en deuda
506. `MILO-R0474` | family `F048` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Regalo sencillo: dos personas, dos necesidades
507. `MILO-R0475` | family `F048` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Regalo sencillo: el acuerdo que nadie había entendido
508. `MILO-R0476` | family `F048` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Regalo sencillo: la ayuda que cambió algo querido
509. `MILO-R0477` | family `F048` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Regalo sencillo: la pregunta que no quería hacer
510. `MILO-R0478` | family `F048` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Regalo sencillo: el recuerdo que tenían distinto
511. `MILO-R0479` | family `F048` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Regalo sencillo: el agradecimiento dicho demasiado tarde
512. `MILO-R0480` | family `F048` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Regalo sencillo: el cuidado que necesitó permiso
513. `MILO-R0482` | family `F049` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Foto familiar: la copia que no funcionó
514. `MILO-R0483` | family `F049` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Foto familiar: el favor convertido en deuda
515. `MILO-R0484` | family `F049` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Foto familiar: dos personas, dos necesidades
516. `MILO-R0485` | family `F049` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Foto familiar: el acuerdo que nadie había entendido
517. `MILO-R0486` | family `F049` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Foto familiar: la ayuda que cambió algo querido
518. `MILO-R0487` | family `F049` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Foto familiar: la pregunta que no quería hacer
519. `MILO-R0488` | family `F049` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Foto familiar: el recuerdo que tenían distinto
520. `MILO-R0489` | family `F049` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Foto familiar: el agradecimiento dicho demasiado tarde
521. `MILO-R0490` | family `F049` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Foto familiar: el cuidado que necesitó permiso
522. `MILO-R0491` | family `F050` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Zapato gastado: el gesto que llegó a la persona equivocada
523. `MILO-R0492` | family `F050` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Zapato gastado: la copia que no funcionó
524. `MILO-R0493` | family `F050` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Zapato gastado: el favor convertido en deuda
525. `MILO-R0494` | family `F050` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Zapato gastado: dos personas, dos necesidades
526. `MILO-R0495` | family `F050` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Zapato gastado: el acuerdo que nadie había entendido
527. `MILO-R0496` | family `F050` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Zapato gastado: la ayuda que cambió algo querido
528. `MILO-R0497` | family `F050` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Zapato gastado: la pregunta que no quería hacer
529. `MILO-R0498` | family `F050` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Zapato gastado: el recuerdo que tenían distinto
530. `MILO-R0499` | family `F050` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Zapato gastado: el agradecimiento dicho demasiado tarde
531. `MILO-R0500` | family `F050` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Vergüenza y comparación | Zapato gastado: el cuidado que necesitó permiso
532. `MILO-R0502` | family `F051` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Llavero: la copia que no funcionó
533. `MILO-R0503` | family `F051` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Llavero: el favor convertido en deuda
534. `MILO-R0504` | family `F051` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Llavero: dos personas, dos necesidades
535. `MILO-R0505` | family `F051` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Llavero: el acuerdo que nadie había entendido
536. `MILO-R0506` | family `F051` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Llavero: la ayuda que cambió algo querido
537. `MILO-R0507` | family `F051` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Llavero: la pregunta que no quería hacer
538. `MILO-R0508` | family `F051` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Llavero: el recuerdo que tenían distinto
539. `MILO-R0509` | family `F051` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Llavero: el agradecimiento dicho demasiado tarde
540. `MILO-R0510` | family `F051` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Llavero: el cuidado que necesitó permiso
541. `MILO-R0512` | family `F052` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Cama preparada: la copia que no funcionó
542. `MILO-R0513` | family `F052` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Cama preparada: el favor convertido en deuda
543. `MILO-R0514` | family `F052` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Cama preparada: dos personas, dos necesidades
544. `MILO-R0515` | family `F052` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Cama preparada: el acuerdo que nadie había entendido
545. `MILO-R0516` | family `F052` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Cama preparada: la ayuda que cambió algo querido
546. `MILO-R0517` | family `F052` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Cama preparada: la pregunta que no quería hacer
547. `MILO-R0518` | family `F052` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Cama preparada: el recuerdo que tenían distinto
548. `MILO-R0519` | family `F052` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Cama preparada: el agradecimiento dicho demasiado tarde
549. `MILO-R0520` | family `F052` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Cama preparada: el cuidado que necesitó permiso
550. `MILO-R0522` | family `F053` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Taza guardada: la copia que no funcionó
551. `MILO-R0523` | family `F053` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Taza guardada: el favor convertido en deuda
552. `MILO-R0524` | family `F053` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Taza guardada: dos personas, dos necesidades
553. `MILO-R0525` | family `F053` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Taza guardada: el acuerdo que nadie había entendido
554. `MILO-R0526` | family `F053` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Taza guardada: la ayuda que cambió algo querido
555. `MILO-R0527` | family `F053` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Taza guardada: la pregunta que no quería hacer
556. `MILO-R0528` | family `F053` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Taza guardada: el recuerdo que tenían distinto
557. `MILO-R0529` | family `F053` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Taza guardada: el agradecimiento dicho demasiado tarde
558. `MILO-R0530` | family `F053` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Taza guardada: el cuidado que necesitó permiso
559. `MILO-R0531` | family `F054` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Marca en pared: el gesto que llegó a la persona equivocada
560. `MILO-R0532` | family `F054` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Marca en pared: la copia que no funcionó
561. `MILO-R0533` | family `F054` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Marca en pared: el favor convertido en deuda
562. `MILO-R0534` | family `F054` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Marca en pared: dos personas, dos necesidades
563. `MILO-R0535` | family `F054` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Marca en pared: el acuerdo que nadie había entendido
564. `MILO-R0536` | family `F054` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Marca en pared: la ayuda que cambió algo querido
565. `MILO-R0537` | family `F054` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Marca en pared: la pregunta que no quería hacer
566. `MILO-R0538` | family `F054` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Marca en pared: el recuerdo que tenían distinto
567. `MILO-R0539` | family `F054` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Marca en pared: el agradecimiento dicho demasiado tarde
568. `MILO-R0540` | family `F054` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Marca en pared: el cuidado que necesitó permiso
569. `MILO-R0542` | family `F055` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Perchero: la copia que no funcionó
570. `MILO-R0543` | family `F055` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Perchero: el favor convertido en deuda
571. `MILO-R0544` | family `F055` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Perchero: dos personas, dos necesidades
572. `MILO-R0545` | family `F055` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Perchero: el acuerdo que nadie había entendido
573. `MILO-R0546` | family `F055` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Perchero: la ayuda que cambió algo querido
574. `MILO-R0547` | family `F055` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Perchero: la pregunta que no quería hacer
575. `MILO-R0548` | family `F055` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Perchero: el recuerdo que tenían distinto
576. `MILO-R0549` | family `F055` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Perchero: el agradecimiento dicho demasiado tarde
577. `MILO-R0550` | family `F055` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Regreso y pertenencia | Perchero: el cuidado que necesitó permiso
578. `MILO-R0552` | family `F056` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Silla vacía: la copia que no funcionó
579. `MILO-R0553` | family `F056` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Silla vacía: el favor convertido en deuda
580. `MILO-R0554` | family `F056` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Silla vacía: dos personas, dos necesidades
581. `MILO-R0555` | family `F056` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Silla vacía: el acuerdo que nadie había entendido
582. `MILO-R0556` | family `F056` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Silla vacía: la ayuda que cambió algo querido
583. `MILO-R0557` | family `F056` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Silla vacía: la pregunta que no quería hacer
584. `MILO-R0558` | family `F056` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Silla vacía: el recuerdo que tenían distinto
585. `MILO-R0559` | family `F056` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Silla vacía: el agradecimiento dicho demasiado tarde
586. `MILO-R0560` | family `F056` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Silla vacía: el cuidado que necesitó permiso
587. `MILO-R0562` | family `F057` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Taza sin usar: la copia que no funcionó
588. `MILO-R0563` | family `F057` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Taza sin usar: el favor convertido en deuda
589. `MILO-R0564` | family `F057` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Taza sin usar: dos personas, dos necesidades
590. `MILO-R0565` | family `F057` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Taza sin usar: el acuerdo que nadie había entendido
591. `MILO-R0566` | family `F057` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Taza sin usar: la ayuda que cambió algo querido
592. `MILO-R0567` | family `F057` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Taza sin usar: la pregunta que no quería hacer
593. `MILO-R0568` | family `F057` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Taza sin usar: el recuerdo que tenían distinto
594. `MILO-R0569` | family `F057` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Taza sin usar: el agradecimiento dicho demasiado tarde
595. `MILO-R0570` | family `F057` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Taza sin usar: el cuidado que necesitó permiso
596. `MILO-R0572` | family `F058` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Prenda guardada: la copia que no funcionó
597. `MILO-R0573` | family `F058` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Prenda guardada: el favor convertido en deuda
598. `MILO-R0574` | family `F058` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Prenda guardada: dos personas, dos necesidades
599. `MILO-R0575` | family `F058` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Prenda guardada: el acuerdo que nadie había entendido
600. `MILO-R0576` | family `F058` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Prenda guardada: la ayuda que cambió algo querido
601. `MILO-R0577` | family `F058` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Prenda guardada: la pregunta que no quería hacer
602. `MILO-R0578` | family `F058` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Prenda guardada: el recuerdo que tenían distinto
603. `MILO-R0579` | family `F058` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Prenda guardada: el agradecimiento dicho demasiado tarde
604. `MILO-R0580` | family `F058` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Prenda guardada: el cuidado que necesitó permiso
605. `MILO-R0582` | family `F059` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Receta heredada: la copia que no funcionó
606. `MILO-R0583` | family `F059` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Receta heredada: el favor convertido en deuda
607. `MILO-R0584` | family `F059` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Receta heredada: dos personas, dos necesidades
608. `MILO-R0585` | family `F059` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Receta heredada: el acuerdo que nadie había entendido
609. `MILO-R0586` | family `F059` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Receta heredada: la ayuda que cambió algo querido
610. `MILO-R0587` | family `F059` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Receta heredada: la pregunta que no quería hacer
611. `MILO-R0588` | family `F059` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Receta heredada: el recuerdo que tenían distinto
612. `MILO-R0589` | family `F059` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Receta heredada: el agradecimiento dicho demasiado tarde
613. `MILO-R0590` | family `F059` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Receta heredada: el cuidado que necesitó permiso
614. `MILO-R0592` | family `F060` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Fotografía en cajón: la copia que no funcionó
615. `MILO-R0593` | family `F060` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Fotografía en cajón: el favor convertido en deuda
616. `MILO-R0594` | family `F060` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Fotografía en cajón: dos personas, dos necesidades
617. `MILO-R0595` | family `F060` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Fotografía en cajón: el acuerdo que nadie había entendido
618. `MILO-R0596` | family `F060` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Fotografía en cajón: la ayuda que cambió algo querido
619. `MILO-R0597` | family `F060` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Fotografía en cajón: la pregunta que no quería hacer
620. `MILO-R0598` | family `F060` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Fotografía en cajón: el recuerdo que tenían distinto
621. `MILO-R0599` | family `F060` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Fotografía en cajón: el agradecimiento dicho demasiado tarde
622. `MILO-R0600` | family `F060` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Ausencia y despedida | Fotografía en cajón: el cuidado que necesitó permiso
623. `MILO-R0602` | family `F061` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Vaso de agua: la copia que no funcionó
624. `MILO-R0603` | family `F061` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Vaso de agua: el favor convertido en deuda
625. `MILO-R0604` | family `F061` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Vaso de agua: dos personas, dos necesidades
626. `MILO-R0605` | family `F061` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Vaso de agua: el acuerdo que nadie había entendido
627. `MILO-R0606` | family `F061` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Vaso de agua: la ayuda que cambió algo querido
628. `MILO-R0607` | family `F061` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Vaso de agua: la pregunta que no quería hacer
629. `MILO-R0608` | family `F061` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Vaso de agua: el recuerdo que tenían distinto
630. `MILO-R0609` | family `F061` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Vaso de agua: el agradecimiento dicho demasiado tarde
631. `MILO-R0610` | family `F061` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Vaso de agua: el cuidado que necesitó permiso
632. `MILO-R0612` | family `F062` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Sofá: la copia que no funcionó
633. `MILO-R0613` | family `F062` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Sofá: el favor convertido en deuda
634. `MILO-R0614` | family `F062` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Sofá: dos personas, dos necesidades
635. `MILO-R0615` | family `F062` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Sofá: el acuerdo que nadie había entendido
636. `MILO-R0616` | family `F062` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Sofá: la ayuda que cambió algo querido
637. `MILO-R0617` | family `F062` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Sofá: la pregunta que no quería hacer
638. `MILO-R0618` | family `F062` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Sofá: el recuerdo que tenían distinto
639. `MILO-R0619` | family `F062` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Sofá: el agradecimiento dicho demasiado tarde
640. `MILO-R0620` | family `F062` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Sofá: el cuidado que necesitó permiso
641. `MILO-R0622` | family `F063` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Llamada: la copia que no funcionó
642. `MILO-R0623` | family `F063` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Llamada: el favor convertido en deuda
643. `MILO-R0624` | family `F063` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Llamada: dos personas, dos necesidades
644. `MILO-R0625` | family `F063` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Llamada: el acuerdo que nadie había entendido
645. `MILO-R0626` | family `F063` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Llamada: la ayuda que cambió algo querido
646. `MILO-R0627` | family `F063` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Llamada: la pregunta que no quería hacer
647. `MILO-R0628` | family `F063` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Llamada: el recuerdo que tenían distinto
648. `MILO-R0629` | family `F063` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Llamada: el agradecimiento dicho demasiado tarde
649. `MILO-R0630` | family `F063` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Llamada: el cuidado que necesitó permiso
650. `MILO-R0632` | family `F064` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Juego de mesa: la copia que no funcionó
651. `MILO-R0633` | family `F064` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Juego de mesa: el favor convertido en deuda
652. `MILO-R0634` | family `F064` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Juego de mesa: dos personas, dos necesidades
653. `MILO-R0635` | family `F064` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Juego de mesa: el acuerdo que nadie había entendido
654. `MILO-R0636` | family `F064` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Juego de mesa: la ayuda que cambió algo querido
655. `MILO-R0637` | family `F064` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Juego de mesa: la pregunta que no quería hacer
656. `MILO-R0638` | family `F064` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Juego de mesa: el recuerdo que tenían distinto
657. `MILO-R0639` | family `F064` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Juego de mesa: el agradecimiento dicho demasiado tarde
658. `MILO-R0640` | family `F064` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Juego de mesa: el cuidado que necesitó permiso
659. `MILO-R0642` | family `F065` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Plato extra: la copia que no funcionó
660. `MILO-R0643` | family `F065` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Plato extra: el favor convertido en deuda
661. `MILO-R0644` | family `F065` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Plato extra: dos personas, dos necesidades
662. `MILO-R0645` | family `F065` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Plato extra: el acuerdo que nadie había entendido
663. `MILO-R0646` | family `F065` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Plato extra: la ayuda que cambió algo querido
664. `MILO-R0647` | family `F065` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Plato extra: la pregunta que no quería hacer
665. `MILO-R0648` | family `F065` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Plato extra: el recuerdo que tenían distinto
666. `MILO-R0649` | family `F065` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Plato extra: el agradecimiento dicho demasiado tarde
667. `MILO-R0650` | family `F065` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Amistad en casa | Plato extra: el cuidado que necesitó permiso
668. `MILO-R0651` | family `F066` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Manta: el gesto que llegó a la persona equivocada
669. `MILO-R0652` | family `F066` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Manta: la copia que no funcionó
670. `MILO-R0653` | family `F066` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Manta: el favor convertido en deuda
671. `MILO-R0654` | family `F066` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Manta: dos personas, dos necesidades
672. `MILO-R0655` | family `F066` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Manta: el acuerdo que nadie había entendido
673. `MILO-R0656` | family `F066` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Manta: la ayuda que cambió algo querido
674. `MILO-R0657` | family `F066` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Manta: la pregunta que no quería hacer
675. `MILO-R0658` | family `F066` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Manta: el recuerdo que tenían distinto
676. `MILO-R0659` | family `F066` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Manta: el agradecimiento dicho demasiado tarde
677. `MILO-R0660` | family `F066` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Manta: el cuidado que necesitó permiso
678. `MILO-R0662` | family `F067` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Bandeja: la copia que no funcionó
679. `MILO-R0663` | family `F067` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Bandeja: el favor convertido en deuda
680. `MILO-R0664` | family `F067` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Bandeja: dos personas, dos necesidades
681. `MILO-R0665` | family `F067` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Bandeja: el acuerdo que nadie había entendido
682. `MILO-R0666` | family `F067` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Bandeja: la ayuda que cambió algo querido
683. `MILO-R0667` | family `F067` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Bandeja: la pregunta que no quería hacer
684. `MILO-R0668` | family `F067` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Bandeja: el recuerdo que tenían distinto
685. `MILO-R0669` | family `F067` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Bandeja: el agradecimiento dicho demasiado tarde
686. `MILO-R0670` | family `F067` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Bandeja: el cuidado que necesitó permiso
687. `MILO-R0672` | family `F068` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Escoba: la copia que no funcionó
688. `MILO-R0673` | family `F068` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Escoba: el favor convertido en deuda
689. `MILO-R0674` | family `F068` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Escoba: dos personas, dos necesidades
690. `MILO-R0675` | family `F068` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Escoba: el acuerdo que nadie había entendido
691. `MILO-R0676` | family `F068` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Escoba: la ayuda que cambió algo querido
692. `MILO-R0677` | family `F068` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Escoba: la pregunta que no quería hacer
693. `MILO-R0678` | family `F068` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Escoba: el recuerdo que tenían distinto
694. `MILO-R0679` | family `F068` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Escoba: el agradecimiento dicho demasiado tarde
695. `MILO-R0680` | family `F068` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Escoba: el cuidado que necesitó permiso
696. `MILO-R0681` | family `F069` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Jarra: el gesto que llegó a la persona equivocada
697. `MILO-R0682` | family `F069` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Jarra: la copia que no funcionó
698. `MILO-R0683` | family `F069` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Jarra: el favor convertido en deuda
699. `MILO-R0684` | family `F069` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Jarra: dos personas, dos necesidades
700. `MILO-R0685` | family `F069` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Jarra: el acuerdo que nadie había entendido
701. `MILO-R0686` | family `F069` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Jarra: la ayuda que cambió algo querido
702. `MILO-R0687` | family `F069` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Jarra: la pregunta que no quería hacer
703. `MILO-R0688` | family `F069` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Jarra: el recuerdo que tenían distinto
704. `MILO-R0689` | family `F069` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Jarra: el agradecimiento dicho demasiado tarde
705. `MILO-R0690` | family `F069` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Jarra: el cuidado que necesitó permiso
706. `MILO-R0692` | family `F070` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Almohada: la copia que no funcionó
707. `MILO-R0693` | family `F070` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Almohada: el favor convertido en deuda
708. `MILO-R0694` | family `F070` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Almohada: dos personas, dos necesidades
709. `MILO-R0695` | family `F070` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Almohada: el acuerdo que nadie había entendido
710. `MILO-R0696` | family `F070` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Almohada: la ayuda que cambió algo querido
711. `MILO-R0697` | family `F070` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Almohada: la pregunta que no quería hacer
712. `MILO-R0698` | family `F070` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Almohada: el recuerdo que tenían distinto
713. `MILO-R0699` | family `F070` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Almohada: el agradecimiento dicho demasiado tarde
714. `MILO-R0700` | family `F070` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Cuidado recíproco | Almohada: el cuidado que necesitó permiso
715. `MILO-R0701` | family `F071` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Sillón: el gesto que llegó a la persona equivocada
716. `MILO-R0702` | family `F071` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Sillón: la copia que no funcionó
717. `MILO-R0703` | family `F071` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Sillón: el favor convertido en deuda
718. `MILO-R0704` | family `F071` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Sillón: dos personas, dos necesidades
719. `MILO-R0705` | family `F071` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Sillón: el acuerdo que nadie había entendido
720. `MILO-R0706` | family `F071` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Sillón: la ayuda que cambió algo querido
721. `MILO-R0707` | family `F071` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Sillón: la pregunta que no quería hacer
722. `MILO-R0708` | family `F071` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Sillón: el recuerdo que tenían distinto
723. `MILO-R0709` | family `F071` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Sillón: el agradecimiento dicho demasiado tarde
724. `MILO-R0710` | family `F071` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Sillón: el cuidado que necesitó permiso
725. `MILO-R0712` | family `F072` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lista: la copia que no funcionó
726. `MILO-R0713` | family `F072` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lista: el favor convertido en deuda
727. `MILO-R0714` | family `F072` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lista: dos personas, dos necesidades
728. `MILO-R0715` | family `F072` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lista: el acuerdo que nadie había entendido
729. `MILO-R0716` | family `F072` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lista: la ayuda que cambió algo querido
730. `MILO-R0717` | family `F072` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lista: la pregunta que no quería hacer
731. `MILO-R0718` | family `F072` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lista: el recuerdo que tenían distinto
732. `MILO-R0719` | family `F072` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lista: el agradecimiento dicho demasiado tarde
733. `MILO-R0720` | family `F072` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lista: el cuidado que necesitó permiso
734. `MILO-R0722` | family `F073` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lámpara: la copia que no funcionó
735. `MILO-R0723` | family `F073` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lámpara: el favor convertido en deuda
736. `MILO-R0724` | family `F073` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lámpara: dos personas, dos necesidades
737. `MILO-R0725` | family `F073` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lámpara: el acuerdo que nadie había entendido
738. `MILO-R0726` | family `F073` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lámpara: la ayuda que cambió algo querido
739. `MILO-R0727` | family `F073` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lámpara: la pregunta que no quería hacer
740. `MILO-R0728` | family `F073` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lámpara: el recuerdo que tenían distinto
741. `MILO-R0729` | family `F073` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lámpara: el agradecimiento dicho demasiado tarde
742. `MILO-R0730` | family `F073` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Lámpara: el cuidado que necesitó permiso
743. `MILO-R0731` | family `F074` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Taza de café: el gesto que llegó a la persona equivocada
744. `MILO-R0732` | family `F074` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Taza de café: la copia que no funcionó
745. `MILO-R0733` | family `F074` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Taza de café: el favor convertido en deuda
746. `MILO-R0734` | family `F074` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Taza de café: dos personas, dos necesidades
747. `MILO-R0735` | family `F074` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Taza de café: el acuerdo que nadie había entendido
748. `MILO-R0736` | family `F074` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Taza de café: la ayuda que cambió algo querido
749. `MILO-R0737` | family `F074` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Taza de café: la pregunta que no quería hacer
750. `MILO-R0738` | family `F074` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Taza de café: el recuerdo que tenían distinto
751. `MILO-R0739` | family `F074` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Taza de café: el agradecimiento dicho demasiado tarde
752. `MILO-R0740` | family `F074` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Taza de café: el cuidado que necesitó permiso
753. `MILO-R0741` | family `F075` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Ventana abierta: el gesto que llegó a la persona equivocada
754. `MILO-R0742` | family `F075` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Ventana abierta: la copia que no funcionó
755. `MILO-R0743` | family `F075` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Ventana abierta: el favor convertido en deuda
756. `MILO-R0744` | family `F075` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Ventana abierta: dos personas, dos necesidades
757. `MILO-R0745` | family `F075` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Ventana abierta: el acuerdo que nadie había entendido
758. `MILO-R0746` | family `F075` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Ventana abierta: la ayuda que cambió algo querido
759. `MILO-R0747` | family `F075` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Ventana abierta: la pregunta que no quería hacer
760. `MILO-R0748` | family `F075` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Ventana abierta: el recuerdo que tenían distinto
761. `MILO-R0749` | family `F075` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Ventana abierta: el agradecimiento dicho demasiado tarde
762. `MILO-R0750` | family `F075` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Descanso y valor | Ventana abierta: el cuidado que necesitó permiso
763. `MILO-R0752` | family `F076` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Herramienta prestada: la copia que no funcionó
764. `MILO-R0753` | family `F076` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Herramienta prestada: el favor convertido en deuda
765. `MILO-R0754` | family `F076` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Herramienta prestada: dos personas, dos necesidades
766. `MILO-R0755` | family `F076` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Herramienta prestada: el acuerdo que nadie había entendido
767. `MILO-R0756` | family `F076` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Herramienta prestada: la ayuda que cambió algo querido
768. `MILO-R0757` | family `F076` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Herramienta prestada: la pregunta que no quería hacer
769. `MILO-R0758` | family `F076` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Herramienta prestada: el recuerdo que tenían distinto
770. `MILO-R0759` | family `F076` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Herramienta prestada: el agradecimiento dicho demasiado tarde
771. `MILO-R0760` | family `F076` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Herramienta prestada: el cuidado que necesitó permiso
772. `MILO-R0762` | family `F077` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Plato lavado: la copia que no funcionó
773. `MILO-R0763` | family `F077` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Plato lavado: el favor convertido en deuda
774. `MILO-R0764` | family `F077` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Plato lavado: dos personas, dos necesidades
775. `MILO-R0765` | family `F077` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Plato lavado: el acuerdo que nadie había entendido
776. `MILO-R0766` | family `F077` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Plato lavado: la ayuda que cambió algo querido
777. `MILO-R0767` | family `F077` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Plato lavado: la pregunta que no quería hacer
778. `MILO-R0768` | family `F077` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Plato lavado: el recuerdo que tenían distinto
779. `MILO-R0769` | family `F077` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Plato lavado: el agradecimiento dicho demasiado tarde
780. `MILO-R0770` | family `F077` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Plato lavado: el cuidado que necesitó permiso
781. `MILO-R0771` | family `F078` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Nota: el gesto que llegó a la persona equivocada
782. `MILO-R0772` | family `F078` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Nota: la copia que no funcionó
783. `MILO-R0773` | family `F078` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Nota: el favor convertido en deuda
784. `MILO-R0774` | family `F078` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Nota: dos personas, dos necesidades
785. `MILO-R0775` | family `F078` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Nota: el acuerdo que nadie había entendido
786. `MILO-R0776` | family `F078` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Nota: la ayuda que cambió algo querido
787. `MILO-R0777` | family `F078` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Nota: la pregunta que no quería hacer
788. `MILO-R0778` | family `F078` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Nota: el recuerdo que tenían distinto
789. `MILO-R0779` | family `F078` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Nota: el agradecimiento dicho demasiado tarde
790. `MILO-R0780` | family `F078` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Nota: el cuidado que necesitó permiso
791. `MILO-R0781` | family `F079` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Planta regalada: el gesto que llegó a la persona equivocada
792. `MILO-R0782` | family `F079` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Planta regalada: la copia que no funcionó
793. `MILO-R0783` | family `F079` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Planta regalada: el favor convertido en deuda
794. `MILO-R0784` | family `F079` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Planta regalada: dos personas, dos necesidades
795. `MILO-R0785` | family `F079` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Planta regalada: el acuerdo que nadie había entendido
796. `MILO-R0786` | family `F079` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Planta regalada: la ayuda que cambió algo querido
797. `MILO-R0787` | family `F079` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Planta regalada: la pregunta que no quería hacer
798. `MILO-R0788` | family `F079` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Planta regalada: el recuerdo que tenían distinto
799. `MILO-R0789` | family `F079` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Planta regalada: el agradecimiento dicho demasiado tarde
800. `MILO-R0790` | family `F079` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Planta regalada: el cuidado que necesitó permiso
801. `MILO-R0791` | family `F080` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Asiento reservado: el gesto que llegó a la persona equivocada
802. `MILO-R0792` | family `F080` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Asiento reservado: la copia que no funcionó
803. `MILO-R0793` | family `F080` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Asiento reservado: el favor convertido en deuda
804. `MILO-R0794` | family `F080` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Asiento reservado: dos personas, dos necesidades
805. `MILO-R0795` | family `F080` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Asiento reservado: el acuerdo que nadie había entendido
806. `MILO-R0796` | family `F080` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Asiento reservado: la ayuda que cambió algo querido
807. `MILO-R0797` | family `F080` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Asiento reservado: la pregunta que no quería hacer
808. `MILO-R0798` | family `F080` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Asiento reservado: el recuerdo que tenían distinto
809. `MILO-R0799` | family `F080` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Asiento reservado: el agradecimiento dicho demasiado tarde
810. `MILO-R0800` | family `F080` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Gratitud concreta | Asiento reservado: el cuidado que necesitó permiso
811. `MILO-R0801` | family `F081` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Pan compartido: el gesto que llegó a la persona equivocada
812. `MILO-R0802` | family `F081` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Pan compartido: la copia que no funcionó
813. `MILO-R0803` | family `F081` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Pan compartido: el favor convertido en deuda
814. `MILO-R0804` | family `F081` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Pan compartido: dos personas, dos necesidades
815. `MILO-R0805` | family `F081` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Pan compartido: el acuerdo que nadie había entendido
816. `MILO-R0806` | family `F081` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Pan compartido: la ayuda que cambió algo querido
817. `MILO-R0807` | family `F081` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Pan compartido: la pregunta que no quería hacer
818. `MILO-R0808` | family `F081` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Pan compartido: el recuerdo que tenían distinto
819. `MILO-R0809` | family `F081` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Pan compartido: el agradecimiento dicho demasiado tarde
820. `MILO-R0810` | family `F081` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Pan compartido: el cuidado que necesitó permiso
821. `MILO-R0811` | family `F082` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Dominó: el gesto que llegó a la persona equivocada
822. `MILO-R0812` | family `F082` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Dominó: la copia que no funcionó
823. `MILO-R0813` | family `F082` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Dominó: el favor convertido en deuda
824. `MILO-R0814` | family `F082` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Dominó: dos personas, dos necesidades
825. `MILO-R0815` | family `F082` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Dominó: el acuerdo que nadie había entendido
826. `MILO-R0816` | family `F082` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Dominó: la ayuda que cambió algo querido
827. `MILO-R0817` | family `F082` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Dominó: la pregunta que no quería hacer
828. `MILO-R0818` | family `F082` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Dominó: el recuerdo que tenían distinto
829. `MILO-R0819` | family `F082` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Dominó: el agradecimiento dicho demasiado tarde
830. `MILO-R0820` | family `F082` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Dominó: el cuidado que necesitó permiso
831. `MILO-R0822` | family `F083` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Café de domingo: la copia que no funcionó
832. `MILO-R0823` | family `F083` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Café de domingo: el favor convertido en deuda
833. `MILO-R0824` | family `F083` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Café de domingo: dos personas, dos necesidades
834. `MILO-R0825` | family `F083` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Café de domingo: el acuerdo que nadie había entendido
835. `MILO-R0826` | family `F083` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Café de domingo: la ayuda que cambió algo querido
836. `MILO-R0827` | family `F083` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Café de domingo: la pregunta que no quería hacer
837. `MILO-R0828` | family `F083` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Café de domingo: el recuerdo que tenían distinto
838. `MILO-R0829` | family `F083` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Café de domingo: el agradecimiento dicho demasiado tarde
839. `MILO-R0830` | family `F083` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Café de domingo: el cuidado que necesitó permiso
840. `MILO-R0831` | family `F084` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Mantel diario: el gesto que llegó a la persona equivocada
841. `MILO-R0832` | family `F084` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Mantel diario: la copia que no funcionó
842. `MILO-R0833` | family `F084` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Mantel diario: el favor convertido en deuda
843. `MILO-R0834` | family `F084` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Mantel diario: dos personas, dos necesidades
844. `MILO-R0835` | family `F084` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Mantel diario: el acuerdo que nadie había entendido
845. `MILO-R0836` | family `F084` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Mantel diario: la ayuda que cambió algo querido
846. `MILO-R0837` | family `F084` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Mantel diario: la pregunta que no quería hacer
847. `MILO-R0838` | family `F084` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Mantel diario: el recuerdo que tenían distinto
848. `MILO-R0839` | family `F084` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Mantel diario: el agradecimiento dicho demasiado tarde
849. `MILO-R0840` | family `F084` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Mantel diario: el cuidado que necesitó permiso
850. `MILO-R0842` | family `F085` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Luz de cocina: la copia que no funcionó
851. `MILO-R0843` | family `F085` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Luz de cocina: el favor convertido en deuda
852. `MILO-R0844` | family `F085` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Luz de cocina: dos personas, dos necesidades
853. `MILO-R0845` | family `F085` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Luz de cocina: el acuerdo que nadie había entendido
854. `MILO-R0846` | family `F085` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Luz de cocina: la ayuda que cambió algo querido
855. `MILO-R0847` | family `F085` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Luz de cocina: la pregunta que no quería hacer
856. `MILO-R0848` | family `F085` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Luz de cocina: el recuerdo que tenían distinto
857. `MILO-R0849` | family `F085` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Luz de cocina: el agradecimiento dicho demasiado tarde
858. `MILO-R0850` | family `F085` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Rituales familiares | Luz de cocina: el cuidado que necesitó permiso
859. `MILO-R0852` | family `F086` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Control extraviado: la copia que no funcionó
860. `MILO-R0853` | family `F086` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Control extraviado: el favor convertido en deuda
861. `MILO-R0854` | family `F086` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Control extraviado: dos personas, dos necesidades
862. `MILO-R0855` | family `F086` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Control extraviado: el acuerdo que nadie había entendido
863. `MILO-R0856` | family `F086` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Control extraviado: la ayuda que cambió algo querido
864. `MILO-R0857` | family `F086` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Control extraviado: la pregunta que no quería hacer
865. `MILO-R0858` | family `F086` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Control extraviado: el recuerdo que tenían distinto
866. `MILO-R0859` | family `F086` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Control extraviado: el agradecimiento dicho demasiado tarde
867. `MILO-R0860` | family `F086` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Control extraviado: el cuidado que necesitó permiso
868. `MILO-R0861` | family `F087` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Frasco de galletas: el gesto que llegó a la persona equivocada
869. `MILO-R0862` | family `F087` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Frasco de galletas: la copia que no funcionó
870. `MILO-R0863` | family `F087` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Frasco de galletas: el favor convertido en deuda
871. `MILO-R0864` | family `F087` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Frasco de galletas: dos personas, dos necesidades
872. `MILO-R0865` | family `F087` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Frasco de galletas: el acuerdo que nadie había entendido
873. `MILO-R0866` | family `F087` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Frasco de galletas: la ayuda que cambió algo querido
874. `MILO-R0867` | family `F087` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Frasco de galletas: la pregunta que no quería hacer
875. `MILO-R0868` | family `F087` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Frasco de galletas: el recuerdo que tenían distinto
876. `MILO-R0869` | family `F087` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Frasco de galletas: el agradecimiento dicho demasiado tarde
877. `MILO-R0870` | family `F087` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Frasco de galletas: el cuidado que necesitó permiso
878. `MILO-R0871` | family `F088` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Silla que cruje: el gesto que llegó a la persona equivocada
879. `MILO-R0872` | family `F088` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Silla que cruje: la copia que no funcionó
880. `MILO-R0873` | family `F088` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Silla que cruje: el favor convertido en deuda
881. `MILO-R0874` | family `F088` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Silla que cruje: dos personas, dos necesidades
882. `MILO-R0875` | family `F088` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Silla que cruje: el acuerdo que nadie había entendido
883. `MILO-R0876` | family `F088` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Silla que cruje: la ayuda que cambió algo querido
884. `MILO-R0877` | family `F088` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Silla que cruje: la pregunta que no quería hacer
885. `MILO-R0878` | family `F088` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Silla que cruje: el recuerdo que tenían distinto
886. `MILO-R0879` | family `F088` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Silla que cruje: el agradecimiento dicho demasiado tarde
887. `MILO-R0880` | family `F088` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Silla que cruje: el cuidado que necesitó permiso
888. `MILO-R0881` | family `F089` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Toalla confundida: el gesto que llegó a la persona equivocada
889. `MILO-R0882` | family `F089` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Toalla confundida: la copia que no funcionó
890. `MILO-R0883` | family `F089` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Toalla confundida: el favor convertido en deuda
891. `MILO-R0884` | family `F089` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Toalla confundida: dos personas, dos necesidades
892. `MILO-R0885` | family `F089` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Toalla confundida: el acuerdo que nadie había entendido
893. `MILO-R0886` | family `F089` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Toalla confundida: la ayuda que cambió algo querido
894. `MILO-R0887` | family `F089` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Toalla confundida: la pregunta que no quería hacer
895. `MILO-R0888` | family `F089` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Toalla confundida: el recuerdo que tenían distinto
896. `MILO-R0889` | family `F089` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Toalla confundida: el agradecimiento dicho demasiado tarde
897. `MILO-R0890` | family `F089` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Toalla confundida: el cuidado que necesitó permiso
898. `MILO-R0891` | family `F090` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Rompecabezas incompleto: el gesto que llegó a la persona equivocada
899. `MILO-R0892` | family `F090` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Rompecabezas incompleto: la copia que no funcionó
900. `MILO-R0893` | family `F090` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Rompecabezas incompleto: el favor convertido en deuda
901. `MILO-R0894` | family `F090` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Rompecabezas incompleto: dos personas, dos necesidades
902. `MILO-R0895` | family `F090` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Rompecabezas incompleto: el acuerdo que nadie había entendido
903. `MILO-R0896` | family `F090` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Rompecabezas incompleto: la ayuda que cambió algo querido
904. `MILO-R0897` | family `F090` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Rompecabezas incompleto: la pregunta que no quería hacer
905. `MILO-R0898` | family `F090` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Rompecabezas incompleto: el recuerdo que tenían distinto
906. `MILO-R0899` | family `F090` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Rompecabezas incompleto: el agradecimiento dicho demasiado tarde
907. `MILO-R0900` | family `F090` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Humor doméstico | Rompecabezas incompleto: el cuidado que necesitó permiso
908. `MILO-R0901` | family `F091` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Marcas de altura: el gesto que llegó a la persona equivocada
909. `MILO-R0902` | family `F091` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Marcas de altura: la copia que no funcionó
910. `MILO-R0903` | family `F091` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Marcas de altura: el favor convertido en deuda
911. `MILO-R0904` | family `F091` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Marcas de altura: dos personas, dos necesidades
912. `MILO-R0905` | family `F091` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Marcas de altura: el acuerdo que nadie había entendido
913. `MILO-R0906` | family `F091` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Marcas de altura: la ayuda que cambió algo querido
914. `MILO-R0907` | family `F091` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Marcas de altura: la pregunta que no quería hacer
915. `MILO-R0908` | family `F091` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Marcas de altura: el recuerdo que tenían distinto
916. `MILO-R0909` | family `F091` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Marcas de altura: el agradecimiento dicho demasiado tarde
917. `MILO-R0910` | family `F091` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Marcas de altura: el cuidado que necesitó permiso
918. `MILO-R0911` | family `F092` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Manos: el gesto que llegó a la persona equivocada
919. `MILO-R0912` | family `F092` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Manos: la copia que no funcionó
920. `MILO-R0913` | family `F092` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Manos: el favor convertido en deuda
921. `MILO-R0914` | family `F092` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Manos: dos personas, dos necesidades
922. `MILO-R0915` | family `F092` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Manos: el acuerdo que nadie había entendido
923. `MILO-R0916` | family `F092` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Manos: la ayuda que cambió algo querido
924. `MILO-R0917` | family `F092` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Manos: la pregunta que no quería hacer
925. `MILO-R0918` | family `F092` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Manos: el recuerdo que tenían distinto
926. `MILO-R0919` | family `F092` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Manos: el agradecimiento dicho demasiado tarde
927. `MILO-R0920` | family `F092` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Manos: el cuidado que necesitó permiso
928. `MILO-R0922` | family `F093` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mochila: la copia que no funcionó
929. `MILO-R0923` | family `F093` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mochila: el favor convertido en deuda
930. `MILO-R0924` | family `F093` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mochila: dos personas, dos necesidades
931. `MILO-R0925` | family `F093` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mochila: el acuerdo que nadie había entendido
932. `MILO-R0926` | family `F093` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mochila: la ayuda que cambió algo querido
933. `MILO-R0927` | family `F093` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mochila: la pregunta que no quería hacer
934. `MILO-R0928` | family `F093` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mochila: el recuerdo que tenían distinto
935. `MILO-R0929` | family `F093` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mochila: el agradecimiento dicho demasiado tarde
936. `MILO-R0930` | family `F093` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mochila: el cuidado que necesitó permiso
937. `MILO-R0932` | family `F094` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Reloj detenido: la copia que no funcionó
938. `MILO-R0933` | family `F094` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Reloj detenido: el favor convertido en deuda
939. `MILO-R0934` | family `F094` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Reloj detenido: dos personas, dos necesidades
940. `MILO-R0935` | family `F094` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Reloj detenido: el acuerdo que nadie había entendido
941. `MILO-R0936` | family `F094` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Reloj detenido: la ayuda que cambió algo querido
942. `MILO-R0937` | family `F094` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Reloj detenido: la pregunta que no quería hacer
943. `MILO-R0938` | family `F094` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Reloj detenido: el recuerdo que tenían distinto
944. `MILO-R0939` | family `F094` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Reloj detenido: el agradecimiento dicho demasiado tarde
945. `MILO-R0940` | family `F094` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Reloj detenido: el cuidado que necesitó permiso
946. `MILO-R0941` | family `F095` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mesa familiar: el gesto que llegó a la persona equivocada
947. `MILO-R0942` | family `F095` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mesa familiar: la copia que no funcionó
948. `MILO-R0943` | family `F095` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mesa familiar: el favor convertido en deuda
949. `MILO-R0944` | family `F095` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mesa familiar: dos personas, dos necesidades
950. `MILO-R0945` | family `F095` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mesa familiar: el acuerdo que nadie había entendido
951. `MILO-R0946` | family `F095` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mesa familiar: la ayuda que cambió algo querido
952. `MILO-R0947` | family `F095` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mesa familiar: la pregunta que no quería hacer
953. `MILO-R0948` | family `F095` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mesa familiar: el recuerdo que tenían distinto
954. `MILO-R0949` | family `F095` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mesa familiar: el agradecimiento dicho demasiado tarde
955. `MILO-R0950` | family `F095` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Tiempo y crecimiento | Mesa familiar: el cuidado que necesitó permiso
956. `MILO-R0952` | family `F096` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Dos sillas: la copia que no funcionó
957. `MILO-R0953` | family `F096` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Dos sillas: el favor convertido en deuda
958. `MILO-R0954` | family `F096` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Dos sillas: dos personas, dos necesidades
959. `MILO-R0955` | family `F096` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Dos sillas: el acuerdo que nadie había entendido
960. `MILO-R0956` | family `F096` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Dos sillas: la ayuda que cambió algo querido
961. `MILO-R0957` | family `F096` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Dos sillas: la pregunta que no quería hacer
962. `MILO-R0958` | family `F096` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Dos sillas: el recuerdo que tenían distinto
963. `MILO-R0959` | family `F096` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Dos sillas: el agradecimiento dicho demasiado tarde
964. `MILO-R0960` | family `F096` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Dos sillas: el cuidado que necesitó permiso
965. `MILO-R0962` | family `F097` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Taza entre manos: la copia que no funcionó
966. `MILO-R0963` | family `F097` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Taza entre manos: el favor convertido en deuda
967. `MILO-R0964` | family `F097` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Taza entre manos: dos personas, dos necesidades
968. `MILO-R0965` | family `F097` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Taza entre manos: el acuerdo que nadie había entendido
969. `MILO-R0966` | family `F097` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Taza entre manos: la ayuda que cambió algo querido
970. `MILO-R0967` | family `F097` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Taza entre manos: la pregunta que no quería hacer
971. `MILO-R0968` | family `F097` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Taza entre manos: el recuerdo que tenían distinto
972. `MILO-R0969` | family `F097` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Taza entre manos: el agradecimiento dicho demasiado tarde
973. `MILO-R0970` | family `F097` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Taza entre manos: el cuidado que necesitó permiso
974. `MILO-R0972` | family `F098` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Puerta de entrada: la copia que no funcionó
975. `MILO-R0973` | family `F098` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Puerta de entrada: el favor convertido en deuda
976. `MILO-R0974` | family `F098` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Puerta de entrada: dos personas, dos necesidades
977. `MILO-R0975` | family `F098` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Puerta de entrada: el acuerdo que nadie había entendido
978. `MILO-R0976` | family `F098` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Puerta de entrada: la ayuda que cambió algo querido
979. `MILO-R0977` | family `F098` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Puerta de entrada: la pregunta que no quería hacer
980. `MILO-R0978` | family `F098` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Puerta de entrada: el recuerdo que tenían distinto
981. `MILO-R0979` | family `F098` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Puerta de entrada: el agradecimiento dicho demasiado tarde
982. `MILO-R0980` | family `F098` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Puerta de entrada: el cuidado que necesitó permiso
983. `MILO-R0982` | family `F099` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Teléfono apagado: la copia que no funcionó
984. `MILO-R0983` | family `F099` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Teléfono apagado: el favor convertido en deuda
985. `MILO-R0984` | family `F099` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Teléfono apagado: dos personas, dos necesidades
986. `MILO-R0985` | family `F099` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Teléfono apagado: el acuerdo que nadie había entendido
987. `MILO-R0986` | family `F099` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Teléfono apagado: la ayuda que cambió algo querido
988. `MILO-R0987` | family `F099` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Teléfono apagado: la pregunta que no quería hacer
989. `MILO-R0988` | family `F099` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Teléfono apagado: el recuerdo que tenían distinto
990. `MILO-R0989` | family `F099` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Teléfono apagado: el agradecimiento dicho demasiado tarde
991. `MILO-R0990` | family `F099` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Teléfono apagado: el cuidado que necesitó permiso
992. `MILO-R0992` | family `F100` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Mantel doblado: la copia que no funcionó
993. `MILO-R0993` | family `F100` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Mantel doblado: el favor convertido en deuda
994. `MILO-R0994` | family `F100` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Mantel doblado: dos personas, dos necesidades
995. `MILO-R0995` | family `F100` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Mantel doblado: el acuerdo que nadie había entendido
996. `MILO-R0996` | family `F100` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Mantel doblado: la ayuda que cambió algo querido
997. `MILO-R0997` | family `F100` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Mantel doblado: la pregunta que no quería hacer
998. `MILO-R0998` | family `F100` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Mantel doblado: el recuerdo que tenían distinto
999. `MILO-R0999` | family `F100` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Mantel doblado: el agradecimiento dicho demasiado tarde
1000. `MILO-R1000` | family `F100` | compuesto `88.00` | calidad `89.0` | afinidad `90.0` | Conversaciones difíciles | Mantel doblado: el cuidado que necesitó permiso

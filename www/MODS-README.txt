MOD DE COMBATE NINJA — Bola contra los Verdes

1) Entra en MODS y descarga "Mod combate ninja".
2) Pulsa "Importar mod" y selecciona combate-ninja.json.
3) Actívalo en la lista de mods.
4) Los verdes empezarán a perseguir a la bola. Desde la puntuación indicada aparecen enemigos morados que disparan apuntando a la posición del jugador.
5) Pulsa 🥷 ESQUIVAR cuando el proyectil esté cerca de la bola: dentro de la ventana de precisión, esquiva el disparo y suma un punto. El botón tiene enfriamiento; si lo pulsas demasiado pronto no gasta el intento.

Puedes editar los valores de config (luego vuelve a importarlo):
- unlockScore: puntuación a partir de la cual aparecen morados (0–500).
- purpleChance: probabilidad de que un enemigo nuevo sea morado (0–1).
- greenHoming: rapidez de persecución lateral de los verdes (0.001–0.2).
- purpleFireRate: intervalo aproximado entre tiros morados, en frames (20–600; menor = más frecuente).
- projectileSpeed: rapidez del proyectil (1–12).
- dodgeWindowPx: qué tan cerca debe estar para que cuente como esquiva perfecta (20–130).
- dodgeDuration: duración de la protección de la esquiva, en frames (5–60).
- dodgeCooldown: espera entre esquivas, en frames (10–300).

El tipo de comportamiento debe ser "combat-ninja". Los mods no ejecutan JavaScript externo: sus valores se validan y limitan por seguridad.

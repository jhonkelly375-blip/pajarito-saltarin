# Sala de partida Firebase
- Firebase Authentication anónimo debe estar habilitado.
- En Authentication > Settings > Authorized domains, agregar jhonkelly375-blip.github.io.
- Las reglas en database.rules.json solo admiten partidas bajo gameRooms y limitan la escritura del puntaje a cada uid. Revisar con Firebase Rules Simulator antes de publicar.
- No activar Test mode ni publicar reglas que permitan a cualquiera leer/escribir la base.
- El modo actual sincroniza sala, estado y puntuaciones; no retransmite posiciones/acciones frame a frame, por lo tanto es una carrera con puntajes sincronizados, no una misma partida cooperativa en tiempo real.

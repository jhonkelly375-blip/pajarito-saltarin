CREAR UN MOD PARA BOLA CONTRA LOS VERDES

Por seguridad, el importador acepta mods de tipo autopilot (no ejecuta JavaScript arbitrario). El mod debe ser un archivo de texto JSON con extension .json y este formato:

{
  "format": "bola-verdes-mod",
  "version": 1,
  "id": "mi-piloto",
  "name": "Mi piloto",
  "description": "Mi configuración del piloto automático",
  "type": "autopilot",
  "config": {
    "dangerDistance": 1
  }
}

Puedes cambiar id (usa letras minúsculas, números y guiones; empieza con letra o número), name, description y dangerDistance. dangerDistance tiene que ser un número de 0 a 100000. El valor 1 se importa correctamente; cambia el comportamiento: el piloto intenta apartarse al final, cuando el enemigo está muy cerca del fondo.

Pasos: crea el texto en una app de notas o editor; guárdalo como mi-piloto.json (asegúrate de que no termine en .txt); en el juego abre MODS > Importar mod y selecciona el archivo. Queda apagado hasta que tú lo actives. Si deseas que un mod haga algo distinto a autopilot, hace falta programar y añadir ese nuevo tipo de función al propio juego; el importador no ejecuta código externo por seguridad.

## Fork

Es importante, a la hora de hacer el fork, desmarcar la opción que dice \`Copy the main branch only\`.

**Atención:** Revisando el código de la interfaz, te das cuenta de que el último commit tiene código que no debe incluirse. Decides no mezclar ese commit en la versión final.

1. Creamos el issue y lo llamamos \`Deshacer último commit de la rama interface\` y me lo asigno a mí mismo. GitHub ya le asigna el \#1.
2. Creamos otro issue con el \#2 y lo cerramos con un commit en el que juntamos todas las ramas menos la llamada \`readme\`.
3. Hacemos el merge squash.
4. Antes de hacer el push, le ponemos una etiqueta que llamaremos \`v1.0\`.

Una vez terminado con esto en GitHub, crearemos la release que llamaremos version final 1.0 y listo.
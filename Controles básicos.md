# Controles básicos

En primer lugar, los principales controles de la vista de trabajo son:
- Orbit: `MMB` + ↕↔   Movimiento alrededor del foco de la vista.
- Pan: `⇧ Shift` + `MMB` + ↕↔  Movimiento en el plano de la vista.
- Dolly: `⇧ Shift` + `Ctrl` + `MMB` + ↕  Movimiento hacia la vista.

<img size="50%" src=https://github.com/AMDLC/UFV_JPA/assets/157854852/35236f32-df18-4479-9f39-36e05089834b> <blockquote>Control básico de la vista de trabajo con ratón y modificadores</blockquote><p>  
  
Los **objetos** en Blender interactúan cuando se le indica al programa a través de instrucciones, para ello normalmente es necesario realizar una selección de los mismos. <p>

Para ello tenemos la **herramienta de selección**, a la que accederemos con la tecla `W`. Al pulsarla repetidamente, cambia entre los distintos modos de selección. <p>

Con un objeto activo seleccionado, se pueden realizar transformaciones que alteran los valores de **posición, rotación o escala de su punto de origen**, que actúa sobre el objeto y la información que contiene.<p>
<img size="50%" src=https://github.com/AMDLC/UFV_JPA/assets/157854852/8622629c-531f-4fcd-8ebe-e7c05168f216> <blockquote>Selección y transformaciones</blockquote><p>

Los controles de transformación básica son los siguientes:
- **Grab**: `G` Traslación, afecta a la posición.
- **Rotate**: `R` Rotación, afecta a la orientación.
- **Scale**: `S` Escalar, afecta al tamaño.

Estos controles se pueden usar junto a los ejes principales:
`X` / `Y` / `Z` : respectivamente la trasformación tiene lugar en ese eje.

<img size="50%" src=https://github.com/AMDLC/UFV_JPA/assets/157854852/e471b6d9-fd98-4cd5-bdb9-f837e8dc064a> <blockquote>Uso de atajos de teclado</blockquote><p>

Del mismo modo, al pulsar `MMB` y mover el cursor, se puede determinar el eje en el cual realizar la acción, con un ciclo entre ellos.

Finalmente, puedes realizar la transformación en dos ejes al excluir el restante con la tecla ⇧ Shift y por lo tanto:<p>
- `⇧ Shift` + `X` : realizará la transformación en los ejes Y y Z, todos menos el X.
- `⇧ Shift` + `Y` : realizará la transformación en los ejes X y Z, todos menos el Y.
- `⇧ Shift` + `Z` : realizará la transformación en los ejes X e Y, todos menos el Z.
<p></p>

Para deshacer las transformaciones de traslación, rotación y escala, combinaremos la tecla  Alt con la transformación:
- `Alt` + `G` : deshacer transformaciones de traslación.
- `Alt` + `R` : deshacer transformaciones de rotación.
- `Alt` + `S` : deshacer transformaciones de escala.

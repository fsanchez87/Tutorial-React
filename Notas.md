# Notas

- Para 'recordar' cosas, los componentes usan **estado**.
  
- Todas las clases de componentes de React que tienen un constructor deben empezar con una llamada a `super(props)`.

- Cuando llamas `setState` en un componente, React actualiza automáticamente los componentes hijos dentro del mismo también.

- En React, sin embargo, es una convención usar los nombres on[Evento] para props que representan eventos y handle[Evento] para los métodos que manejan los eventos.

- En handleClick, llamamos .slice() para crear una copia del array de squares para modificarlo en vez de modificar el array existente.

    `var player = {score: 1, name: 'Jeff'};`
    
    `var newPlayer = {...player, score: 2};`
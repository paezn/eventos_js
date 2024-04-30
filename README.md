# Eventos en Javascript

## Modelo de gestión de eventos

- Un evento en programación web es una notificación de que ha ocurrido algo en la página, generalmente relacionado con la interacción con el usuario.
- Ejemplos:
    - Click en un botón o enlace
    - Se presiona una tecla específica
    - Se termina de cargar un archivo de audio o video
    - Se hace scroll sobre la página
-El evento más común es el evento **click**, que se produce cuando el usuario hace click con el ratón en un elemento de la página.

## Métodos para gestionar eventos

### Eventos mediante HTML

-Si se quiere que se muestre un mensaje emergente cuando el usuario haga click en un botón, podemos asociar el evento **click** al botón y definir la función que queremos que se ejecute cuando se produzca dicho evento.


```Javascript
```

- Cuando el usuario haga click sobre el botón, se disparará el evento **click** y se ejecutará la función **alert()** que mostrará un mensaje emergente con el texto ¡Hola, Guanentá!.

```Javascript
```

- Cuando trabajamos con eventos en JS, es común asociar una función al evento que queremos escuchar.  Se crea una función y se asocia al evento.

### Eventos mediante Javascript

```Javascript
```

```Javascript
```

- Una vez se identifica el elemento HTML, se asocia la función al evento del elemento

### Eventos mediante addEventListener()

**.addEventListener(evento, función, opciones)**

- Es la forma mas potente y versatil de manejar los eventos.
- Puede añadir varias funcionalidades, eliminar una funcionalidad previamente añadida con **removeEventListener()** e indicar ciertos comportamientos especiales.
- Es posible añadir una escucha **(listener)** para el evento específico indicado como primer parámetro.
- En caso de que dicho evento ocurra, se ejecutará la función asociada que se proporciona como segundo parámetro.
- También es posible un tercer parámetro opcional relacionado con el evento.

```Javascript
```

- Forma mas organizada

```Javascript
```
- Añadir múltiples listener

#### Opciones de ejecución

- **capture**: especifica si el evento se debe propagar desde el elemento raíz hacia el elemento actual o viceversa.
- **once**: especifica si el evento se debe escuchar sólo una vez
- **pasive**: mejorar el rendimiento de la página.

```Javascript
```


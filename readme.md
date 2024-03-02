# Wordle PPY

Wordle PPY es una versión simplificada del popular juego en línea "Wordle", donde los jugadores deben adivinar una palabra de cinco letras. Este proyecto es un juego basado en web desarrollado usando HTML, CSS y JavaScript.

## Cómo Jugar

1. Ingresa una palabra de cinco letras en el campo de entrada.
2. Haz clic en el botón "Intentar" para enviar tu intento.
3. El juego proporcionará retroalimentación sobre tu intento:
   - Verde: Letra correcta en la posición correcta.
   - Amarillo: Letra correcta en la posición incorrecta.
   - Gris: Letra incorrecta.
4. Tienes seis intentos para adivinar la palabra correcta.

## Características

- Selecciona una palabra al azar de un diccionario predefinido.
- Valida la entrada del usuario para asegurarse de que sea una palabra de cinco letras.
- Lleva un seguimiento y muestra el número de intentos restantes.
- Evita que el usuario adivine la misma palabra varias veces.
- Muestra la palabra correcta cuando el juego termina.

# Wordle PPY

Este es un juego de adivinanzas de palabras similar al juego Wordle. El objetivo es adivinar una palabra de 5 letras en un número limitado de intentos.

## Funcionalidades

- **init():** Inicializa el juego al cargar la página. Agrega un event listener al botón de "Guess" y al input para que al presionar Enter se ejecute la función guess().
- **getRandomWord():** Devuelve una palabra aleatoria de la lista predefinida.
- **guess():** Maneja la lógica principal del juego. Comprueba si la palabra ingresada por el jugador es correcta y actualiza la interfaz en consecuencia.
- **getGuess():** Obtiene la palabra ingresada por el jugador y la convierte a mayúsculas. Si la palabra no tiene 5 letras, muestra una alerta y devuelve una cadena vacía.
- **updateAttempts():** Actualiza el número de intentos restantes en la interfaz.
- **endGame(message):** Finaliza el juego y muestra un mensaje de éxito o fracaso en la interfaz. Deshabilita el input y el botón de "Guess".
- **showMessage(message):** Muestra un mensaje en la interfaz para informar al jugador sobre el estado del juego.

## Tecnologías utilizadas

- HTML
- CSS
- JavaScript

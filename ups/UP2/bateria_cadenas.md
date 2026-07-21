## :pencil: Batería de ejercicios con cadenas de caracteres

**:arrow_forward: Ejercicio 1**. A partir de una cadena de caracteres que se pide al usuario por teclado, aplicar:

&nbsp;&nbsp;&nbsp;a) Muestra el texto original introducido.

&nbsp;&nbsp;&nbsp;b) Muestra la longitud del texto introducido `length()`.

&nbsp;&nbsp;&nbsp;c) Elimina los espacios del texto (si los hay) y muestra como queda `replace()`.

&nbsp;&nbsp;&nbsp;d) Divide la cadena de texto en dos partes iguales (por la mitad) para posteriormente concatenarlas y mostrarlas de nuevo, pero con el siguiente formato: _"Primera mitad del texto es "_ `+` **_mitad1_** `+` _" y la segunda mitad del texto es "_ `+` **_mitad2_**. (`substring()` + `concat()`).

&nbsp;&nbsp;&nbsp;e) Transforma la cadena de texto a mayúsculas `toUpperCase()`.

&nbsp;&nbsp;&nbsp;**Ejemplo de ejecución :eyes::**

    INTRODUCE UNA PALABRA O FRASE: Prueba ejercicio caracteres
    
    Texto original: Prueba ejercicio caracteres
    La longitud del texto es: 27
    Texto sin espacios: Pruebaejerciciocaracteres
    Texto dividido en 2 mitades: "Primera mitad del texto es "Prueba ejerci" y la segunda mitad del texto es "cio caracteres".
    Texto a mayúsculas: PRUEBA EJERCICIO CARACTERES
 
**:arrow_forward: Ejercicio 2**. Desarrolla un programa que permita leer 2 cadenas de caracteres (palabras) diferentes y nos diga cual es la más larga. 

**:arrow_forward: Ejercicio 3**. Desarrolla un programa que quite a una variable numérica _N_ sus _m_ últimas cifras. Por ejemplo, si _N = 123456_ y _m = 2_, el nuevo valor de _N_ será _1234_.
 
**:arrow_forward: Ejercicio 4**. Escribe un programa que cuente cuántas veces aparece una subcadena dentro de una cadena, sin usar bucles. Usa como ejemplo las siguientes:

    String texto = "Hola Mundo, bienvenido a Mundo. Mundo es genial."; 
    String subcadena = "Mundo";
 
**:arrow_forward: Ejercicio 5**. Escribe un programa que simule un juego para 2 jugadores. El funcionamiento debe ser el siguiente:

1. El programa le pide al `Jugador 1` introducir una **_cadena_**.

2. El programa pide al `Jugador 2` que introduzca una **_palabra_**.

3. El programa debe verificar si la **_palabra_** insertada por el `Jugador 2` está contenida en la **_cadena_** que ha introducido el `Jugador 1`.
 
- Si no está, se debe **restar un intento** (intentos iniciales 10) y mostrar un mensaje de intento fallido. Seguidamente, el programa procederá a dar otra oportunidad al `Jugador 2` (hasta 10 intentos).
 
- Si está, el programa imprimirá un mensaje de **_¡enhorabuena, has acertado una palabra!_** y finalizará.
 
Usa la función `contains("palabra")`, la cual devuelve un _booleano_.
# Espiral de Ulam

**[Pruébala en el navegador →](https://jscalon.github.io/Ulam-Spiral/)**

Los números naturales escritos en espiral desde el centro, con los primos marcados. Al
hacerlo aparece algo que nadie espera: los primos tienden a alinearse en diagonales. Lo
descubrió el matemático Stanisław Ulam en 1963, garabateando durante una conferencia
aburrida, y sigue sin tener una explicación completa.

Puedes elegir cuántas vueltas da la espiral y de qué color se dibujan los primos; la figura
se redibuja al instante.

## Cómo funciona

- **La espiral** se recorre por tramos: en cada vuelta avanza a la derecha, sube, va a la
  izquierda y baja, y cada par de tramos es dos casillas más largo que el anterior
  (`2c + 1`, `2c + 1`, `2c + 2`, `2c + 2`).
- **La prueba de primalidad** divide solo hasta la raíz cuadrada del número: si `n` tuviera
  un divisor mayor que `√n`, tendría también uno menor, y ya se habría encontrado.
- **El dibujo** usa un `<canvas>`, y el tamaño de cada casilla se recalcula según las vueltas
  para que la espiral siempre quepa.

HTML, CSS y JavaScript, sin dependencias.

## Por qué lo hice

Es un proyecto personal, escrito a mano, para practicar el lenguaje, entender mejor la
matemática detrás de la espiral y ejercitar la algorítmica: convertir una idea matemática en
un algoritmo que la dibuje.

---

**English** — The Ulam spiral: the natural numbers written in a spiral from the centre, with
the primes highlighted, which reveals their tendency to line up along diagonals. You can set
the number of turns and the colour. A personal project, hand-written in plain HTML, CSS and
JavaScript to practise the language, the maths behind it and algorithm design.
[Try it in your browser](https://jscalon.github.io/Ulam-Spiral/).

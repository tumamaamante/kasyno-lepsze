# Casino Polaco - Tragamonedas y Blackjack

Este es un proyecto de simulación de casino que incluye dos juegos populares: Tragamonedas y Blackjack. Está desarrollado con HTML, CSS y JavaScript, con una interfaz completamente en polaco pero con documentación en español.

## Características

- **Tragamonedas**: Un juego de máquina tragamonedas con 3 rodillos y múltiples símbolos. 
  - Apuestas: 10, 25, 50, 100 PLN
  - Combinaciones ganadoras:
    - Tres símbolos iguales: x5 (x20 para 💎, x15 para 7️⃣, x10 para 🔔)
    - Dos símbolos iguales: x2

- **Blackjack**: El clásico juego de cartas contra el crupier.
  - Apuestas: 10, 25, 50, 100 PLN
  - Funciones: Repartir, Pedir carta, Plantarse

## Tecnologías utilizadas

- HTML5
- CSS3 (con TailwindCSS)
- JavaScript

## Instalación

No se requiere instalación. Solo abre el archivo `index.html` en tu navegador web.

## Estructura de archivos

```
polskie-kasyno/
│
├── index.html          # Página principal con la interfaz de usuario
├── style.css           # Estilos personalizados para el juego
└── casino.js           # Lógica del juego (tragamonedas y blackjack)
```

## Cómo jugar

1. **Tragamonedas**:
   - Selecciona el valor de la apuesta
   - Haz clic en "KRĘĆ!" (Girar) para jugar
   - Si obtienes símbolos iguales, ¡ganarás según la combinación!

2. **Blackjack**:
   - Selecciona el valor de la apuesta
   - Haz clic en "ROZDANIE" (Repartir) para iniciar el juego
   - Usa "DOBIERZ" (Pedir) para tomar otra carta
   - Usa "PAS" (Plantarse) para finalizar tu turno
   - El crupier jugará automáticamente después de que te plantes

## Nota importante

Este proyecto es solo para fines educativos y de entretenimiento. No implica apuestas reales.

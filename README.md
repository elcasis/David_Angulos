# 📐 ¡Super Ángulos! 🎯 — Juego Web Educativo

Aplicación web interactiva contenida en **un único archivo HTML (`index.html`)**, lista para publicar directamente en **GitHub Pages** y diseñada especialmente para jugar desde un **teléfono móvil**.

---

## ✨ ¿Qué puede hacer el programa?

### 1. Aprendizaje de los 6 tipos de ángulos
El programa dibuja ángulos de forma dinámica en un lienzo escolar (`<canvas>`) con colores vivos, vértice destacado, flechas y etiquetas de grados:
- **🐦 Ángulo Agudo (`< 90º`, ej. `40º`)**: Muestra ángulos cerrados como el de `40º` con arco azul.
- **📐 Ángulo Recto (`90º`)**: Muestra una esquina de `90º` con su clásico símbolo cuadrado verde.
- **🐘 Ángulo Obtuso (`> 90º`, ej. `120º`)**: Muestra ángulos abiertos como el de `120º` con arco naranja.
- **➖ Ángulo Llano (`180º`)**: Muestra una línea recta horizontal con el arco de media vuelta (`180º`).
- **👯 Ángulos Consecutivos**: Dibuja dos ángulos pegados que comparten el vértice y el lado central común (en color rojo/rosa), pero sin llegar a formar una línea recta.
- **🌈 Ángulos Adyacentes**: Dibuja dos ángulos consecutivos que comparten vértice y lado central, y cuyos lados exteriores forman una línea recta de `180º` (por ejemplo, `60º + 120º = 180º`).

---

### 2. Refuerzo Educativo con Sonidos (Web Audio API)
No necesita archivos MP3 externos (todo el sonido se sintetiza en tiempo real dentro del propio archivo HTML):
- **Sonido Agudo para el Ángulo Agudo**: Notas muy altas, cristalinas y brillantes (como un pajarito o flauta aguda) para asociar el concepto de *"ángulo agudo = sonido agudo"*.
- **Sonido Grave para el Ángulo Obtuso**: Notas bajas, profundas y gorditas (como una tuba o un elefante) para asociar *"ángulo obtuso/abierto = sonido grave"*.
- **Sonido Cuadrado para el Ángulo Recto (`90º`)**: Dos tonos firmes de onda cuadrada que marcan una esquina exacta.
- **Sonido Plano para el Ángulo Llano (`180º`)**: Un tono continuo, largo y horizontal sin subidas ni bajadas.
- **Sonido de 2 Pasos para Consecutivos**: Dos notas seguidas (*Do → Mi*) que suenan una al lado de la otra.
- **Sonido de 2 Pasos + Acorde 180º para Adyacentes**: Dos notas consecutivas que desembocan en un acorde plano completo.

---

### 3. Modo para 1 o 2 Jugadores (12 Rondas por Jugador)
- **Personalización**: Cada jugador puede escribir su nombre y elegir su propio avatar animal (`🦊`, `🐼`, `🦁`, `🐸`, `🦄`, `🦖`, etc.).
- **12 Rondas por jugador por defecto** (también permite elegir partidas rápidas de 6 o 10 rondas).
- **Turnos alternos en 2 Jugadores**:
  - *Ronda 1*: Turno del Jugador 1 ➔ Turno del Jugador 2.
  - *Ronda 2*: Turno del Jugador 1 ➔ Turno del Jugador 2.
  - Así sucesivamente hasta completar las **12 rondas de cada jugador**, con una ventana de aviso entre turnos para pasarse el teléfono móvil cómodamente.
- **Mazo equilibrado**: Garantiza que a lo largo de las 12 rondas a ambos jugadores les salgan todos los tipos de ángulos la misma cantidad de veces.

---

### 4. Laboratorio de Ángulos y Sonidos (Modo Aprender)
Incluye una pantalla de práctica libre donde el niño puede pulsar cualquiera de los 6 botones tantas veces como quiera para:
- Ver el dibujo clásico de ese ángulo (`40º`, `90º`, `120º`, `180º`, consecutivos y adyacentes).
- Escuchar su sonido característico y leer por qué se llama así antes de empezar la partida.

---

## 🚀 Cómo subirlo a GitHub Pages
1. Crea un repositorio nuevo en GitHub.
2. Sube el archivo `index.html` (y opcionalmente este `README.md`).
3. En **Settings ➔ Pages**, selecciona la rama `main` y guarda.
4. Abre el enlace desde tu teléfono móvil (incluso puedes pulsar *"Añadir a pantalla de inicio"* para usarlo como aplicación a pantalla completa).

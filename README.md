# JuanPa Arcade 🕹️

Colección de juegos clásicos de arcade para navegador, construidos en HTML, CSS y JavaScript modernos, sin dependencias externas.

---

## 🐍 Cyber Snake

Una reimplementación moderna y pulida del legendario juego Snake, autocontenida en un único archivo HTML (`index.html` / `snake.html`).

### ✨ Características
- **Gráficos Cyberpunk / Neón**: Estética retro-futurista, ojos dinámicos en la cabeza de la serpiente orientados en la dirección del movimiento, y efectos de partículas de neón.
- **Sintetizador de Audio Web Audio API**: Efectos de sonido generados por código (comer manzana, manzana dorada, choque, inicio de partida) sin dependencias ni archivos `.mp3`/`.wav` externos.
- **Frutas Especiales**: Manzanas doradas temporales con temporizador visual que otorgan +50 puntos.
- **🐰💣 Conejos Bomba (Obstáculos Dinámicos)**: Peligrosos conejos cibernéticos con mecha chispeante que aparecen a medida que avanzas en el juego. Chocar con uno provoca una explosión con vibración de pantalla (*screen shake*), sonido de detonación y partículas de fuego. Se pueden activar o desactivar desde el panel de opciones.
- **Selector de Dificultad**: Fácil, Normal y Difícil (con aumento progresivo de velocidad según el puntaje).
- **Modos de Pared**: Paredes sólidas clásicas o modo túnel (wrap-around).
- **Prevención de Suicidio Accidental**: Cola de direcciones inteligente con buffer para evitar giros imposibles en ráfagas rápidas de teclas.
- **Récords Guardados**: Almacenamiento local (`localStorage`) para persistir la puntuación máxima.
- **Multiplataforma y Responsivo**: Controles por teclado, gestos táctiles (swipe) y pad direccional virtual para móviles y tablets.
- **Gráficos nítidos en pantallas Retina / HiDPI**: Escalado automático según `devicePixelRatio`.

---

### 🎮 Controles

| Acción | Teclas / Control |
| :--- | :--- |
| **Moverse** | Flechas del cursor (`↑`, `↓`, `←`, `→`) o `W`, `A`, `S`, `D` |
| **Pausar / Reanudar** | `Espacio` o `P` |
| **Reiniciar partida** | `R` o botón en pantalla |
| **Móvil / Pantalla táctil** | D-Pad táctil en pantalla o deslizar el dedo (Swipe) |

---

### 🚀 Cómo jugar

1. Abre directamente `index.html` o `snake.html` en cualquier navegador web moderno (doble clic o arrastrando a Chrome, Safari, Firefox o Edge).
2. O inicia un servidor local rápido:
   ```bash
   # Con Python
   python3 -m http.server 8080
   # Luego abre http://localhost:8080 en tu navegador
   ```

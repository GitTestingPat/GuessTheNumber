# GUESS THE NUMBER

Un juego simple e interactivo donde debes adivinar el número secreto que la computadora ha elegido.

## 📝 Descripción

Guess The Number es un juego web clásico desarrollado con HTML, CSS y JavaScript vanilla. El objetivo es adivinar un número aleatorio generado por la computadora dentro de un rango específico. El juego proporciona pistas después de cada intento para ayudarte a encontrar el número correcto.

## 🎮 Características

- Interfaz limpia y fácil de usar
- Número aleatorio generado automáticamente
- Sistema de pistas (mayor/menor)
- Contador de intentos
- Opción para reiniciar el juego
- Diseño responsivo

## 🛠️ Tecnologías utilizadas

- **HTML5** - Estructura del documento
- **CSS3** - Estilos y diseño responsivo
- **JavaScript** - Lógica del juego e interactividad

## 📋 Requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- No se requieren instalaciones adicionales

## 🚀 Instalación y uso

1. **Clonar o descargar el repositorio**
   ```bash
   git clone [URL-del-repositorio]
   ```
   O descargar como ZIP y extraer los archivos.

2. **Navegar al directorio del proyecto**
   ```bash
   cd guess-the-number
   ```

3. **Abrir el juego**
   - Hacer doble clic en el archivo `index.html`, o
   - Abrir el archivo `index.html` con tu navegador preferido, o
   - Si tienes un servidor local instalado:
     ```bash
     # Con Python 3
     python -m http.server 3000
     
     # Con Node.js (si tienes http-server instalado)
     npx http-server -p 3000
     
     # Con PHP
     php -S localhost:3000
     ```
   Luego visitar `http://localhost:3000` en tu navegador.

## 📂 Estructura del proyecto

```
guess-the-number/
├── index.html          # Archivo principal del juego
├── styles.css          # Estilos CSS (si está separado)
├── script.js           # Lógica del juego en JavaScript (si está separado)
└── README.md           # Este archivo
```

## 🎯 Cómo jugar

1. Abre el archivo `index.html` en tu navegador
2. El juego generará automáticamente un número secreto
3. Ingresa tu suposición en el campo de entrada
4. Haz clic en "Adivinar" o presiona Enter
5. El juego te dará una pista:
   - "Muy alto" si tu número es mayor al secreto
   - "Muy bajo" si tu número es menor al secreto
   - "¡Correcto!" si adivinaste el número
6. Continúa adivinando hasta encontrar el número correcto
7. Usa el botón "Nuevo juego" para jugar otra ronda

## 🔧 Personalización

Puedes modificar fácilmente:

- **Rango de números**: Edita las variables en `script.js`
- **Estilos visuales**: Modifica `styles.css` o los estilos en `index.html`
- **Mensajes del juego**: Cambia los textos en el código JavaScript
- **Dificultad**: Ajusta el rango de números o agrega límite de intentos

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar el juego:

1. Fork del repositorio
2. Crea una rama para tu característica (`git checkout -b feature/nueva-caracteristica`)
3. Commit tus cambios (`git commit -am 'Agrega nueva característica'`)
4. Push a la rama (`git push origin feature/nueva-caracteristica`)
5. Crea un Pull Request

## 📝 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## ✨ Posibles mejoras

- [ ] Añadir diferentes niveles de dificultad
- [ ] Implementar sistema de puntuación
- [ ] Agregar efectos de sonido
- [ ] Crear animaciones CSS
- [ ] Añadir modo multijugador
- [ ] Implementar historial de puntuaciones

## 📧 Contacto

Si tienes preguntas o sugerencias, no dudes en contactarme.

---

¡Disfruta jugando Guess The Number! 🎯
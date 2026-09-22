# 🌻 Flores Amarillas — Developer Edition

Página web creada con **HTML, CSS y JavaScript** en un único archivo. Las fotos van incrustadas directamente en el `index.html` (no dependen de ninguna carpeta ni ruta externa), así no hay riesgo de que se rompan los enlaces al subirlo.

## Archivos

```text
floresamarillas/
├── index.html   (incluye las fotos incrustadas)
└── README.md
```

- `index.html`: contiene toda la página, estilos, animaciones y las 17 fotos ya incrustadas.
- `README.md`: información del proyecto.

## Publicar con GitHub Pages

1. Sube únicamente `index.html` y `README.md` al repositorio (no necesitas ninguna carpeta extra).
2. En GitHub entra en **Settings**.
3. Ve a **Pages**.
4. En **Build and deployment**, selecciona:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Guarda los cambios.

GitHub generará una dirección similar a:

```text
https://TU-USUARIO.github.io/floresamarillas/
```

## Características

- Diseño oscuro tipo programador.
- Terminal simulada con efecto de máquina de escribir.
- Flores amarillas creadas con CSS, con brillo pulsante.
- Animación de pétalos cayendo, corazones subiendo y luciérnagas doradas flotando.
- Galería de fotos con carrusel automático, flechas, puntos, miniaturas, swipe táctil y modo de foto ampliada (lightbox).
- Fotos incrustadas directamente en el HTML (base64), sin depender de rutas externas ni carpetas adicionales.
- Diseño responsive para celular y computadora.
- Sin librerías externas.
- Todo funciona desde un único archivo `index.html`.

---

`build: successful ✓`

# Pastora Invaders — La cruzada de los decretos

Videojuego web de sátira política en 8 bits, inspirado en Space Invaders. Funciona en celular y computadora, sin instalar nada.

## Cómo publicarlo
Sitio estático: sube esta carpeta a un repositorio de GitHub y créalo en Render como **Static Site** (sin comando de build, carpeta de publicación `.`).
Cuando tengas dominio, ponlo en `"shareUrl"` dentro de `index.html` (bloque `cfg`) y en `og:image` como URL absoluta.

## Contenido
- `index.html`: el juego completo (configuración de niveles, dificultad y puntos en el bloque `cfg`).
- `assets/`: sprites recortados de la hoja de MNRY, fuentes y `yape-qr.png`.
- `herramientas/extract.py`: vuelve a recortar los sprites desde `sheet.png` si cambias la hoja.

## Controles
- Celular: ◀ ▶ y DECRETO (mantener para disparo continuo), o arrastrar el dedo sobre el escenario.
- Computadora: flechas o A/D, espacio para disparar, P o ESC para pausar.

---
Videojuego de sátira política. Obra ficticia.
Desarrollado por MNRY · mantarraya.pe

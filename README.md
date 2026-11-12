# Bracket de octavos · Torneo de Smash Bros · Legado TCG x Smash & Snacks

Página estática (un solo `index.html`) con bracket de eliminación simple de 16 jugadores.
Los resultados se guardan en el navegador (localStorage).

## Logos
Pon tus imágenes en `logos/` con estos nombres (PNG con fondo transparente recomendado):

- `logos/legado.png` (izquierda)
- `logos/smash.png` (centro, junto al título)
- `logos/smash-snacks.png` (derecha)

Si falta alguno, se muestra un recuadro de aviso en su lugar.

## Probar en local
Abre `index.html` en el navegador.

## Desplegar en Portainer
1. Sube esta carpeta a un repositorio de GitHub.
2. En Portainer: **Stacks → Add stack → Repository**.
3. URL del repo, rama `main`, ruta del compose `docker-compose.yml`.
4. **Deploy the stack**. Queda en `http://IP_DEL_SERVIDOR:8090`.

Para actualizar: haz commit en GitHub y en el stack pulsa **Pull and redeploy**.

## Alternativa: GitHub Pages
Settings → Pages → Deploy from branch → `main` / root.

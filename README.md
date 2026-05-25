# Editor de Materialidad de Ropa en Imágenes

Aplicación web local para cambiar la materialidad de zonas de ropa en una imagen.

## Funciones principales

- Cargar una imagen desde el equipo.
- Dos ventanas: imagen de edición y resultado.
- Pintar manualmente la zona de ropa a modificar.
- Borrar selección con pincel.
- Aplicar materialidades procedurales:
  - Madera
  - Plástico
  - Malla / red
  - Papel
  - Metal satinado
  - Cuero
  - Tela gruesa
- Ajustar color base, intensidad, escala de textura y conservación de sombras.
- Descargar el resultado en PNG.
- Copiar el resultado para seguir editando por etapas.

## Uso

1. Abre `index.html` en un navegador moderno.
2. Carga una imagen.
3. Pinta sobre la ropa.
4. Elige materialidad y ajustes.
5. Presiona **Aplicar materialidad**.
6. Descarga la imagen modificada.

## Instalación en GitHub Pages

1. Crea un repositorio.
2. Sube `index.html`.
3. En GitHub, entra a **Settings > Pages**.
4. En **Branch**, selecciona `main` y carpeta `/root`.
5. Guarda. GitHub entregará un enlace público para abrir la app.

## Nota técnica

La aplicación no usa inteligencia artificial ni sube imágenes a servidores. La edición se realiza localmente con HTML5 Canvas. Para mejores resultados, selecciona cuidadosamente la zona de ropa con el pincel.
